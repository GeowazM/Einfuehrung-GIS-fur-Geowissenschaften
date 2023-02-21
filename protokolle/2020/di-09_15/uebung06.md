# Protokoll 09.06.2020 09:15

## Begrüßung

**Tutoren:**
- Marco Kern
    - m.kern@stud.uni-heidelberg.de
- Matthias Schaub
    - schaub@stud.uni-heidelberg.de


## Organisation

 1. Abgabe 1 ist korrigiert
    - Signaturen (40)
    - Kartengestaltung (40)
    - Elementgestaltung (20)
2. Abgabe 2 ist am 12.06.
3. Übung 6


## Wiederholung

Häufige Fehler vermeiden:
https://www.youtube.com/watch?v=1BkWy8RFDh4

- Rasterdaten im GIS öffnen und kennenlernen
- farbliche Darstellung der Rasterwerte anpassen
- Rasterdaten in Vektordaten umwandeln
- Globale Rasteroperationen anwenden (z.B. Projektion ändern)
- Lokale Rasteroperationen anwenden (z.B. NDVI berechnen)


### ASTER

- Instrument an Board des Satelliten Terra.
- Advanced Spaceborne Thermal Emission and Reflection Radiometer (ASTER)
- Global Digital Elevation Model can be derived from the data


### Band/ Kanal

In der Übungsaufgabe nach dem erstellen eines virtuellen Rasters ist:
- Kanal 1 = Kanal 2 Blau (Landsat)
- Kanal 2 = Kanal 3 Grün (Landsat)
- Kanal 3 = Kanal 4 Rot (Landsat)
- Kanal 4 = Kanal 5 nahes Infrarot/ near infra-red (NIR) (Landsat)


### Falsch Farben

Falsch Farben Darstellung entsteht durch die Kombination verschiedener Bänder.

Falsche Farben für Vegetation (Color Infrared (vegetation)) ist RGB 5 4 3

Ergebnis: https://transfer.sh/15XA3L/falsch-farben.png

Siehe auch:
- Landsat Bands
    - https://de.wikipedia.org/wiki/Landsat#Instrumente
    - https://www.usgs.gov/faqs/what-are-best-landsat-spectral-bands-use-my-research?qt-news_science_products=0#qt-news_science_products
- Band Combinations:
    - https://www.esri.com/arcgis-blog/products/product/imagery/band-combinations-for-landsat-8/
    - https://earthobservatory.nasa.gov/features/FalseColor/page6.php


### NDVI

https://www.usgs.gov/land-resources/nli/landsat/landsat-normalized-difference-vegetation-index?qt-science_support_page_related_con=0#qt-science_support_page_related_con

NDVI = (Band 5 – Band 4) / (Band 5 + Band 4)


## Wer möchte in einen Breakoutroom um gemeinsam an der Übung zu arbeiten?

- ...

