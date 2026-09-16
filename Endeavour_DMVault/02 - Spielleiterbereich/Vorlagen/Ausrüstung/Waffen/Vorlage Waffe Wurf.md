---
tags:
  - Gegenstand/Waffe
Schaden:
Schadensart:
Eigenschaften:

SchadenFern:
SchadensartFern:
Range1:
Range2:
Range3:
EigenschaftenFern:

Hände:
Größe:
Plaetze:
Stapelgroesse:
Kosten:
Verfügbarkeit:
---
## `=this.file.name`

| Waffe             | Schaden         | Art                 |     Hände     |     Größe     | Eigenschaften         |
| ----------------- | --------------- | ------------------- |:-------------:|:-------------:| --------------------- |
| `=this.file.name` | `=this.Schaden` | `=this.Schadensart` | `=this.Hände` | `=this.Größe` | `=this.Eigenschaften` |

## `=this.file.name` (Wurf)

| Waffe             | Schaden             | Art                     |     Hände     |     Größe     | Min RW         | Gnd RW         | Max RW         | Eigenschaften             |
| ----------------- | ------------------- | ----------------------- |:-------------:|:-------------:| -------------- | -------------- | -------------- | ------------------------- |
| `=this.file.name` | `=this.SchadenFern` | `=this.SchadensartFern` | `=this.Hände` | `=this.Größe` | `=this.Range1` | `=this.Range2` | `=this.Range3` | `=this.EigenschaftenFern` |

## Handel

| Waffe             | Plätze              | Stapelgröße                | Kosten         | Verfügbarkeit         |
| ----------------- | -------------------:| ---------------------------:| --------------:| --------------------- |
| `=this.file.name` | `=this.Plaetze` | `=this.Stapelgroesse` | `=this.Kosten` | `=this.Verfügbarkeit` |