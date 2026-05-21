# SOP: Bestellung prüfen

> Wann und wie eingehende Bestellungen geprüft werden

## Kanäle überwachen

| Kanal | Zugang | Häufigkeit |
|---|---|---|
| **Shopify** | Shopify Admin + Email | Täglich |
| **Amazon Seller** | Seller Central + Email | Täglich |
| **TikTok Shop** | TikTok Seller Center | Täglich |
| **Email** | printmagbr@gmail.com (IMAP) | Täglich |

## Prüfungs-Prozess

### 1. Bestellung identifizieren
- Email-Filter: Bestellbestätigungen erkennen
- Wichtige Absender:
  - `*@shopify.com` → Shopify Bestellungen
  - `*@amazon.*` → Amazon Bestellungen
  - `*@tiktok.com` → TikTok Bestellungen

### 2. Bestellung validieren
- [ ] Produkt/e vorhanden?
- [ ] Material verfügbar?
- [ ] Preis korrekt?
- [ ] Lieferadresse komplett?
- [ ] Zahlung eingegangen?

### 3. Bestellung kategorisieren
```
Bestellung/
├── Amazon/          # Amazon Bestellungen
├── Shopify/        # Shopify Bestellungen
├── TikTok/         # TikTok Bestellungen
├── Storniert/       # Stornierte Bestellungen
└── Problem/         # Probleme, Klärungsbedarf
```

### 4. Nächste Schritte
- [ ] Druckdaten prüfen (STL/OBJ Files)
- [ ] Produktionszeit kalkulieren
- [ ] Versandlabel generieren
- [ ] Versand bestätigen

## E-Mail Filter-Struktur (Gmail)

```
PrintMa/
├── Eingehend/
│   ├── Bestellungen/
│   │   ├── Amazon/       → from:*@amazon.*
│   │   ├── Shopify/      → from:*@shopify.com
│   │   └── TikTok/       → from:*@tiktok.com
│   └── Kundenanfragen/    → kontakt@printma.net
├── Gebucht/              → Versandlabel erstellt
└── Erledigt/             → Abgeschlossen
```

## Wichtige Keys / Prio-Flags

- 🔴 **DRINGEND:** Versand am selben Tag nötig
- 🟡 **WARTEN:** Auf Kundenantwort/Datei
- 🟢 **OK:** Bereit zur Produktion

## Retention

- Bestellungen: **2 Jahre** aufbewahren
- Rechnungen: **10 Jahre** (steuerrechtlich)
- Kundendaten: gemäß DSGVO