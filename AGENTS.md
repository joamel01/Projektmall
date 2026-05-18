# AGENTS.md

Instruktioner för Codex och andra AI-agenter som arbetar i detta repo.

## Grundregler

- Läs `README.md` och relevant dokumentation innan du ändrar filer.
- Håll ändringar små, tydliga och kopplade till uppgiften.
- Ändra inte filer utanför uppgiftens område utan att det behövs.
- Lägg inte in hemligheter, tokens, lösenord, nycklar eller kunddata i repot.
- Använd `.env.example` för exempel på miljövariabler och lokala `.env`-filer för verkliga värden.
- Dokumentera viktiga vägval i `09-beslut/` som ADR när beslutet påverkar framtida arbete.
- Uppdatera `TODO.md` när nya uppgifter upptäcks eller slutförs.
- Uppdatera `CHANGELOG.md` vid ändringar som påverkar mallens användning.
- Skriv kort arbetsnotering i `reports/codex-log.md` när större ändringar görs.

## Språk och stil

- Skriv dokumentation på svenska om inget annat anges.
- Använd tydliga rubriker, korta stycken och konkreta checklistor.
- Föredra praktiska exempel framför abstrakta instruktioner.
- Håll filnamn beskrivande och konsekventa.

## Rekommenderat arbetsflöde

1. Förstå uppgiften och identifiera berörda filer.
2. Kontrollera befintlig struktur och följ lokala mönster.
3. Gör minsta rimliga ändring som löser uppgiften.
4. Kör relevanta kontroller om projektet har test-, lint- eller byggkommandon.
5. Summera ändringar, kontroller och eventuella kvarstående risker.

## Kommandon

Projektmallen är teknikneutral. När ett konkret projekt skapas bör dessa kommandon fyllas i:

```powershell
# Test

# Lint

# Format

# Build
```

## Känsligt innehåll

Följande ska aldrig commitas:

- `.env` eller andra lokala konfigurationsfiler med verkliga värden.
- API-nycklar, access tokens, certifikat eller privata nycklar.
- Personuppgifter, kunddata eller produktionsdata.
- Stora loggfiler, exportfiler eller temporära datafiler.

## När du är osäker

- Fråga hellre än att göra antaganden som kan påverka säkerhet, data eller leverans.
- Om något ser ut som en hemlighet: stoppa, rapportera fyndet och föreslå borttagning/rotation.
