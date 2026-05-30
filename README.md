# claude-skills

Marketplace de [skills de Claude Code](https://code.claude.com/docs/en/custom-skills) mantingut per [albertolive](https://github.com/albertolive).

## catalan-natural

Skill per escriure i revisar text en **català correcte i natural**, no traduït automàticament de l'anglès (*catalanglish*) ni interferit pel castellà. Cobreix qualsevol prosa de cara a l'usuari: interfícies, copy, landing pages, documentació, correus i missatges.

### Què corregeix

- **Castellanismes i barbarismes** — lèxics (*disfrutar* → gaudir, *vivenda* → habitatge) i sintàctics (*tenir que* → haver de, *lo* neutre, *a nivell de*).
- **Calcs de l'anglès** — passiva excessiva, *tens* per *reps*, 2a persona calcada, expressions traduïdes massa literalment.
- **Gramàtica** — *hi han* → *hi ha*, *els hi* datiu, *fins a*, *per* vs *per a*, gerundi de posterioritat.
- **Diacrítics** — els 15 parells de la reforma de l'IEC del 2017.
- **Apostrofació** — casos i excepcions.
- **Puntuació** — cometes baixes «», ratlla, espais amb signes, majúscules (dies, mesos, idiomes en minúscula).
- **Accentuació** — accent obert/tancat (amb nota dialectal valenciana), dièresi i excepcions.
- **Xifres i moneda** — coma decimal, punt de milers, símbol després de la xifra amb espai (`0,50 €`).

Cada regla està verificada contra fonts oficials: IEC/GIEC, Optimot, ésAdir (3Cat), guia d'estil de Softcatalà i la UB. No surt de memòria.

### Instal·lació

```
/plugin marketplace add albertolive/claude-skills
/plugin install catalan-natural@albertolive-skills
```

Després, recarrega amb `/reload-plugins`. El skill s'activa sol quan generes o revises text català, o manualment amb `/catalan-natural:catalan-natural`.

### Ús manual

```
/catalan-natural:catalan-natural

[enganxa aquí el text català que vols revisar]
```

## Llicència

[MIT](./LICENSE)
