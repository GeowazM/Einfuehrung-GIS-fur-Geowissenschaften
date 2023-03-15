# Übung 6
## Ziel der Übung
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

* Sentinel-2 data (Source: [Copernicus](https://scihub.copernicus.eu/))
* SRTM DEM (Source: [USGS EROS Customer Services](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-shuttle-radar-topography-mission-srtm-1))

## Aufgaben

### Aufgabe 1: Arbeiten mit Geländemodellen
* Bringt das SRTM-Höhenmodell in eine metrische Projektion (z.B. WGS84/UTM 33N).
* Verschafft euch einen Überblick über die Höhenwerte. Was sind die maximalen und minimalen Höhen im Untersuchungsgebiet. Schaut dies in den Layer-Eigenschaften nach. 
* Berechnet aus dem SRTM-Höhenmodell Konturlinien 100 Meter Schritten. Vergleicht es mit 1 Meter Schritten.
* Berechnet ein Hillshade.

### Aufgabe 2: Arbeiten mit Sentinel-2 Daten
* In dieser Aufgabe arbeiten wir mit Daten der Sentinel-2 Mission. Wir nutzen für unsere Analyse die Bänder 2, 3, 4 & 8. Welchen Farben entsprechen diese Bänder?
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

### Aufgabe 3: 3D Visualisierung erstellen
* Erstellt ein Polygon (Vektordatei), mit dem ihr die Sentinel-2 Daten und das SRTM Höhenmodell verkleinern (clippen) könnt. Ziel ist es ein Untersuchungsgebiet um den Vesuv zu definieren.
* Installiert das Plugin *Qgis2threejs*. Startet den *Qgis2threejs Explorer*, aktiviert das SRTM Höhenmodell & das Sentinel-2 Bild. Tipp: Ändere die Überhöhung (exaggeration) in den Scene Settings zu 2.5.
* Schaut euch das Modell an, findet eine gute Perspektive und exportiert diese als .png 


