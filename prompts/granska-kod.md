# Prompt: Granska kod

Använd när Codex ska göra en kodgranskning eller riskgranskning.

```text
Läs AGENTS.md först och inta kodgranskningsläge.

Granska:
[Beskriv branch, PR, filer eller ändring]

Fokusera på:
- Buggar och regressionsrisker.
- Säkerhet och hemligheter.
- Testluckor.
- Otydlig ansvarsfördelning eller svårförvaltad kod.

Svara med:
- Fynd först, sorterade efter allvarlighetsgrad.
- Fil- och radreferenser där det går.
- Kort sammanfattning efter fynden.
- Säg tydligt om inga blockerande fynd hittas.
```
