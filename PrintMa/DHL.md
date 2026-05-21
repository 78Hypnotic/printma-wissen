# DHL GKP – PrintMa

## Account-Daten
- **EKP:** 5305091454
- **Plattform:** DHL Developer Portal (dhl.com/develop)
- **API:** REST v2

## Versandablauf
1. Bestellung prüfen (Amazon/Shopify/TikTok)
2. Versandboxen (22x16x8 cm Standard)
3. DHL Label generieren via API
4. Label drucken, Paket bekleben
5. Bei DHL Abgabestelle abgeben

## Retouren
- DHL Retouretikett wird vom Kunden angefordert
- Retourelabel über DHL GKP API generieren
- PrintMa-Adresse: Randenstr. 8, 78234 Engen

## Wichtige Links
- [DHL Developer Portal](https://dhl.com/develop)
- [DHL GKP Dokumentation](https://entwickler.dhl.de/)

## Status
- ✅ GKP Konto verbunden
- ✅ ROPC OAuth (Systembenutzer)
- ⚠️ ROPC Auth noch nicht funktionsfähig (invalid_grant – Portal Verknüpfung)
