# Übung 8
## Ziel der Übung
* Räumliche Interpolation anwenden
* Rasterfunktionen vertiefen

## Wiki:
* [Räumliche Interpolationsverfahren](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Räumliche-Interpolationsverfahren) 
* [lokale Rasterfunktionen](https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/qgis-Konvertierung)


## Daten
Lade dir [die Daten herunter](exercise_08_data_new.zip) und speichert sie auf eurem PC. Lege einen lokalen Ordner an und speichere dort die obigen Daten. (.zip Ordner müssen vorher entpackt werden.)
* Höhenmodell: germany_dem.tif (Quelle: [GTOPO30 USGS](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-global-30-arc-second-elevation-gtopo30?qt-science_center_objects=0#qt-science_center_objects))
* Messstationen: [DWD]([https://www.geo.fu-berlin.de/en/v/soga/Geodata-analysis/geostatistics/Data-sets-used/DWD-weather-data-Germany/index.html](https://www.dwd.de/DE/leistungen/cdc/climate-data-center.html;jsessionid=19070115479E2AED22A5D5D622F8CA58.live31083?nn=17626))

## Aufgaben
### Aufgabe 1: Von der Textdatei zu Geodaten
* Bringe die Daten in ein geeignetes Koordinatensystem (z.B. WGS84/UTM 32N).
* Importiere die Tabelle in QGIS. Hinweis: Achte auf die Formatierung (engl. vs. dt.)


### Aufgabe 2: Temperaturwerte interpolieren.
* Schaue dir nach dem erfolgreichen importieren der Daten die Attributtabelle an und notiere dir den Spaltennamen für die Jahresdurchschnittstemperatur.
* Inpterpoliere anhand der gewonnenen Werte die Durchschnittstemperaturen in Deutschland.
  * Nutze dazu Inverse Distanz Gewichtung (IDW)
  * und einen Power-Wert von 2 
* Style das Ergebnis, sodass Temperaturunterschiede deutlich erkennbar werden.

Das könnte dann ungefähr so aussehen:
![temperatur_idw_pow2](temperatur_idw_pow2.PNG)

*(Wer findet den Fehler in dieser Abbildung? Welche Messstation liefert einen möglicherweise falschen Wert?)*
