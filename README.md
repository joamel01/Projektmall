# Projektnamn

Kort beskrivning av projektet, syfte och målbild.

## Struktur

- `00-admin` - projektstyrning, planering, budget och övergripande administration.
- `01-krav` - krav, user stories, acceptanskriterier och scope.
- `02-analys` - nuläge, processer, risker, beroenden och tekniska analyser.
- `03-design` - arkitektur, lösningsskisser, UX/UI, datamodeller och beslutade mönster.
- `04-implementation` - kod, tester och scripts.
- `05-data` - rådata och bearbetade datafiler.
- `06-dokumentation` - teknisk och funktionell dokumentation, inklusive Codex-arbetsflöde.
- `07-leveranser` - färdiga leveranser, exportfiler och releasepaket.
- `08-moten` - mötesanteckningar och agendor.
- `09-beslut` - beslut, ADR:er och vägval.
- `10-arkiv` - äldre material som sparas men inte längre är aktivt.
- `assets` - bilder, diagram och andra resurser.
- `config` - konfigurationsmallar och miljöinställningar.
- `logs` - lokala loggar och körningar. Innehåll ignoreras av Git som standard.
- `prompts` - återanvändbara promptmallar för Codex-arbete.
- `reports` - statusrapporter, analyser och sammanställningar.

## Codex-stöd

- `AGENTS.md` - arbetsinstruktioner för Codex och andra AI-agenter.
- `prompts/` - promptmallar för implementation, kodgranskning, dokumentation och felsökning.
- `06-dokumentation/codex-arbetsflode.md` - rekommenderat arbetssätt med Codex.
- `reports/codex-log.md` - löpande arbetslogg för AI-assisterade ändringar.
- `.env.example` - exempel på lokala miljövariabler utan verkliga hemligheter.

## Kom igång

1. Fyll i projektnamn, ägare och mål i `00-admin/projektkort.md`.
2. Samla krav i `01-krav/kravlista.md`.
3. Dokumentera viktiga beslut i `09-beslut/ADR-0001-mall.md`.
4. Håll korta arbetsuppgifter i `TODO.md`.
5. Läs `AGENTS.md` innan du ber Codex göra större ändringar.
6. Lägg löpande status i `reports/statusrapport.md`.
