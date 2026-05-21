# Produktion – PrintMa

> Eigene Printer und Partner-Netzwerk

## Eigene FDM Printer

### Printer 1
- **Modell:** [Modell eintragen]
- **Baufläche:** [z.B. 220x220x250mm]
- **Status:** ✅ Betriebsbereit
- **Hauptmaterial:** PLA / PETG
- **Besonderheiten:** [Beschriftung]

### Printer 2
- **Modell:** [Modell eintragen]
- **Baufläche:** [Baufläche]
- **Status:** [✅/🔴/🟡]
- **Hauptmaterial:** [Material]
- **Besonderheiten:** [Beschriftung]

### Printer 3 (falls vorhanden)
- [ ]
- [ ]
- [ ]
- [ ]
- [ ]

## Slicer-Einstellungen

### PLA
```
Layer Height:     0.2mm (Standard) / 0.1mm (Fein)
Infill:           15% (Standard) / 40% (Fest)
Walls:            3 Perimeter
Temp Nozzle:      210°C
Temp Bed:         60°C
Print Speed:      50mm/s
```

### PETG
```
Layer Height:     0.2mm
Infill:           20%
Walls:            4 Perimeter
Temp Nozzle:      240°C
Temp Bed:         70°C
Print Speed:      40mm/s
Fan:              50%
```

### TPU
```
Layer Height:     0.24mm
Infill:           30%
Walls:            3 Perimeter
Temp Nozzle:       235°C
Temp Bed:         50°C
Print Speed:      20mm/s (langsam!)
Retraction:       Ausschalten oder minimal
```

## SLS Partner-Netzwerk

### Partner 1
- **Name:** [Name]
- **Website:** [URL]
- **Material:** [PA12 / PA11]
- **Preismodell:** [Volumen / Stück]
- **Lead Time:** [Werktage]
- **Mindestbestellwert:** [€]
- **Ansprechpartner:** [Name]
- **Konditionen:** [Notizen]

### Partner 2
- [ ]
- [ ]
- [ ]
- [ ]
- [ ]

## Qualitätskontrolle

### Prüfprotokoll
- [ ] Sichtprüfung (Schichtlinien, Stringing)
- [ ] Masshaltigkeit (wenn kritisch: Messschieber)
- [ ] Stabilität prüfen
- [ ] Oberfläche: Grate/Support-Reste entfernen
- [ ] Foto für Kunden (bei Bedarf)

### Häufige Fehler
| Fehler | Ursache | Lösung |
|---|---|---|
| Stringing | Retraction zu wenig | Retraction erhöhen |
| Layer Shift | Stepper überhitzt | Kühlung prüfen |
| Warping | Bett-Temp zu hoch/niedrig | Temp anpassen |
| Clogging | Temp zu niedrig / Filament feucht | Temp erhöhen, trocknen |

## Druckdaten

- **Format:** STL, OBJ, 3MF
- **Auflösung:** Mindestens 0.1mm Details auflösen
- **Check:** Meshes geschlossen, kein Floaters
- **Slicer:** Cura, PrusaSlicer, Bambu Studio (nach Preference)