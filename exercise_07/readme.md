# Übung 7
## Ziel der Übung
* Rasterdaten zuschneiden  
* Reliefanalysen durchführen
* zonale Statistiken berechnen
* Rasterdaten in Vektordaten umwandeln
* ein Höhenprofil erstellen

## Wiki:
* [Rasterdaten in Vektordaten umwandeln](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Konvertierung)
* [fokale Rasteroperationen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Fokale-Funktionen)
* [zonale Rasteroperationen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Zonale-Funktionen)
* [weitere Rasteroperationen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Weitere-Rasterfunktionen)

## Daten
Ladet euch die Daten vom USB-Stick und speichert sie auf eurem PC. Legt einen lokalen Ordner an und speichert dort die obigen Daten. (.zip Ordner müssen vorher entpackt werden.)
* Linien-Layer: trails (Quelle: OpenRouteService, OpenStreetMap and Contributors)
* Polygon-Layer: national_parks (Quelle: OpenStreetMap and Contributors)
* Raster-Layer: ASTER Höhendaten (Quelle: METI/NASA)

## Aufgaben
### Aufgabe 1: Vorbereitung
* Bringt die Höhendaten in eine passende metrische Projektion (z.B. WGS 84 / UTM 37N).
* Schneidet (**Clip**) den Raster-Datensatz auf die Ausdehnung des Nationalpark-Layers zu.

### Aufgabe 2: Reliefanalysen
* Berechnet zunächst einen **Hillshade** für das Geländemodell. Tipp: Nutze die Processing - Toolbox, um Funktionen zu finden.
* Ermittelt die Hangneigung in ° (via **Slope**).
* Erstellt Übersichtsstatistiken für die beiden Nationalparks (bspw. mit Hilfe von **Zonal Statistics**).
  * Was ist die maximale Hangneigung pro Nationalpark?
  * Wie hoch ist die durchschnittliche Hangneigung pro Nationalpark?
* Glättet euer Ergebnis in dem ihr pro Pixel den Durchschnitt der 11x11 Nachbarschaft berechnet (via **r.neighbors**).
* Selektiert besonders steile Regionen (>30°) (nutzt dazu zunächst den Raster Calculator oder das **Reclassify Tool**)
* Konvertiert die Auswahl ins Vektorformat. Tipp: Du kannst auch das **Basic statistic per field** für die Rasterdatei nutzen.

### Aufgabe 3: Höhenprofil
* Erstellt für die Sirimon-Route im trails-Layer ein Höhenprofil.
* Das Höhenprofil soll auf der x-Achse die Distanz in Meter zeigen & auf der y-Achse die Höhe ü.N.
* Tipp: Achtet auf die einzelnen Schritte des Erklärvideos für das Plugin, was ihr hierfür nutzt. Kleinigkeiten können hier entscheidend sein.

Das könnte dann ungefähr so aussehen:
![profile](sirimon_route_profile.png)
