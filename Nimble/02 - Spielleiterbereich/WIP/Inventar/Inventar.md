---
tags:
  - Regeln/Nimble/WIP
---
# `=this.file.name`

## Konzept
Inventar funktioniert platzbasiert, angelehnt an Mausritter.
Gegenstände werden nicht in Kilogramm sondern in Plätzen gezählt.
Schwere Gegenstände verbrauchen zusätzlich mehr Plätze als ihr Volumen vermuten lässt.
Damit ersetzt der Platz fast vollständig die klassische Gewichtsangabe.

Ein Charakter trägt Ausrüstung direkt am Körper und zusätzlich in Behältern.
Nur Gegenstände in Behältern mit Schnellzugriff können im Kampf benutzt werden.

## Abschnitte
```dataview
TABLE WITHOUT ID
file.link AS "Abschnitt"
FROM #Regeln/Nimble/Inventar
SORT file.name
```
