# Testplan (10 Szenarien)

Alle Tests als BO3 je Matchup/Mapgröße, jeweils mit identischer Mod-Datei für alle Clients.

## Gemessene Metriken
- Zeit bis erste Scout-Einheit sichtbar
- Zeit bis erste Angriffswelle (und Wave-Größe)
- Zeit bis zweite Raffinerie/Slave Miner
- Zeit bis erstes Tech-Upgrade (Radar/Battle Lab/äquivalent)
- Harvester-Verluste (pro Minute und gesamt)
- APM-nahe Aktivität proxy: TeamType-Spawn-Rate pro 2 Minuten
- Army Value Trade (vernichtet/verloren)
- Expansion-Timing (erste externe Ore-Node)

## Szenarien

1. **Kleine Map, Mirror Rush (Allies vs Allies)**
   - Ziel: Anti-Rush-BO Stabilität, frühe Scouts, keine Idle-Army.

2. **Kleine Map, Soviets vs Allies Fast Pressure**
   - Ziel: Rhino-Hit&Retreat vs IFV/GI-Defence Verhalten.

3. **Mittlere Map, Yuri vs Soviets Standard**
   - Ziel: Gatt/Magnetron Counter-Entscheidungen ohne Snowball-Cheat.

4. **Mittlere Map, Allies vs Yuri Air-heavy**
   - Ziel: AA-Reaktionszeit, Anti-Air Team-Auslösung (<= 30 s nach Sichtkontakt).

5. **Große Map, Soviets vs Allies Macro**
   - Ziel: Expansion vor 03:30, Wave-Frequenz statt 1 großer All-in.

6. **Große Map, Yuri vs Allies Tech Turtle Gegner**
   - Ziel: Harass-Cycles gegen Ökonomie statt Frontalverlust.

7. **Oil-Map aktiv, Allies vs Soviets**
   - Ziel: Oil-Capture Team priorisiert, aber nicht auf Kosten der Basisverteidigung.

8. **Bridge/Choke Map, Soviets vs Yuri**
   - Ziel: Choke-Hold Scripts, Positioning und nicht-statische Army.

9. **Fast Rush Gegner (manuell aggressiver Human-Build simuliert)**
   - Ziel: Refinery-Sicherheit, Harvester-Death < 2 bis Minute 4.

10. **Air Heavy + Multi-Harass (2 Fronten)**
    - Ziel: Dynamische Team-Erzeugung (AA + Harv-Defence) ohne Eco-Kollaps.

## Abnahme-Kriterien
- Erste Angriffswelle konsistent zwischen 01:20 und 02:10.
- Harvester-Deaths im Mittel mindestens 25% niedriger als Vanilla-AI in denselben Szenarien.
- Keine ungewöhnlichen Öko-/Buildspitzen, die auf Cheat-Boni hindeuten.
- KI wechselt in mindestens 7/10 Szenarien sichtbar den Unit-Mix nach Scout-Info.
