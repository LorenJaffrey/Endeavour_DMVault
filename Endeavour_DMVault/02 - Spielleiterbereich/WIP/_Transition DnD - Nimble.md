## Attribute
- 4 Attribute -> 6 Attribute -> 8 Attribute
- Erweiterung 6 -> 8: Geschick(Dex) gesplittet in Beweglichkeit + Geschick, Weisheit gesplittet in Instinkt + Entschlossenheit (DSA-inspiriert)

### [[_Key Stats]] 
- pro Klasse neu festgelegt:
	- max. +5
	- max. +3 auf Stufe 1 (Startwert-Obergrenze, nur im Min-Max-Array erreicht)
	- 3 Key Stats
	- 5 Secondary Stats
	- Character Creation Splits (Reihenfolge: Key1, Key2, Key3, Sec1, Sec2, Sec3, Sec4, Sec5):
		- Standard: +2, +2, +1, +1, +0, +0, +0, -1 (Summe 5)
		- Balanced: +2, +1, +1, +1, +1, +1, +0, -1 (Summe 6)
		- Min-Max: +3, +1, +1, +1, +1, +0, -1, -1 (Summe 5)
	- Begründung Balanced: niedrigere Key Stats als Standard/Min-Max, dafür breiter positive Secondary Stats. Summe bewusst nur 1 über Standard/Min-Max, nicht wie vorher 1 (relativ) zu hoch.
	- Erhöhung im Aufstieg, kalibriert auf Ø 2 Punkte pro Attribut über die Kampagne (wie im alten 6-Attribute-System, siehe Berechnung unten):
		- Key Stats:
			- Stufen 3, 6, 9, 12, 15, 18 (alle 3 Stufen)
			- 1 mal +1
			- 6 Erhöhungen / 3 Key Stats = Ø 2 Punkte/Stat
		- Secondary Stats:
			- Stufen 2, 5, 8, 11, 14, 17, 20 (alle 3 Stufen, Start bei Stufe 2)
			- 1 mal +1
			- 7 Erhöhungen x 1 Punkt / 5 Secondary Stats = Ø 1,4 Punkte/Stat
			- Einschränkung: dasselbe Secondary Attribut darf nicht zwei Stufenaufstiege in Folge erhöht werden. Verhindert Ein-Attribut-Fokussierung, erzwingt Streuung über mindestens 2 Attribute.
	- Bewusste Abkehr vom Ø 2 Punkte/Stat Prinzip: Secondary Stats wachsen jetzt langsamer im Schnitt (1,4 statt 2) und im Fokus-Fall (ein Attribut wird konsequent bevorzugt) erst auf Stufe 20 den Cap +5, statt schon um Stufe 14-16 mit Rest-Kampagne am Anschlag. Key Stats bleiben bei Ø 2 Punkte/Stat und können bei Fokus schon um Stufe 9 capped sein. Damit reifen Key Stats immer früher und zuverlässiger als Secondary Stats, keine versehentliche Überholung mehr.
	- Hinweis: altes System (2 Key/4 Secondary) kam ebenfalls auf Ø 2 Punkte/Stat in beiden Pools (4 Erhöhungen/2 Key-Stats, 8 Punkte/4 Secondary-Stats). Key Stats bleiben bei alle 3 Stufen/1x+1 (seltenere, gezielte Wahl unter 3 Optionen), Secondary Stats wechseln auf alle 2 Stufen/1x+1 (häufigere, kleinere Schritte für kontinuierlicheres Wachstumsgefühl). Beides ergibt weiterhin exakt Ø 2 Punkte/Stat, keine Verschiebung der Gesamtstärke gegenüber dem alten System.

### Beispiel: Berserker (8 Attribute)
Key Stats: Stärke > Beweglichkeit > Konstitution (Prioritätsreihenfolge für Punktevergabe in diesem Beispiel)
Secondary Stats Priorität: Entschlossenheit > Geschick > Instinkt > Verstand > Präsenz

Spalten in Prioritätsreihenfolge: ST, BW, KO | EN, GE, IN, VS, PR

> [!note] Annahme
> Punktevergabe folgt strikt der oben genannten Priorität (erst Key Stat 1 auf Cap, dann Key Stat 2, usw.), mit der Einschränkung "nicht zweimal in Folge dasselbe Secondary Attribut". Sobald die Top-Prioritäten gecapped sind und die nächste Wiederholung blockiert wäre, rutscht der Punkt zur nächsten freien Priorität durch (sichtbar z.B. bei Balanced/Min-Max auf Stufe 20, wo ein Punkt in Verstand landet statt in Geschick/Entschlossenheit erneut zu investieren). Ein echter Spieler kann natürlich anders verteilen, das hier ist nur ein Referenzpfad zur Veranschaulichung der Wachstumsrate.

#### Standard

| Stufe | ST  | BW  | KO  | EN  | GE  | IN  | VS  | PR  |
| ----- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1     |  2  |  2  |  1  |  1  |  0  |  0  |  0  | -1  |
| 2     |  2  |  2  |  1  |  2  |  0  |  0  |  0  | -1  |
| 3     |  3  |  2  |  1  |  2  |  0  |  0  |  0  | -1  |
| 4     |  3  |  2  |  1  |  2  |  0  |  0  |  0  | -1  |
| 5     |  3  |  2  |  1  |  2  |  1  |  0  |  0  | -1  |
| 6     |  4  |  2  |  1  |  2  |  1  |  0  |  0  | -1  |
| 7     |  4  |  2  |  1  |  2  |  1  |  0  |  0  | -1  |
| 8     |  4  |  2  |  1  |  3  |  1  |  0  |  0  | -1  |
| 9     |  5  |  2  |  1  |  3  |  1  |  0  |  0  | -1  |
| 10    |  5  |  2  |  1  |  3  |  1  |  0  |  0  | -1  |
| 11    |  5  |  2  |  1  |  3  |  2  |  0  |  0  | -1  |
| 12    |  5  |  3  |  1  |  3  |  2  |  0  |  0  | -1  |
| 13    |  5  |  3  |  1  |  3  |  2  |  0  |  0  | -1  |
| 14    |  5  |  3  |  1  |  4  |  2  |  0  |  0  | -1  |
| 15    |  5  |  4  |  1  |  4  |  2  |  0  |  0  | -1  |
| 16    |  5  |  4  |  1  |  4  |  2  |  0  |  0  | -1  |
| 17    |  5  |  4  |  1  |  4  |  3  |  0  |  0  | -1  |
| 18    |  5  |  4  |  2  |  4  |  3  |  0  |  0  | -1  |
| 19    |  5  |  4  |  2  |  4  |  3  |  0  |  0  | -1  |
| 20    |  5  |  4  |  2  |  5  |  3  |  0  |  0  | -1  |

#### Balanced

| Stufe | ST  | BW  | KO  | EN  | GE  | IN  | VS  | PR  |
| ----- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1     |  2  |  1  |  1  |  1  |  1  |  1  |  0  | -1  |
| 2     |  2  |  1  |  1  |  2  |  1  |  1  |  0  | -1  |
| 3     |  3  |  1  |  1  |  2  |  1  |  1  |  0  | -1  |
| 4     |  3  |  1  |  1  |  2  |  1  |  1  |  0  | -1  |
| 5     |  3  |  1  |  1  |  2  |  2  |  1  |  0  | -1  |
| 6     |  4  |  1  |  1  |  2  |  2  |  1  |  0  | -1  |
| 7     |  4  |  1  |  1  |  2  |  2  |  1  |  0  | -1  |
| 8     |  4  |  1  |  1  |  3  |  2  |  1  |  0  | -1  |
| 9     |  5  |  1  |  1  |  3  |  2  |  1  |  0  | -1  |
| 10    |  5  |  1  |  1  |  3  |  2  |  1  |  0  | -1  |
| 11    |  5  |  1  |  1  |  3  |  3  |  1  |  0  | -1  |
| 12    |  5  |  2  |  1  |  3  |  3  |  1  |  0  | -1  |
| 13    |  5  |  2  |  1  |  3  |  3  |  1  |  0  | -1  |
| 14    |  5  |  2  |  1  |  4  |  3  |  1  |  0  | -1  |
| 15    |  5  |  3  |  1  |  4  |  3  |  1  |  0  | -1  |
| 16    |  5  |  3  |  1  |  4  |  3  |  1  |  0  | -1  |
| 17    |  5  |  3  |  1  |  4  |  4  |  1  |  0  | -1  |
| 18    |  5  |  3  |  2  |  4  |  4  |  1  |  0  | -1  |
| 19    |  5  |  3  |  2  |  4  |  4  |  1  |  0  | -1  |
| 20    |  5  |  3  |  2  |  5  |  4  |  1  |  0  | -1  |

#### Min-Max

| Stufe | ST  | BW  | KO  | EN  | GE  | IN  | VS  | PR  |
| ----- |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1     |  3  |  1  |  1  |  1  |  1  |  0  | -1  | -1  |
| 2     |  3  |  1  |  1  |  2  |  1  |  0  | -1  | -1  |
| 3     |  4  |  1  |  1  |  2  |  1  |  0  | -1  | -1  |
| 4     |  4  |  1  |  1  |  2  |  1  |  0  | -1  | -1  |
| 5     |  4  |  1  |  1  |  2  |  2  |  0  | -1  | -1  |
| 6     |  5  |  1  |  1  |  2  |  2  |  0  | -1  | -1  |
| 7     |  5  |  1  |  1  |  2  |  2  |  0  | -1  | -1  |
| 8     |  5  |  1  |  1  |  3  |  2  |  0  | -1  | -1  |
| 9     |  5  |  2  |  1  |  3  |  2  |  0  | -1  | -1  |
| 10    |  5  |  2  |  1  |  3  |  2  |  0  | -1  | -1  |
| 11    |  5  |  2  |  1  |  3  |  3  |  0  | -1  | -1  |
| 12    |  5  |  3  |  1  |  3  |  3  |  0  | -1  | -1  |
| 13    |  5  |  3  |  1  |  3  |  3  |  0  | -1  | -1  |
| 14    |  5  |  3  |  1  |  4  |  3  |  0  | -1  | -1  |
| 15    |  5  |  4  |  1  |  4  |  3  |  0  | -1  | -1  |
| 16    |  5  |  4  |  1  |  4  |  3  |  0  | -1  | -1  |
| 17    |  5  |  4  |  1  |  4  |  4  |  0  | -1  | -1  |
| 18    |  5  |  5  |  1  |  4  |  4  |  0  | -1  | -1  |
| 19    |  5  |  5  |  1  |  4  |  4  |  0  | -1  | -1  |
| 20    |  5  |  5  |  1  |  5  |  4  |  0  | -1  | -1  |


### Fertigkeiten
- 10 Fertigkeiten -> 18 Fertigkeiten
- max. +12 -> max. +10
	- Grund: Attribut max. +5 + Fertigkeit max. +10 = max. +15 Gesamtbonus (statt vorher +17).
	- Bei SG 30 ("Fast unmöglich") braucht ein Vollspezialist damit eine 15+ (30% Erfolgschance), bleibt eine echte Herausforderung statt Formsache.
	- Bewusst keine SG-Skalierung nach Stufe, stattdessen dieser Cap als Korrektur.
- Character Creation
	- 4 -> 6 Skillpunkte auf Stufe 1 beliebig verteilt
	- 1 -> 2 Skillpunkte pro Stufenaufstieg auf zwei Fertigkeiten

| Stufe | Skillpunke alt | Skillpunkte neu |     |
| ----- | --------------:| ---------------:| --- |
| 1     |              4 |               6 |     |
| 2     |              5 |               8 |     |
| 3     |              6 |              10 |     |
| 4     |              7 |              12 |     |
| 5     |              8 |              14 |     |
| 6     |              9 |              16 |     |
| 7     |             10 |              18 |     |
| 8     |             11 |              20 |     |
| 9     |             12 |              22 |     |
| 10    |             13 |              24 |     |
| 11    |             14 |              26 |     |
| 12    |             15 |              28 |     |
| 13    |             16 |              30 |     |
| 14    |             17 |              32 |     |
| 15    |             18 |              34 |     |
| 16    |             19 |              36 |     |
| 17    |             20 |              38 |     |
| 18    |             21 |              40 |     |
| 19    |             22 |              42 |     |
| 20    |             23 |              44 |     |