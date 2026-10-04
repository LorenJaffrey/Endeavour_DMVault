---
tags:
  - Regeln/Endeavour/Merkmal/Klasse/Mönch
aliases:
  - Schwungpunkt
  - Schwungpunkte
Einsatz: Passiv
---
# `=this.file.name`
Wenn du [[Initiative]] würfelst, erhältst du [[Schwung]] in Höhe deiner [[Entschlossenheit|EN]], die du während dieser [[Begegnung]] einsetzen kannst.
Du kannst nie mehr [[Schwung]] haben als deine [[Entschlossenheit|EN]].

**Sammeln (1 [[Aktionspunkte|AP]]):** Du erhältst 1 [[Schwung|Schwungpunkt]].

Du kannst [[Schwung|Schwungpunkte]] ausgeben, um die folgenden Aktionen einzusetzen.
Die Kosten stehen bei der jeweiligen Aktion:

```dataview
TABLE WITHOUT ID

file.link AS "Title",
Einsatz

FROM #Regeln/Endeavour/Merkmal/Klasse/Mönch/Schwungaktion  

SORT file.name
```