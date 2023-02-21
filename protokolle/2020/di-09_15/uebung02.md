# Protokoll 05.05.2020 09:15

## Begrüßung

**Tutoren:**
- Marco Kern
    - m.kern@stud.uni-heidelberg.de
- Matthias Schaub
    - schaub@stud.uni-heidelberg.de


## Organisation

- erste Abgabe am 22.05.


## Wiederholung

### Karten

**Map**
- A map is a graphic representation of a part of the surface of the Earth (or another planet) that exposes the following characteristics (Wolfgang Scharfe)
  - has a scale
  - generalized
  - georeferenced
  - uses symbols to encode information
  - annotated with textual explanations
  - representation in the plane [german: verebnet]
  - planimetric

**Kartenelemente:**
- Titel
- Legende
- Maßstab (bar + lexical)
- Autor
- Quellen
- Nordpfeil (optional bei genordeten Karten)
- Kartenausschnitt (optional)
- Koordinaten Referenz System


### Maßstab

**cartographic scale**
- ratio between distances on the map and distances in reality

**lexical scale**
- SCALE 1:2000000

**bar scale**
- also called linear scale

**size**
- 1:5,000 (large scale) > 1:500,000 (medium scale) > 1:5,000,000 (small scale)



### Label

**Why to use labels in maps?**
- names and other complex information otherwise hard do convey
- semantics is, in most cases, already known

**Why not to use labels in maps?**
- labels harder to read than cartographic signs
- reading labels takes longer than reading cartographic signs (preattentive processing not possible)

**What to use labels for?**
- Names
  - New York City, Heidelberg, Mühltalstraße
- Descriptions
  - Kleine Höhle, Schutzhütte
- Abbreviations and acronyms
  - A 1, B 225
- Numbers
  - Hausnummern, Höhenangaben
- ...

**Label placement**
- label in proximity to the corresponding map sign (helps associating the label to the map sign)
- labels can uniquely be related to the map signs (helps associating the label to the map sign)

**Label placement in case of point symbols**
- suitable distance to the labelled map sign
- preferred positions: right and above

**Label placement in case of linear symbols**
- suitable distance to the labelled map sign
- preferred positions: left and above
- parallel aligned to the labelled map sign
- potentially: repeated use of the label
- potentially: tracking

**Label placement in case of areal symbols**
- placed inside the labelled area
- placed in the centre of gravity (for square-sized areas)
- placed along the main axis (for long areas)
- fill the area: font size, tracking


### Ziele der Übung
- Eigene Vektorsignaturen gestalten.
- Eine Karte gestalten und typische Elemente wie Legenden, Nordpfeile und Maßstabsleisten hinzufügen, Hinweis auf Autor und Datenquellen.
- Eine Karte als PDF-Dokument exportieren.

- https://docs.qgis.org/3.10/en/docs/training_manual/map_composer/map_composer.html
- https://docs.qgis.org/3.10/en/docs/training_manual/basic_map/symbology.html



## Fragen

- zu Legende: Symbol aus der Karte zum Layerelement erscheint nicht in der Legende?
- zur Karte im Drucklayout: In dem Feld für die Karte ist außen ein recht großer Rand, wie bekomme ich es hin dass die Karte dieses Feld mehr ausfüllt?
- Wie aktiviert man denn das Grid?
    - https://courses.gistools.geog.uni-heidelberg.de/giscience/gis-einfuehrung/wikis/home/QGIS/Kartengestaltung#kartenrahmen-gestalten-grid-hinzuf%C3%BCgen
- Muss der textuelle Maßstab auf dem Endergebnis (also auf dem Drucklayout) auch angegeben werden? Oder reicht der Maßstabsbalken?
    - Der textuelle Maßstab sollte auch auf der Karte (Endergebnis) sichtbar sein.

**Offene Fragen:**

Die Karte mit dem Maßstaab 1:110000 füllt nur ein Bruchteil des Drucklayouts (A4). Ist dieser dann sinnvoll gewählt? (Je nach EPSG ist der Kartenausschnitt im Drucklayout unterschiedlinch groß.)

Ist es möglich in der Legende einem Polygon Layer ein Strich Symbol zuzuordnen? Bsp. Stadtteile in Übung 2 eine gestrichelte Linie statt einem gestrichelten Polygon.


## Wer möchte in einen Breakoutroom um gemeinsam an der Übung zu arbeiten?

- ...


## Sonstiges

- https://colorbrewer2.org/
- Cartography Guide: https://www.axismaps.com/guide/


## Inspirationen

- http://hint.fm/wind/ (Fehlt der Maßstaab)
