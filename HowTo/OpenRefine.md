# How to Ogham - OpenRefine - WIKIDATA

1. Öffnen des Google SpreadSheet
2. Ändern / Hunzufügen von Daten
3. Herunterladen als `*.tsv`
4. Commit TSV File in GitHub Repository
5. OpenRefine öffnen
6. Create Project
7. Web Addresses (URLs) auswählen
8. Pfad zur TSV im GitHub als Raw eingeben z.B. https://raw.githubusercontent.com/ogi-ogham/ogham-wikidata/master/OgamStones/OgamStones.tsv
9. Next drücken
10. Character Encoding `UTF-8` wählen
11. `Parse cell text into numbers, ...` auswählen
12. Create Project klicken
13. Unter `Extensions/Wikidata` --> `Import Schema auswählen` und Schema auswählen (z.B. OgamStones_WikidataSchema.json) und Import drücken
14. auf `Undo/Redo` und --> `Apply` klicken
15. JSON Inhalt der OpenRefine-Datei (z.B. OgamStones_OpenRefine.json) kopieren, im Feld einfügen und auf `Perform Operations`  klicken
16. unter label_en "matches" auswählen
16. Daten kontrollieren --> `Issues` und `Preview`

## WIkidata QuickStatements

* Wikidata -> `Export to Qick Statements`
* https://tools.wmflabs.org/quickstatements/#/
* Neuer Stapel
* Anweisungen importieren
* Import

## Koordinaten

https://www.gpskoordinaten.de/gps-koordinaten-konverter
