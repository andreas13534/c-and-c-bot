# Fair Play AI Mod Pack (RA2 / Yuri's Revenge)

Dieses Repository enthält eine **faire KI-Mod** für CnCNet-kompatible RA2/YR-Matches.

## Ziele
- Keine Cheat-Boni (kein Extra-Income, keine Buildspeed-Boni, keine Free Units, keine versteckte Vision).
- KI-Stärke über Entscheidungen: bessere BOs, Scout-Zyklen, Countering, Multi-Wave-Pressure.
- Multiplayer-tauglich auf CnCNet, sofern alle Spieler dieselben Mod-Dateien nutzen.

## Struktur
- `mod/YR/aimd.ini` – Haupt-KI für Yuri's Revenge.
- `mod/RA2/ai.ini` – RA2-Variante mit denselben Designprinzipien.
- `docs/build-orders.md` – 3–5 Build Orders pro Fraktion inkl. Timing-Ziele.
- `docs/testplan.md` – 10 konkrete Test-Szenarien mit Metriken.

## Integration
1. YR: `aimd.ini` in den Mod-Ordner legen und über CnCNet mit identischer Datei verteilen.
2. RA2: `ai.ini` analog einsetzen.
3. Keine `rulesmd.ini`-Power-Buffs nötig; nur AI-Dateien werden angepasst.
