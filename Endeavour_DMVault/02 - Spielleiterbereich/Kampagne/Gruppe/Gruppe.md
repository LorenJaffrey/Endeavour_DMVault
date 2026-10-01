# `=this.file.name`

```dataview
TABLE WITHOUT ID

file.link AS "Character",
Hintergrund.Volk AS "Volk",
Hintergrund.Klasse AS "Klasse",
Hintergrund.Subklasse AS "Subklasse",
Hintergrund.Gesinnung AS "Gesinnung",
Hintergrund.Hintergrund AS "Hintergrund"

FROM #Charakter/GORN

SORT file.name
```

| Spieler | Geschlecht | Abstammung | Klasse          | Rolle   |
| ------- |:----------:| ---------- | --------------- | ------- |
| Frank   |     w      | Mensch?    | [[Kleriker]]    | Heiler  |
| Deekay  |     w      | Mensch?    | [[Paladin]]     | Tank/DD |
| Sancho  |     m      | Elf        | [[Mönch]]       | DD      |
| Tobi    |     m      | Mensch     | [[Gauner]]      | DD      |
| Michi   |     m      | Mensch     | [[Fluchwirker]] | DD      |
