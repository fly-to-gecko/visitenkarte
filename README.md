# Visitenkarte QR

Kleine App (PWA) für iPhone, Android und PC: Kontaktdaten eintragen, daraus
eine Visitenkarte mit vCard-QR-Code erzeugen – als Bild im Quer- und
Hochformat fürs Handy und als Druckvorlage 85 × 55 mm (PDF/PNG, 3 mm Beschnitt).
Mehrere Karten mit eigenen Daten, Designs „Standard“ und „belCAT-Briefkopf“.

Die eingegebenen Daten bleiben nur im Browser des jeweiligen Geräts.

## Aufs Handy bringen

- **iPhone:** Adresse in Safari öffnen → Teilen-Symbol → „Zum Home-Bildschirm“.
- **Android:** Adresse in Chrome öffnen → Menü → „App installieren“.

Danach vom Icon starten. Die App läuft dann auch ohne Internet
(ohne Netz mit Systemschrift statt Sora/Inter).

## Später ändern

Geänderte Datei hochladen und in `sw.js` die Zeile
`const CACHE = PREFIX + "v1";` auf `v2`, `v3` usw. erhöhen.
