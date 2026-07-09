## EP.01 | Kleines Einmaleins der thematischen Kartographie | Dasymetrische Choroplethenkarte

### Berliner Bevölkerung 2024 [Arbeitsauftrag 1]

In dieser Aufgabe haben wir 3 verschiedenen Methoden zur Darstellung von Bevölkerungsdaten erstellt. Eine absolute und eine relative Chloroplethenkarte waren zwei der Darstellungen und die dritte war eome dasy,etrische Chloroplethenkarte, bei der die Bevölkerungszahlen auf tatsächlich bewohnten Flächen verteilt wurde. Diese drei Versionen mussten wir auf 1 Layout nebeneinander stellen, um den Unterschied der Darstellung sichtbarer zu machen und damit die bevölkerungsverteilung genauer interpretiert werden kann. 

<img width="2000" height="1413" alt="Download" src="https://github.com/user-attachments/assets/a7913cbc-82a3-43e1-aeaf-967b2ba207cd" />

## EP.02 | Kleines Einmaleins der thematischen Kartographie | Gitterchoroplethenkarten

### Kirschbäume in Berlin [Arbeitsauftrag 2]

Hier war es unsere Aufgabe, eine, in der Lehrveranstaltungs erstellte, Gitterchoroplethenkarte zu reproduzieren, nur als ein Hexagonengitter. Grundlage  bildete ein Datensatz der die Berliner Straßenbäume und ihre Position enthielt. Aus diesem wurden alle Kirschbaumarten gefiltert und dann innerhalb von Hexagonen mit einer Seitenlänge von 500m zusammengefasst. Die Darstellung ermöglicht eine übersichtliche Analyse der räumlichen Verteilung von Kirschbäumen im Berliner Stadtgebiet. 

<img width="2000" height="1413" alt="Download (1)" src="https://github.com/user-attachments/assets/2d42a15e-b218-4549-8843-75a1b0fb69a0" />

## EP.03 | Punktrasterkarten

### Kirschenbäume in Berlin - Darstellung mit SVG Datei [Arbeitsauftrag 3]

Auf Grundlage des bereits verwendeten Datensatz, aus dem 2. Arbeitsauftrag, haben wir in einer Lernveranstaltung ein Punkteraster erstellt. Um die Verteilung der Kirschebäume visuell hervorzuheben und eine kartrographisch ansprechende Darstellung zu erreichen, haben wir dann individuell gestalte SVG-Symbole benutzt, um sie im Platz von den Punkten, bzw. hexagonen einzufügen. Ihre größe passt sich der jeweiligen Menge der Bäume in diesem gebiet an. 

<img width="3507" height="2480" alt="Blütenbäume in Berlin - SVG" src="https://github.com/user-attachments/assets/07fd6ca4-fec2-4b77-b587-ef86a4e18b2e" />

### Kirschbäume in Berlin - Punkteraster [Arbeitsauftrag 4]

In 4. Arbeitsautrag sollten wir die SVG-Darstellung als eigenständiges Punkterasterkarte darstellen. Die Kirschbaumdaten wurden als Punkte dargestellt, wobei die Größe und die Farbgebung, ähnlich wie bei den Karten zuvor, die Anzahl der Kirschbäume repräsentiert.

<img width="3507" height="2480" alt="Punktlayout_JonasKrüger" src="https://github.com/user-attachments/assets/028c4202-cfe4-4784-a0d1-e43ecc6e99ac" />

## EP.04 | Value-By-Alpha Mapping

### Ungarn_Wahlen_2026 - Value-By-Alpha Mapping/Chloroplethenkarte [Arbeitsauftrag 5]

Das Kartenlayout visualisiert die Ergebnisse der ungarischen Parlamentswahl 2026 auf Ebene der Wahlbezirke. Die in der Lehrveranstaltung erstellte Value-by-Alpha-Map kombiniert eine regelbasierte Symbolisierung, bei der die Gewinnerpartei (Tisza oder Fidesz) durch den Farbton dargestellt wird, während die Transparenz den jeweiligen Vorsprung zwischen den Parteien visualisiert. Ergänzend wurden zwei Choroplethenkarten erstellt, welche die Stimmenanteile von Fidesz und Tisza bezogen auf die Wahlberechtigten in den einzelnen Wahlbezirken darstellen.

<img width="4960" height="3507" alt="Ungarn_Wahlen" src="https://github.com/user-attachments/assets/b0439588-021b-4e59-b203-2a0bb3dda56a" />

## EP.05 | Ursprung-Ziel-Karten

### Ukraine Flüchtlingsbewegung 

In dieser Übung wurde eine Ursprung-Ziel-Karte (Origin-Destination Map) in QGIS erstellt, welche die Fluchtbewegungen aus der Ukraine in verschiedene Aufnahmeländer visualisiert. Grundlage bilden die UNHCR-Flüchtlingsdaten für das Jahr 2025, wobei die Ukraine als Ursprungsland und sämtliche Zielländer berücksichtigt wurden.

Für die Erstellung der Karte wurden die UNHCR-Daten zunächst mit den Natural Earth Admin-0-Länderdaten über die ISO-Ländercodes verknüpft. Anschließend wurden die Zielländer mit registrierten ukrainischen Flüchtlingen ausgewählt, deren Zentroiden berechnet und mithilfe des Werkzeugs XY to Line Ursprung-Ziel-Linien erzeugt. Durch eine benutzerdefinierte orthografische Projektion wurde die Erde auf die Ukraine zentriert und als Globus dargestellt.

Die Linienstärke sowie die Größe der Zielpunkte wurden anhand der Anzahl der aufgenommenen ukrainischen Flüchtlinge abgestuft. Dadurch lassen sich die wichtigsten Aufnahmeländer auf einen Blick erkennen und miteinander vergleichen.

<img width="3507" height="2480" alt="Earth_Ukraine" src="https://github.com/user-attachments/assets/fb7fe34d-277a-4c4f-9f5e-7e86e993b27c" />

### Flüchtlingsbewegungen nach Deutschland

In dieser Übung wurde eine Ursprung-Ziel-Karte (Origin-Destination Map) in QGIS erstellt. Grundlage bilden die UNHCR-Flüchtlingsdaten für das Jahr 2025, wobei Deutschland als Zielland gewählt wurde. Ausgehend von den Herkunftsländern wurden Linien zum Zentrum Deutschlands erzeugt, um die wichtigsten Fluchtbewegungen darzustellen.

Für die Umsetzung wurden zunächst die UNHCR-Daten mit den Natural Earth Admin-0-Länderdaten über ISO-Codes verknüpft. Anschließend wurden die Herkunftsländer gefiltert, Zentroiden berechnet und mithilfe des Werkzeugs XY to Line Ursprung-Ziel-Linien erstellt. Durch eine benutzerdefinierte orthografische Projektion wurde die Erde auf Deutschland zentriert und als Globus dargestellt.

Zur Verbesserung der Übersichtlichkeit wurden nur Herkunftsländer mit mindestens 1.000 registrierten Flüchtlingen berücksichtigt. Dadurch werden die wichtigsten Fluchtbewegungen hervorgehoben und die Karte bleibt trotz der Vielzahl an Datensätzen gut lesbar. Zusätzlich wurde die Linienstärke nach der Anzahl der Flüchtlinge abgestuft, sodass größere Fluchtbewegungen unmittelbar erkennbar sind.

<img width="3507" height="2480" alt="Erde_Deutschland_Top_Einwanderer" src="https://github.com/user-attachments/assets/ec0ab9da-0d3b-4034-a659-5f4e4fad7880" />


## EP.06 | Tilemaps

### Berlin - Legokarte 

Für die Berliner Lego-Karte wurde ein regelmäßiges Gitter über das Untersuchungsgebiet gelegt und mit Höheninformationen aus einem digitalen Geländemodell verknüpft. Durch die Symbolisierung der Gitterzellen im Lego-Stil entsteht eine vereinfachte, aber gut erkennbare Darstellung der Reliefunterschiede innerhalb Berlins.

<img width="4960" height="3507" alt="Berlin_Lego" src="https://github.com/user-attachments/assets/589567a2-1312-4b64-ac22-eee7adac1a0a" />

### Deutschland - Legokarte

Für die Deutschland-Karte wurde derselbe Workflow wie bei der Berliner Lego-Karte angewendet. Dabei wurden die bereits entwickelten Symbolisierungs- und Stileinstellungen übernommen und lediglich an die größere räumliche Ausdehnung sowie den Wertebereich des deutschlandweiten Höhenmodells angepasst, um das Relief Deutschlands im Lego-Stil darzustellen.

<img width="3507" height="4960" alt="Deutschland_Lego" src="https://github.com/user-attachments/assets/06ec9115-05cb-422d-8684-abb6a4822f43" />

## EP.07 | Animation in QGIS

### Meteorschauer - 12/13 August - Deutschland

Für diese Karte wurden Meteorbeobachtungen eines ausgewählten Meteorstroms für Deutschland ausgewertet und zeitlich animiert dargestellt. Die Flugbahnen der Meteore wurden aus den Beobachtungsdaten berechnet und als Linien visualisiert, wodurch die räumliche Verteilung sowie die zeitliche Entwicklung des Meteorstroms während einer Nacht nachvollzogen werden können.

<img width="1256" height="737" alt="perseiden_animation" src="https://github.com/user-attachments/assets/f1d39a11-552e-42fa-91d0-2ee004d8df45" />

### Meteorschauer [Arbeitsauftrag_7] 

Die Animation zeigt die über Bulgarien beobachteten Meteore des Geminiden-Meteorstroms am 13. Dezember 2025. Die Flugbahnen wurden aus Beobachtungsdaten rekonstruiert und minutengenau animiert dargestellt, wodurch die zeitliche Verteilung der beobachteten Sternschnuppen im Untersuchungsgebiet nachvollzogen werden kann.

Aus Gründen der Dateigröße wurde für die Einbindung in GitHub eine zeitlich verdichtete Version der Animation verwendet. Die ursprüngliche Animation wurde minutengenau erstellt.

<img width="1756" height="950" alt="Meteorschauer" src="https://github.com/user-attachments/assets/fd3b4ad3-2603-431b-8704-f184288ac6fe" />

## EP.08 | Mesh-Daten

### Orkan Kyrill Animation [Arbeitsauftrag_8]

Für diesen Arbeitsauftrag haben wir eine GIF-Animation der Windgeschwindigkeiten des Orkans Kyrill für den Zeitraum vom 16. bis 21. Januar 2007 erstellt. Die Daten stammen aus dem ERA5-Reanalyse-Datensatz des Copernicus Climate Change Service (C3S) und wurden in QGIS zeitlich animiert. Zur Gestaltung wurde ein künstlerischer Stil mit dunklem Hintergrund und angepasstem Farbverlauf verwendet. Die Animation enthält einen Zeitstempel sowie ein Impressum mit Quellenangabe.

<img width="1380" height="710" alt="Arbeitsauftrag_8" src="https://github.com/user-attachments/assets/0c570e0b-3deb-469a-9cd1-03591446809d" />

## EP.09 | 3D-Gebäudemodelle

### 2,5D-Gebäudemodell Thüringen [Arbeitsauftrag_9.1]

In diesem Arbeitsauftrag wurde für einen ausgewählten Bereich in Thüringen eine 2,5D-Darstellung von Gebäuden erstellt. Als Datengrundlage dienten die LoD2-Gebäudedaten des Thüringer Geoportals, welche in QGIS importiert und mit dem integrierten 2,5D-Renderer visualisiert wurden.

Für die Darstellung wurde die im Datensatz enthaltene Gebäudehöhe (measuredHeight) verwendet, wodurch die Gebäude entsprechend ihrer tatsächlichen Höhe extrudiert werden. Zusätzlich wurden Perspektive und Symbolisierung angepasst, um eine übersichtliche und räumliche Darstellung des ausgewählten Stadtgebietes zu erzeugen.

<img width="1691" height="1188" alt="Thüringen_Erfurt_25" src="https://github.com/user-attachments/assets/ef58d477-fc02-4182-91b3-3b1a4b6741ea" />

### 3D-Gebäudemodell Sachsen [Arbeitsauftrag_9.2]

Für diesen Arbeitsauftrag mussten wir  eine 3D Ansicht, von einem Bereich aus Sachsen. Hierfür wurden LoD2-Gebäudedaten der Friedrichstadt in Dresden aus dem Geoportal Sachsen heruntergeladen und als Shapefile in QGIS importiert. Anschließend wurden die Daten in der 3D-Kartenansicht visualisiert, wodurch die Gebäude anhand ihrer hinterlegten Höheninformationen als dreidimensionales Stadtmodell dargestellt werden. Über die 3D Ansicht von Qgis konnte man nun die Stadt oder den Bereich, in meinem Fall, als 3D Modell betrachten. 

<img width="2555" height="1372" alt="Screenshot 2026-07-09 205419" src="https://github.com/user-attachments/assets/58abb0bf-1af9-4eea-88ff-2ff676e86767" />

