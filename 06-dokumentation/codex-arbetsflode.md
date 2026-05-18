# Codex-arbetsflöde

Den här guiden beskriver hur projektet kan användas tillsammans med Codex.

## När du startar en uppgift

Ge Codex tydlig kontext:

- Vad som ska göras.
- Vilka filer eller mappar som är relevanta.
- Om ändringen ska vara minimal eller om större omstrukturering är okej.
- Vilka kontroller som ska köras efteråt.

Exempel:

```text
Läs AGENTS.md och uppdatera kravlistan med nya krav för importflödet. Ändra bara filer under 01-krav och uppdatera TODO.md med eventuella följduppgifter.
```

## Under arbetet

Codex bör:

- Läsa relevant dokumentation innan ändring.
- Göra små ändringar i rätt mapp.
- Undvika att skapa nya strukturer om befintliga mappar räcker.
- Uppdatera `TODO.md`, `CHANGELOG.md` eller `reports/codex-log.md` när det är motiverat.

## Efter arbetet

En bra slutsummering från Codex bör innehålla:

- Vad som ändrades.
- Vilka filer som berördes.
- Vilka kontroller som kördes.
- Vad som eventuellt återstår.

## Bra promptar

Återanvändbara promptmallar finns i `prompts/`.
