# Jarvis 🤖

Jarvis är AI-teamet som hjälper till att driva **SnöTass**.

## Så använder du Jarvis
1. Starta en Claude Code-session med det här repot.
2. Skriv vad du vill, till exempel:
   - "Jarvis, kör trendspanaren"
   - "Jarvis, jämför leverantörer för hundtäcken"
   - "Jarvis, skriv en produkttext för tassvaxet"
   - "Jarvis, svara på det här kundmejlet: …"
3. Resultaten sparas i `rapporter/`.

## Mappar
- `CLAUDE.md` – Jarvis hjärna och regler
- `.claude/agents/` – en fil per agent
- `kunskap/` – fakta om butiken, leverantörer och varumärke
- `rapporter/` – allt agenterna producerat

## Lägga till en ny agent
Kopiera en fil i `.claude/agents/`, byt `name`, `description` och instruktionerna. Lägg till agenten i tabellen i `CLAUDE.md`.
