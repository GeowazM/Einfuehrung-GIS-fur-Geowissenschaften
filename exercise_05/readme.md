# Übung 5
## Ziel der Übung
* web-basierte Hintergrundkarten nutzen
* Vektordaten händisch erstellen (Digitalisieren)
* Ein Bild Georeferenzieren


## Wiki:
* [Basemaps](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Basemaps)
* [Digitalisieren](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Digitalisierung)
* [Georeferenzieren](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Georeferenzierung)


## Daten
Ladet euch [die Daten herunter](exercise_05_data.zip) und speichert sie auf eurem PC. Legt einen lokalen Ordner an und speichert dort die obigen Daten. (.zip Ordner müssen vorher entpackt werden.)


## Aufgaben
### Häuser und Straßen kartieren

1. Erstelle zwei neue Layer für (a) Porphyrtuff und (b) jungpleistozäne Sande (haupts. Flugsande).
2. Füge zu jedem Layer ein Attribut (Spalte) "id", "url" und "name" hinzu.
3. Füge eine Hintergrundkarte hinzu (z.B. Bing).
4. Erstelle mindestens 3 Polygone je Layer. Befülle die von dir erstellten Spalten mit Informationen.
5. Füge zu jedem Feature den passenden Namen und einen Hyperlink hinzu.


### Ein Bild georeferenzieren
#### Kontext
Du brauchst für dein Projekt eine geologische Karte von Heidelberg. Die einzig verfügbaren Informationen, die du finden kannst ist eine PDF Karte der Universität Heidelberg. Um diese geologische Karte mit deinen weiteren Geodaten zu kombinieren.

![Heidelberg_1821](Heidelberg_1821.jpg)

1. Versehe das zur Verfügung gestellte Raster mit WGS84 Pseudo-Mercator-Koordinaten (EPSG: 3857).
2. Verwende als Referenz-Layer eine Webkarten deiner Wahl, welche du in Form einer Hintergrundkarte einbinden kannst.
3. Wähle eine geeignete Transformationsvorschrift und setzt genügend und ausreichend verteilte Passpunkte.
4. Kontrolliere abschließend deinen Erfolg, indem du die Passgenauigkeit des georeferenzierten Bildes mit überlagerten Hintergrundkarte vergleichst.
