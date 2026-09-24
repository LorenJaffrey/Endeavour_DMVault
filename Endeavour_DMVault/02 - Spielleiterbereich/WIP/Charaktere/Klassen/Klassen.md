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
| [[Waldläufer]]  | Scharfschütze, Bestienmeister, Fährtenleser                                       | Ranged/Melee DD                   | Leicht/Mittel | -                      |            | +1  |  -  |

## Subklassenübersicht
### [[Taktiker]]
Klassischer Kämpfer-Archetyp

| Subklasse      | Identität               | Rolle            | Rüstung       | 3. Kernattribut |
| -------------- | ----------------------- | ---------------- | ------------- | --------------- |
| Klingenmeister | Kämpfer (Waffenfokus)   | Nahkampf DD      | mittel/schwer | Beweglichkeit   |
| Bollwerk       | Kämpfer (Rüstungsfokus) | Nahkampf Tank    | schwer        | Entschlossenheit |
| Kommandant     | Befehle, Ansporn        | Nahkampf Support | mittel/schwer | Präsenz         |

### [[Paladin]]
Heiliger Krieger, Auren, Heilige Fähigkeiten (keine Zauber!)

| Subklasse   | Identität                  | Rolle                    | Rüstung       | 3. Kernattribut |
| ----------- | -------------------------- | ------------------------ | ------------- | --------------- |
| Vergelter   | Heiliger Ritter (offensiv) | Nahkampf DD              | schwer        | Instinkt        |
| Schildwache | Heiliger Ritter (defensiv) | Nahkampf Tank            | schwer        | Konstitution    |
| Inquisitor  | Inquisitor/Interrogator    | Nahkampf/Support/Debuffs | mittel/schwer | Präsenz         |

### [[Naturalist]]
Naturmagie, Gestaltwandlung, Gestirne, etc.

| Subklasse       | Identität       | Rolle            | Rüstung      | 3. Kernattribut |
| --------------- | --------------- | ---------------- | ------------ | --------------- |
| Beastshifter    | Tiergestalten   | Nahkampf DD/Tank | keine/leicht | Beweglichkeit   |
| Hüter des Hains | Heilung/Natur   | Heiler/Support   | keine/leicht | Entschlossenheit |
| Stormshifter    | Caster/Gestirne | Caster DD        | keine/leicht | Verstand        |

### [[Gauner]]
Gauner, Schurke, Attentäter, etc.

| Subklasse      | Identität               | Rolle               | Rüstung | 3. Kernattribut |
| -------------- | ----------------------- | ------------------- | ------- | --------------- |
| Attentäter     | Verstohlenheit, Gifte   | Nahkampf DD         | leicht  | Instinkt        |
| Duellant       | Mantel und Degen        | Nahkampf DD/Control | leicht  | Beweglichkeit   |
| Strippenzieher | Manipulation, Kontrolle | Support/Debuffs     | leicht  | Präsenz         |

### [[Arkanist]]
Arkaner Magiewirker, Gelehrter, etc.

| Subklasse  | Identität                | Rolle                    | Rüstung | 3. Kernattribut |
| ---------- | ------------------------ | ------------------------ | ------- | --------------- |
| Pyromant   | Feuermagie, Crit-basiert | Caster DD                | keine   | Geschick        |
| Glaciomant | Eismagie, Kontrolle      | Caster DD/Control        | keine   | Instinkt        |
| Chronomant | Zeitmagie                | Caster DD/Heiler/Support | keine   | Präsenz         |

### [[Fluchwirker]]
Kanalisiert negative Energien, nicht unbedingt böse, aber eher verpönt im Vergleich zum Arkanisten.

| Subklasse     | Identität              | Rolle                  | Rüstung      | 3. Kernattribut |
| ------------- | ---------------------- | ---------------------- | ------------ | --------------- |
| Verderber     | Flüche, Debuffs        | Caster DD/Debuffs      | keine/leicht | Instinkt        |
| Dämonenbinder | Beschwörung            | Caster DD/Pets         | keine/leicht | Entschlossenheit |
| Blutgestalt   | Metamorphose/Blutmagie | Caster/Melee DD Hybrid | keine/leicht | Beweglichkeit   |

### [[Kleriker]]
Nutzt Primordiale Magiequellen Licht/Schatten bzw. eine Neutralform.

| Subklasse    | Identität                   | Rolle                   | Rüstung | 3. Kernattribut |
| ------------ | --------------------------- | ----------------------- | ------- | --------------- |
| Lichtbringer | Lichtmagie/Stärkung/Heilung | Heiler/Support          | keine   | Präsenz         |
| Aschgrauer   | Schattenmagie/Chaos/Entzug  | Caster DD/Debuffs       | keine   | Verstand        |
| Mittler      | Gleichgewicht               | Hybrid Heiler/Caster DD | keine   | Geschick        |

### [[Berserker]]
Wut, Mobilität, Hoher Schaden.

| Subklasse   | Identität                    | Rolle                 | Rüstung      | 3. Kernattribut |
| ----------- | ---------------------------- | --------------------- | ------------ | --------------- |
| Verwüster   | Nahkampf/hoher Einzelschaden | Nahkampf DD           | keine/leicht | Beweglichkeit   |
| Unbeugsamer | Zähigkeit, Schadensreduktion | Nahkampf Tank         | keine/leicht | Konstitution    |
| Kopfjäger   | Nahkampf/Wurfwaffen          | Nahkampf/Fernkampf DD | keine/leicht | Geschick        |

### [[Mönch]]
Mönch-Style, Waffenloser Kampf/Mönchswaffen, Beweglichkeit, Mobilität

| Subklasse         | Identität      | Rolle               | Rüstung      | 3. Kernattribut |
| ----------------- | -------------- | ------------------- | ------------ | --------------- |
| Elementweber      | Elemente       | Nahkampf DD/Control | keine/leicht | Instinkt        |
| Trunkener Meister | Drunken Master | Nahkampf Tank       | keine/leicht | Konstitution    |
| Eisenfaust        | Combos         | Nahkampf DD         | keine/leicht | Geschick        |

### [[Waldläufer]]
Fährtenleser, Bogenschütze, Naturverbunden.

| Subklasse      | Identität           | Rolle            | Rüstung       | 3. Kernattribut |
| -------------- | ------------------- | ---------------- | ------------- | --------------- |
| Scharfschütze  | Fernkampf           | Fernkampf DD     | leicht/mittel | Entschlossenheit |
| Bestienmeister | Pet                 | Fernkampf DD/Pet | leicht/mittel | Präsenz         |
| Fährtenleser   | Trapper/Nahkämpfer  | Nahkampf DD      | leicht/mittel | Beweglichkeit   |