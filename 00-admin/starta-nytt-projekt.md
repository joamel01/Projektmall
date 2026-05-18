# Starta nytt projekt från mallen

Använd den här checklistan när du kopierar projektmallen till ett nytt projekt.

## 1. Byt grundinformation

- Byt projektnamn i `README.md`.
- Fyll i `00-admin/projektkort.md`.
- Beskriv syfte, mål, omfattning och avgränsningar.
- Lägg in kända intressenter och ansvariga roller.

## 2. Anpassa Codex-instruktioner

Gå igenom `AGENTS.md` och fyll i projektspecifika regler.

Minst detta bör kontrolleras:

- Språk och dokumentationsstil.
- Vilka mappar Codex får ändra för olika typer av uppgifter.
- Test-, lint-, format- och build-kommandon.
- Regler för känsligt innehåll, data och loggar.
- Om Codex ska uppdatera `TODO.md`, `CHANGELOG.md` eller `reports/codex-log.md` vid varje större ändring.

## 3. Anpassa teknisk struktur

- Välj teknikstack och dokumentera den i `04-implementation/README.md`.
- Lägg källkod i `04-implementation/src`.
- Lägg tester i `04-implementation/tests`.
- Lägg scripts i `04-implementation/scripts`.
- Lägg projektets konfigurationsmallar i `config`.

## 4. Hantera miljövariabler och hemligheter

- Uppdatera `.env.example` med projektets miljövariabler.
- Använd bara exempelvärden eller platshållare i `.env.example`.
- Lägg verkliga värden i lokal `.env`.
- Kontrollera att `.env` och andra känsliga filer ignoreras av Git.

## 5. Starta krav och beslut

- Skapa första kravbilden i `01-krav/kravlista.md`.
- Dokumentera viktiga antaganden och risker i `02-analys/risklogg.md`.
- Skriv första större vägvalet som ADR i `09-beslut/` om projektet redan har ett tydligt arkitektur- eller teknikbeslut.

## 6. Anpassa promptar

Behåll grundpromptarna i `prompts/` och lägg till projektspecifika promptar vid behov.

Bra kandidater:

- Feature-prompt för projektets vanligaste utvecklingsflöde.
- Kodgranskningsprompt med projektets riskområden.
- Dokumentationsprompt med rätt målgrupp och ton.
- Felsökningsprompt med vanliga logg- och driftplatser.

## 7. Första kontrollen

Innan projektet börjar användas skarpt:

- Kontrollera att `README.md` inte längre beskriver bara mallen.
- Kontrollera att `AGENTS.md` passar det nya projektet.
- Kontrollera att inga hemligheter eller lokala data har följt med.
- Kör en enkel `git status` och granska alla filer innan första commit.

## Rekommenderad första Codex-prompt

```text
Läs AGENTS.md, README.md och 00-admin/starta-nytt-projekt.md. Granska om projektet är korrekt initierat från mallen. Föreslå eller gör små förbättringar, men lägg inte till någon teknikstack utan att fråga först.
```
