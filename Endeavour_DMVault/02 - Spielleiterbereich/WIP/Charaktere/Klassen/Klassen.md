---
tags:
  - Regeln/Endeavour/WIP
---
# `=this.file.name`

```dataview
TABLE WITHOUT ID

file.link AS "Title"

FROM #Regeln/Nimble/Charakter/Klasse

SORT file.name
```

## Klassenideen
| Klasse          | Subklassen                                                                        | Identität                         | Rüstung       | Primäre Ressource      | Magie      | TP  | RP  |
| --------------- | --------------------------------------------------------------------------------- | --------------------------------- | ------------- | ---------------------- | ---------- |:---:|:---:|
| [[Taktiker]]    | Melee DD, Melee Tank, Kommandant (Support)                                        | Kämpfer, Support                  | Mittel/Schwer | Fokus (Flow passiv)    |            | +2  |  -  |
| [[Paladin]]     | Melee DD, Melee Tank, Inquisitor/Interrogator                                     | Kämpfer/Caster Hybrid, Auren      | Mittel/Schwer | Heilige Macht (Buffer) |            | +2  |  -  |
| [[Naturalist]]  | Melee DD/Tank, Heiler, Caster DD                                                  | Allrounder                        | Leicht        | Mana (Pool)            | Natur      | +1  |  -  |
| [[Gauner]]      | Assassine , Duellant, Strippenzieher                                              | Melee/Ranged DD, Kritfokus        | Leicht        | -                      |            | +1  |  -  |
| [[Arkanist]]    | Pyromant (Caster DD, Crits), Glaciomant (Caster DD, Control), Chronomant (Heiler) |                                   | -             | Mana (Pool)            | Arkan      |  -  |  -  |
| [[Fluchwirker]] | Caster DD (DoTs), Beschwörer, Melee/Caster Hybrid DD                              | Caster                            | -             | Fluchkraft             | Fluchkraft |  -  |  -  |
| [[Kleriker]]    | Heilig (Heiler), Disziplin (Hybrid), Schatten (Caster DD)                         | Caster, Heiler, Göttlicher Caster | -             | Mana (Pool)            | Göttlich   |  -  |  -  |
| [[Berserker]]   | Verwüster (Melee DD), Kopfjäger (Melee/Ranged Hybrid DD), Unbeugsamer (Tank)      | Melee DD, Rage                    | -             | Wut (Flow aktiv)       |            | +1  |  -  |
| [[Mönch]]       | Elemente (Control), Drunken Master (Tank), Eisenfaust (Combo-DD)                  |                                   | -             | Ki (Pool)              |            | +1  |  -  |
| [[Waldläufer]]  | Scharfschütze, Bestienmeister, Späher/Fallensteller                               | Ranged DD                         | Leicht/Mittel | -                      |            | +1  |  -  |

## Subklassenübersicht
### [[Taktiker]]
Klassischer Kämpfer-Archetyp

| Subklasse  | Identität               | Rolle            | Rüstung       |
| ---------- | ----------------------- | ---------------- | ------------- |
| Klingenmeister | Kämpfer (Waffenfokus)   | Nahkampf DD      | mittel/schwer |
| Bollwerk       | Kämpfer (Rüstungsfokus) | Nahkampf Tank    | schwer        |
| Kommandant | Befehle, Ansporn        | Nahkampf Support | mittel/schwer |

### [[Paladin]]
Heiliger Krieger, Auren, Heilige Fähigkeiten (keine Zauber!)

| Subklasse | Identität                  | Rolle                    | Rüstung       |
| --------- | -------------------------- | ------------------------ | ------------- |
| Vergelter | Heiliger Ritter (offensiv) | Nahkampf DD              | schwer        |
| Schildwache | Heiliger Ritter (defensiv) | Nahkampf Tank            | schwer        |
| Inquisitor | Inquisitor/Interrogator    | Nahkampf/Support/Debuffs | mittel/schwer |

### [[Naturalist]]
Naturmagie, Gestaltwandlung, Gestirne, etc.

| Subklasse | Identität       | Rolle            | Rüstung      |
| --------- | --------------- | ---------------- | ------------ |
| Beastshifter | Tiergestalten   | Nahkampf DD/Tank | keine/leicht |
| Hüter des Hains | Heilung/Natur   | Heiler/Support   | keine/leicht |
| Stormshifter | Caster/Gestirne | Caster DD        | keine/leicht |

### [[Gauner]]
Gauner, Schurke, Attentäter, etc.

| Subklasse  | Identität             | Rolle               | Rüstung |
| ---------- | --------------------- | ------------------- | ------- |
| Attentäter | Verstohlenheit, Gifte | Nahkampf DD         | leicht  |
| Duellant   | Mantel und Degen      | Nahkampf DD/Control | leicht  |
| Strippenzieher | Manipulation, Kontrolle | Support/Debuffs     | leicht  |

### [[Arkanist]]
Arkaner Magiewirker, Gelehrter, etc.

| Subklasse  | Identität                | Rolle                    | Rüstung |
| ---------- | ------------------------ | ------------------------ | ------- |
| Pyromant   | Feuermagie, Crit-basiert | Caster DD                | keine   |
| Glaciomant | Eismagie, Kontrolle      | Caster DD/Control        | keine   |
| Chronomant | Zeitmagie                | Caster DD/Heiler/Support | keine   |

### [[Fluchwirker]]
Kanalisiert negative Energien, nicht unbedingt böse, aber eher verpönt im Vergleich zum Arkanisten.

| Subklasse | Identität              | Rolle                  | Rüstung      |
| --------- | ---------------------- | ---------------------- | ------------ |
| Verderber | Flüche, Debuffs        | Caster DD/Debuffs      | keine/leicht |
| Dämonenbinder | Beschwörung            | Caster DD/Pets         | keine/leicht |
| Blutgestalt | Metamorphose/Blutmagie | Caster/Melee DD Hybrid | keine/leicht |

### [[Kleriker]]
Nutzt Primordiale Magiequellen Licht/Schatten bzw. eine Neutralform.

| Subklasse | Identität                   | Rolle             | Rüstung |
| --------- | --------------------------- | ----------------- | ------- |
| Lichtbringer | Lichtmagie/Stärkung/Heilung | Heiler/Support    | keine   |
| Aschgrauer | Schattenmagie/Chaos/Entzug  | Caster DD/Debuffs | keine   |
| Mittler   | Gleichgewicht               | Hybrid Heiler/Caster DD | keine   |

### [[Berserker]]
Wut, Mobilität, Hoher Schaden.

| Subklasse | Identität                    | Rolle                 | Rüstung      |
| --------- | ---------------------------- | --------------------- | ------------ |
| Verwüster | Nahkampf/hoher Einzelschaden | Nahkampf DD           | keine/leicht |
| Unbeugsamer | Zähigkeit, Schadensreduktion | Nahkampf Tank         | keine/leicht |
| Kopfjäger | Nahkampf/Wurfwaffen          | Nahkampf/Fernkampf DD | keine/leicht |

### [[Mönch]]
Mönch-Style, Waffenloser Kampf/Mönchswaffen, Beweglichkeit, Mobilität

| Subklasse | Identität      | Rolle               | Rüstung      |
| --------- | -------------- | ------------------- | ------------ |
| Elementweber | Elemente       | Nahkampf DD/Control | keine/leicht |
| Trunkener Meister | Drunken Master | Nahkampf Tank       | keine/leicht |
| Eisenfaust | Combos         | Nahkampf DD         | keine/leicht |

### [[Waldläufer]]
Fährtenleser, Bogenschütze, Naturverbunden.

| Subklasse      | Identität           | Rolle            | Rüstung       |
| -------------- | ------------------- | ---------------- | ------------- |
| Scharfschütze  | Fernkampf           | Fernkampf DD     | leicht/mittel |
| Bestienmeister | Pet                 | Fernkampf DD/Pet | leicht/mittel |
| Fährtenleser   | Trapper/Spurenleser |                  | leicht/mittel |