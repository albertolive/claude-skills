---
name: catalan-natural
description: >
  Escriu i revisa text en català correcte i natural: corregeix castellanismes i
  barbarismes, calcs de l'anglès (catalanglish), errors de pronoms febles,
  per/per a, gerundi de posterioritat, diacrítics i apostrofació. Cobreix
  qualsevol prosa de cara a l'usuari: UI, copy, landing pages, docs, correus,
  missatges, comentaris. S'activa quan generes o revises text català, o quan
  l'usuari diu "millora el català", "sona traduït", "catalanglish", "revisa el
  text en català", "fes-ho més natural". També invocable amb /catalan-natural.
version: 1.0.0
author: albertolive
license: MIT
tags:
  - catala
  - catalan
  - language
  - linguistics
  - writing
  - localization
  - proofreading
---

# català natural

Fes que el català soni correcte i escrit per algú d'aquí. Dues fonts
d'interferència delaten el mal català: el **castellà** (barbarismes, calcs
sintàctics) i l'**anglès** (catalanglish, traducció massa literal). Aquest skill
cobreix totes dues, més els errors gramaticals propis més freqüents.

Aplica-ho sempre que escriguis o revisis prosa catalana de cara a l'usuari.

## Regla d'or

El mal català rarament és un problema de paraula solta: és **to i estructura**.
El català natural és curt, directe i fa servir formes ja establertes. Quan
dubtis, llegeix-ho en veu alta: si una persona d'aquí no ho diria parlant,
reescriu-ho. Referència de naturalitat: el registre periodístic (premsa, ràdio,
Viquipèdia, ésAdir).

## A. Interferència del castellà (la font principal)

### Barbarismes lèxics

| Incorrecte (castellanisme) | Correcte |
|---|---|
| bueno / vale | bé / d'acord |
| disfrutar | gaudir |
| entregar | lliurar, donar |
| logro | assoliment, èxit |
| apoyar | donar suport |
| susto | ensurt, espant |
| novio / novia | xicot/xicota, parella |
| a lo millor | potser, tal vegada |
| vivenda | habitatge (preferit en registre formal) |
| realitzar (com a "fer" genèric) | fer (reserva "realitzar" per a un projecte o pla) |
| problemàtica (com a sinònim de "problema") | problema |

Expressions **tolerades però millorables** (no són error dur, però en estil
acurat val més evitar-les): "en base a" → "a partir de" / "d'acord amb"; abús de
"realitzar" i "tema/temàtica".

### Calcs sintàctics del castellà

- **tenir que** → **haver de** ("tinc que anar" → "he d'anar")
- **donar-se compte** → **adonar-se** ("me'n dono compte" → "me n'adono")
- **lo** neutre → **el que / allò / això** ("lo important" → "el que és important")
- **el mateix / la mateixa** com a pronom anafòric → **aquest / aquest darrer / ho**
  ("el president va parlar; el mateix va dir…" → "…; aquest va dir…")
- **degut a que / degut que** → **perquè / a causa del fet que**. (Atenció:
  "degut a" + un nom SÍ que és correcte —"a causa de la pluja" i "degut a la
  pluja" valen totes dues—; l'error és només "degut a que".)
- **doncs** com a causal → **perquè / ja que** ("no vinc, doncs tinc feina" → "no
  vinc perquè tinc feina"). "Doncs" és consecutiu, no causal.
- **a nivell de** → **pel que fa a / quant a** ("a nivell econòmic" → "quant a
  l'economia")

## B. Calcs de l'anglès (catalanglish)

| Anglès / calc dolent | Català natural |
|---|---|
| where the week is heading → "cap on va la setmana" | "l'evolució de la setmana" |
| in plain words → "en paraules normals" | "amb un llenguatge planer" |
| during the morning hours → "durant les hores del matí" | "al matí" |
| at this point in time → "en aquest moment del temps" | "ara mateix" / "de moment" |
| chance of X → "oportunitat de X" | "probabilitat de X" / "risc de X" |
| feel free to → "sent-te lliure de" | "si vols" / "quan vulguis" |
| customize → "customitzar" | "personalitzar" |
| event → "event" | "esdeveniment" |

- **Imperatiu calcat amb subjuntiu** (de *Know…/Be sure…*): sona forçat en un
  titular. ❌ "Sàpigues quin temps farà" → ✅ "Descobreix…" / "Estigues al dia de…"
- **Veu passiva anglesa → activa o pronominal**: ❌ "el sistema serà implementat"
  → ✅ "s'implementarà el sistema". ❌ "està localitzat a" → ✅ "es troba a".
- **`tenir` calcat de *you have*** → verb d'acció: ❌ "tens el resum al correu" →
  ✅ "reps el resum al correu".
- **2a persona contínua descrivint un procés general** → impersonal: ❌ "el
  llegeixes en un minut" (descrivint el producte) → ✅ "es llegeix en un minut".
  (Manté la 2a persona quan t'adreces directament a l'usuari: "apunta-t'hi".)

## C. Gramàtica que falla sovint

- **`hi han` → `hi ha`**: el verb "haver-hi" és impersonal i no concorda mai.
  ❌ "hi han molts problemes" → ✅ "hi ha molts problemes". Amb quantitat
  pressuposada: "Quants n'hi ha? N'hi ha tres."
- **`els hi` datiu → `els`**: ❌ "els hi demanaré l'informe" → ✅ "els demanaré
  l'informe".
- **`fins` + article/temps → `fins a`**: ❌ "fins l'últim dia" → ✅ "fins a
  l'últim dia"; ❌ "obert fins les 8" → ✅ "fins a les 8".
- **`per` vs `per a`**: `per` = causa, mitjà, temps, en nom de ("ho faig per
  amor"); `per a` = finalitat, destinatari ("pa per a la Maria", "eina per a
  professionals"). Davant d'infinitiu de finalitat, en registre central s'admet
  sovint només `per` ("una eina per editar").
- **Gerundi de posterioritat (incorrecte)**: el gerundi expressa simultaneïtat o
  anterioritat, mai una acció posterior. ❌ "va caure, trencant-se el braç" → ✅
  "va caure i es va trencar el braç".
- **Apostrofació**: `el/la` + vocal o `h` muda → apòstrof ("l'home", "l'hora").
  `la` NO s'apostrofa davant `i`/`u` àtones ("la universitat", "la infermera")
  ni davant "una" (hora), "ira", "host". `de` + vocal → "d'avui". `per` no
  s'apostrofa mai.
- **Diacrítics (reforma IEC 2017)**: només queden 15 parells —
  bé/be, déu/deu, és/es, mà/ma, més/mes, món/mon, pèl/pel, què/que, sé/se,
  sí/si, són/son, sòl/sol, té/te, ús/us, vós/vos. La resta van perdre l'accent
  ("adeu", "os", "dona" sense accent). No posis diacrítics fora d'aquesta llista.

## D. Puntuació i accentuació

- **Cometes**: jerarquia catalana «1r nivell», després "2n", després '3r'. El
  primer nivell és la cometa baixa «», no l'anglesa "". ❌ "text" → ✅ «text».
- **Ratlla (—)**: és el signe correcte per a incisos (amb espais: "l'eina —ràpida—
  funciona") i diàlegs (sense espai darrere: "—Hola"). No la confonguis amb el
  guionet (-), que només uneix mots. Nota pràctica: en copy web curt queden més
  nets els parèntesis o les comes que la ratlla.
- **Punts suspensius**: sempre tres, enganxats a la paraula ("espera…").
- **Espais amb signes**: sense espai abans de , ; : ? ! — però amb espai abans de
  la unitat o el símbol: "50 %", "15 km", "25 €" (a diferència de l'anglès, que
  els enganxa).
- **Xifres i moneda**: separador decimal = **coma**, separador de milers =
  **punt** ("1.234,50"). El símbol de moneda va **DESPRÉS** de la xifra i amb
  espai: ✅ "5 €", "0,71 €" — ❌ "€5", "€0.71" (això és anglès). Vigila la
  coherència: no barregis "0,50" amb "€0.71" al mateix text.
- **Majúscules**: en català van en MINÚSCULA els dies (dilluns), mesos (abril),
  estacions (tardor), idiomes i gentilicis (el català, un anglès) i càrrecs
  genèrics (la presidenta). Posar-los en majúscula és calc de l'anglès/castellà.
- **Accent obert/tancat**: la `a` sempre oberta (à); `i`/`u` sempre tancades
  (í, ú); `e` i `o` poden ser totes dues. Regla bàsica: terminacions verbals →
  tancat (cantaré, parló); agudes no verbals → è/ó (cafè, sabó); planes i
  esdrúixoles → obert (telèfon, època). [Varia per dialecte: el valencià fa
  "café/francés" amb tancat; tots dos són normatius dins el seu estàndard.]
- **Dièresi**: marca que la vocal no forma diftong (raïm, diürn). Excepcions
  SENSE dièresi: sufixos -isme/-ista (egoisme), i l'infinitiu, gerundi, futur i
  condicional dels verbs en -ir (agrair, conduiré). Si la vocal ja porta accent,
  no s'hi posa dièresi (veí).

## E. Estil i registre

- **Mots crossa a retallar**: "actualment", "en temps real", "detallat",
  "condicions", quan no aporten res.
- **Excés d'adjectius**: l'anglès de màrqueting n'apila; el català en posa menys.
- **Frases llargues** encadenant subordinades a l'estil anglès: parteix-les.
- **Registre coherent**: tria "tu" (producte/web informal) o "vós/vostè"
  (formal) i mantén-lo de dalt a baix. No barregis.
- **Col·loquialismes** ("au", "plega"): genuïns, però si la resta del text és
  neutre, un de sol sona postís. O to proper de debò, o neutre. No a mitges.

## Checklist abans de donar el text per bo

1. Castellanismes lèxics (taula A) substituïts?
2. "tenir que", "lo" neutre, "degut a", "doncs" causal, "a nivell de" corregits?
3. `hi han` → `hi ha`? `els hi` → `els`?
4. `fins` davant d'article → `fins a`?
5. Calcs de l'anglès (taula B) substituïts? Cap passiva evitable?
6. Cap gerundi de posterioritat?
7. Apostrofació i diacrítics (15 parells) dins de norma?
8. Cometes «», espai abans d'unitats (15 km, 50 %), moneda després de la xifra
   amb coma decimal (0,50 €), dies/mesos/idiomes en minúscula?
9. Accents oberts/tancats i dièresi correctes?
10. Mots crossa i adjectius sobrers retallats? Registre coherent?
11. **Test de veu alta**: ho diria així una persona d'aquí?

## Quan dubtis

No improvisis amb formes dubtoses (preposició, règim verbal, barbarisme). Abans
d'afirmar que una forma és correcta, consulta l'**Optimot** (optimot.gencat.cat),
el diccionari de l'**IEC** (dlc.iec.cat), la **guia d'estil de Softcatalà** o
l'**ésAdir** (esadir.cat). Si no ho has pogut verificar, digues-ho.
