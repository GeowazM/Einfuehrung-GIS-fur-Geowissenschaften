# Übung 3
## Ziel der Übung.
* Nicht-räumliche Abfragen durchführen.
* Räumliche Abfragen durchführen.
* Geometrieoperationen nutzen (z.B. die Fläche eines Polygons berechnen).

## Wiki:
* [Nicht-Räumliche Abfragen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Nicht-Räumliche-Abfragen)
* [Räumliche Abfragen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Räumliche-Abfragen)
* [Geometrieoperationen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Geometrieoperationen)

## Daten
Ladet euch [die Daten herunter](exercise_03_data.zip) und speichert sie auf eurem PC.
* World Administrative Boundaries Level 0 (Countries) (Polygon) (Quelle: [World Food Programme WFPGeonode](https://geonode.wfp.org/layers/geonode%3Awld_bnd_adm0_wfp))
* Urban Agglomerations Datensatz (Point) (Quelle: [UN World Urbanization Prospects 2018](https://population.un.org/wup/))

## Aufgaben

1. Öffne die oben angegebenen Dateien in QGIS.
2. Wähle 3 Städte deiner Wahl (manuell) in der Benutzeroberfläche aus. Öffne nun die Attributtabelle und lass dir die Informationen für die ausgewählten Features anzeigen. Speichere die ausgewählten Features anschließend in einer neuen Datei (Layer). 
3. In welcher Einheit liegen die Einwohnerzahlen vor? Dies ist für die folgenden Aufgaben wichtig.
4. Wähle nun anhand einer Abfrage (automatisch) alle Städte, welche im Jahr 2015 mehr als 15 Millionen Einwohner hatten. Wie viele Städte gibt es, die diese Bedingung erfüllen? Welche Stadt hat die meisten Einwohner?
5. Führe nun eine kombinierte Selektion durch. Selektiere zunächst alle Städte in China. Entferne anschließend alle Städten mit einer Einwohnerzahl kleiner als 1 Million aus dieser Auswahl. Wie viele Millionenstädte gibt es in China?
6. Berechne die Fläche jedes einzelnen Features in Quadratmeter. (Bei Fragestellungen dieses Typs ist es besonders wichtig die Projektion der Daten zu beachten. Wir nutzen hier hier Mollweide (EPSG: 54009), eine flächentreue Projektion.) Welches ist das kleinste Land der Welt und wie groß (klein) ist es? Unter Land verstehen wir hier alle Features mit dem Status *Member State*.
