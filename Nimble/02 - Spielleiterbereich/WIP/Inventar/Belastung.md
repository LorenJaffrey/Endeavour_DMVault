---
tags:
  - Regeln/Nimble/WIP
  - Regeln/Nimble/Inventar
---
# `=this.file.name`

## Allgemeine Belastung
Ersetzt die klassische Gewichtsangabe in Kilogramm durch Gewichtseinheiten aus den Gewichtsklassen in [[Gegenstandsgrößen]].
Nur Gegenstände der Klasse Schwer oder Sehr Schwer zählen dafür, egal wie viele Slots sie belegen.
  - Schwer zählt 1 Gewichtseinheit
  - Sehr schwer zählt 2 Gewichtseinheiten
  - Normale Gegenstände zählen 0 Gewichtseinheiten

Belastungsstufen:
  - Gewichtseinheiten > [[Stärke|ST]] -> Belastet ([[Bewegungsrate]] -3m)
  - Gewichtseinheiten > [[Stärke|ST]] x 2 -> Stark Belastet ([[Bewegungsrate]] -6m; Nachteil bei [[Attribute#Attributswurf]] und [[Stärkerettungswürfe|ST-Rettungswürfen]], [[Beweglichkeitsrettungswürfe|BW-Rettungswürfen]] und [[Konstitutionsrettungswürfe|KO-Rettungswürfen]])

> [!warning]- Negative oder niedrige ST
> Bei ST 0 oder darunter kann schon ein einzelner schwerer Gegenstand Belastet auslösen. Das ist beabsichtigt, sollte aber im Playtest beobachtet werden.

## Größe und Stärke
Große Kreaturen verdoppeln Traglast.
Winzige Kreaturen halbieren Traglast.