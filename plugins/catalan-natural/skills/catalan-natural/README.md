# catalan-natural

Claude Code skill that writes and reviews **correct, natural Catalan**, fixing the two main sources of bad Catalan: interference from Spanish (castellanismes, barbarismes) and from English (calques, *catalanglish*).

## What it covers

- **Castellanismes** — lexical (*disfrutar* → gaudir, *vivenda* → habitatge) and syntactic (*tenir que* → haver de, *lo* neutre, *a nivell de*).
- **English calques** — overuse of the passive, *tens* for *reps*, calqued second person, over-literal expressions.
- **Grammar** — *hi han* → *hi ha*, *els hi* dative, *fins a*, *per* vs *per a*, gerund of posteriority.
- **Diacritics** — the 15 accent pairs kept after the 2017 IEC reform.
- **Apostrophation** — cases and exceptions.
- **Punctuation** — low quotes « », dash, spacing, capitalisation (days, months, languages in lowercase).
- **Accentuation** — open vs closed accent (with a Valencian dialect note), diaeresis and its exceptions.
- **Numbers and currency** — decimal comma, thousands dot, symbol after the figure with a space (`0,50 €`).

Every rule is sourced from official references: IEC/GIEC, Optimot, ésAdir (3Cat), the Softcatalà style guide and the UB.

## Install

```
/plugin marketplace add albertolive/claude-skills
/plugin install catalan-natural@albertolive-skills
```

The skill auto-activates when you generate or review Catalan text.

## License

MIT
