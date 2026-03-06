# Wassergenossenschaften Sulzberg — Homepage Design

## Überblick

Homepage für die 4 Wassergenossenschaften der Gemeinde Sulzberg (Vorarlberg):
- Wassergenossenschaft Sulzberg-Kirchdorf (erste Umsetzung)
- Wassergenossenschaft Sonnenseite (später)
- Wassergenossenschaft Hinterberg (später)
- Wassergenossenschaft Thal (später)

Referenz: wg-mellau.at

## Technik

- Statisches HTML/CSS/JS, kein Build-Step
- Hosting: GitHub Pages
- Responsive Design

## Struktur

```
/
├── index.html              ← Landing Page mit Karte
├── kirchdorf/index.html    ← WG Sulzberg-Kirchdorf
├── assets/
│   ├── style.css
│   └── Wasserturm.jpg
└── data/
    └── kirchdorf.json      ← Inhalte als JSON (für spätere Erweiterung)
```

## Landing Page

- Übersichtskarte von Sulzberg (Leaflet/OpenStreetMap)
- 4 Gebiete der Genossenschaften eingezeichnet
- Kirchdorf klickbar → führt zu /kirchdorf/
- Andere 3 Gebiete ausgegraut mit "Demnächst"

## Genossenschafts-Seite (One-Pager)

1. **Hero** — Wasserturm-Foto, Name der Genossenschaft
2. **Über uns** — Kurztext, Kennzahlen (261 Anschlüsse, 95.000 m³/Jahr, 5 Pumpwerke)
3. **Kosten** — Gebührentabelle (Wasserpreis, Grundgebühr, Zählermiete, Anschlussgebühr)
4. **Wasserqualität** — Eingebetteter PDF-Untersuchungsbericht, Wasserhärte (12°dH)
5. **Kontakt** — Obmann, Adresse, Telefonnummer

## Design

- Hellblauer Hintergrund (#e8f4f8), dunkelblaue Überschriften (#1a3a5c)
- Clean, ruhiges Layout angelehnt an wg-mellau.at
- Hero-Bild: Wasserturm.jpg
