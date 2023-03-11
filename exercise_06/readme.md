# Übung 6
## Ziel der Übung.
* Rasterdaten im GIS öffnen und kennenlernen
* farbliche Darstellung der Rasterwerte anpassen
* Rasterdaten in Vektordaten umwandeln
* Globale Rasteroperationen anwenden (z.B. Projektion ändern)
* Lokale Rasteroperationen anwenden (z.B. NDVI berechnen)

## Wiki:
* [Rasterdaten im GIS öffnen und kennenlernen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Layer-Konzept)
* [Darstellung von Rasterdaten](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Rasterdarstellung)
* [Vektordaten in Rasterdaten umwandeln](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Konvertierung)
* [Globale Rasteroperationen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Globale-Funktionen)
* [Lokale Rasteroperationen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Lokale-Funktionen)

## Daten
Ladet euch [die Daten herunter](exercise_06_data.zip) und speichert sie auf eurem PC. Legt einen lokalen Ordner an und speichert dort die obigen Daten. (.zip Ordner müssen vorher entpackt werden.)

## Aufgaben
### Aufgabe 1: Vorbereitung
* Erstellt zunächst ein Mosaik aus den einzelnen Dateien des ASTER-Höhenmodells.
* Bringt anschließend das Aster-Höhenmodell in eine metrische Projektion.

### Aufgabe 2: Arbeiten mit Geländemodellen
* Verschafft euch einen Überblick über die Höhenwerte. Was sind die maximalen und minimalen Höhen im Untersuchungsgebiet. Schaut dies in den Layer-Eigenschaften nach.
* Reklassifiziert das Aster-Höhenmodell in 500 Meter Schritten.
* Erstellt nun Höhenlinien (Konturlinien) und exportiert diese im Vektorformat.

### Aufgabe 3: Arbeiten mit Landsat-Daten
* In dieser Aufgabe arbeiten wir mit Daten der Landsat 8 Mission. Wir nutzen nur die Bänder 2-5 in unserer Analyse. Welchen Farben entsprechen diese Bänder?
* Erstellt ein Raster Komposit (bzw. Virtual Raster) aus den gegebenen Bändern.
* Visualisiert das Komposit in Falschfarben, sodass Vegetation rot erscheint.
* Berechnet den Normalized Difference Vegetation Index.
* Erstellt anschließend NDVI-Klassen. Orientiert euch dabei an folgender Einteilung.
* Stellt die Klassen farblich sinnvoll dar.

| Kategorie | NDVI |
| --- | --- |
|Wasser und Schnee| < 0 |
| Felsen, Sand, Gebäude | 0 - 0.2 |
| Gras, Sträucher | 0.2 - 0.4 |
| Wald und intensive Landwirtschaft | >0.4 |
