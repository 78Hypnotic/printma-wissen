# SOP: Standardversand

> Standardablauf für jeden DHL-Versand bei PrintMa

## Vorbereitung

- [ ] Bestellung prüfen (Quelle: Amazon / Shopify / TikTok)
- [ ] Adresse auf Richtigkeit prüfen (Strasse, PLZ, Ort)
- [ ] Richtige Boxengrösse wählen:
  - **Standard:** 22x16x8 cm → für Artikel bis 200g
  - **Gross:** 30x20x10 cm → für Artikel 200-500g
  - **XL:** 40x30x15 cm → für Artikel >500g

## Versandboxen

| Grösse | Verwendung | Material |
|---|---|---|
| 22x16x8 | Kleine Teile, Ringe, Ohrringe | Wellpappe |
| 30x20x10 | Mittelgrosse Teile | Wellpappe |
| 40x30x15 | Gross, mehrere Teile | Wellpappe |

Bestellung der Boxen: [DHL Verpackungsmaterial](https://www.dhl.de/)

## Label erstellen

1. DHL GKP Portal öffnen: [entwickler.dhl.de](https://entwickler.dhl.de/)
2. Neues Versandlabel generieren via API
3. Label als PDF speichern
4. Label auf A4/A6 drucken

## Verpacken

1. Ware in Box legen (ggf. mit Polstermaterial)
2. Rechnung/Lieferschein beilegen
3. Label aussen auf die Box
4. **Beutel-Typen:**
   - DHL Beutel für Dokumente
   - Kartonbox für 3D-Teile

## Abgabe

- [ ] Beim nächsten DHL Abgabepunkt abgeben
- [ ] QR-Code / Einlieferungsbeleg aufbewahren
- [ ] Sendungsnummer in Bestellung eintragen

## Troubleshooting

| Problem | Lösung |
|---|---|
| Label druckt nicht | PDF öffnen, anderen Drucker wählen |
| Falsche Adresse | Bei Amazon/Shopify stornieren, neu anlegen |
| Paket zu schwer | DHL Grenze prüfen (max 31.5kg) |
| GKP API Fehler | Logs prüfen, ggf. manuell via Portal |

## Checkbox-Tracking

- [ ] Ware verpackt
- [ ] Label gedruckt
- [ ] Sendungsnummer notiert
- [ ] Abgabeort dokumentiert