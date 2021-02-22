![Image](1.0.Landwirtschaft/kuh.jpeg?raw=true)
# Entwicklungen in der Schweizer und der Schaffhauser Landwirtschaft
Analyse von landwirtschaftlichen Daten des Bundesamts für Statistik für den Zeitraum 2000–2019

## Ausgangsthesen
*Die Schweizer Landwirtschaft (LW) befindet sich in einem starken Wandel*
### Schweiz
- Die Zahl der LW-Betriebe ist stark rückläufig.
- Die Zahl der LW-Beschäftigten ist rückläufig.
- Die weiblichen LW-Beschäftigten sind davon stärker betroffen.
- Die Fläche pro LW-Betrieb nimmt zu.
- Aufgrund des rückläufigen Fleischkonsums ist die Tierhaltung rückläufig.
- Geflügel-Haltung ist trotzdem zunehmend.
### Kantone
- Die Anzahl der LW-Betriebe ist in allen Kantonen rückläufig.
- Die Zahl der LW-Beschäftigten ist in allen Kantonen rückläufig.
- Die Fläche pro LW-Betrieb nimmt in allen Kantonen zu
- Alle Kantone haben ungefähr den gleich grossen Anteil Bio-Betriebe gegenüber konventionellen Betrieben.
- In allen Kantone ist der Anteil des biologisch gehaltenen Geflügels gegenüber des konventionell gehaltenen Geflügels ungefähr gleich.
### Schaffhausen
- Die Anzahl der LW-Betriebe ist in allen Schaffhauser Gemeinden ungefähr gleich stark rückläufig.
- Die Zahl der LW-Beschäftigten ist in allen Schaffhauser Gemeinden ungefähr gleich stark rückläufig.
- Der Kanton Schaffhausen hat einen durchschnittlichen Anteil an Bio-Betrieben
- Im Kanton Schaffhausen ist der Anteil von Bio-Geflügel im Schweizer Mittel

## Einschützung Aufwand/Ertrag vor Beginn des Projekts
Der Aufwand fürs Coden beträgt 2–3 Arbeitstage. Die Entwicklungen in der Landwirtschaft sind zwar nicht unbekannt, jedoch gab es bisher keine vertiefte datenjournalistische Aufarbeitung der Zahlen für den Kanton Schaffhausen. Zudem ist der Code so programmiert, dass seine Resultate auf "Tastendruck" aktualisiert werden kann, sobald neuere Daten vorliegen (aktueller Stand: 2019). Ebenso ermöglichen die erarbeiteten Datenframes die schnelle Erstellung weiterer Auswertungen auf den Ebenen Schweiz, Kantone und Gemeinden.

## Knackpunkte
- Der Datensatz des BFS ist so umfangreich und interessant, dass es schwierig war, sich nur auf die Ausgangsthesen zu fokussieren. 
- Die Datenaktualisierung auf 2020 ist noch nicht erfolgt, was aber bald geschehen soll – eine Publikation macht erst dann Sinn.

## Zusammenfassung Briefing-Gespräch
akjfölaskjföaslkjföaslkfj alkfjölakjföaslkjf

## Verwendete Datensätze
- LW-Daten: BFS "Beschäftigte, Landwirtschafliche Betriebe, Landwirtschaftliche Nutzfläche (LN) und Nutztiere auf Klassifizierungsebene 1 nach institutionellen Gliederungen" [Link](https://www.bfs.admin.ch/bfs/de/home/statistiken/kataloge-datenbanken/daten.assetdetail.12727132.html)
- Geometrie Gemeinden: Shapefile "swissTLMRegio_HOHEITSGEBIET_LV95" [Link](https://shop.swisstopo.admin.ch/de/products/landscape/boundaries3D)
- Geometrie Kantone: Shapefile aus dem DDJ-Kurs ("g1k17.shp" von Simon Schmid)

## Vorgehen
1. Daten beschaffen und Grobübersicht verschaffen (3h)
1. Gespräch mit Briefing-Person (1h)
1. Daten reinigen (3h)
1. Daten visualisieren (8h)
1. Daten analysieren (2h)
1. Thesen justieren: Thesen sind weitgehend korrekt, Unterschiede zwischen Kantonen und Gemeinden sind allerdings grösser als angenommen. Ebenso zeigt sich bei der Anzahl der gehaltenen Tiere (ausser Geflügel) grundsätzlich eine Stagnation und kein Rückgang – zusammen mit dem Geflügel ergibt sich sogar ein deutlicher Anstieg.

## Weiteres Vorgehen
1. Aufsplitten auf die Themen "Strukturwandel/Beschäftigung", "Entwicklung Bio-Landwirtschaft" und "Entwicklung Geflügelhaltung"
1. Ergänzen durch klassische Recherche (Landwirtschaftsamt, Bauernverband, etc.)
2. Verfassen einer Landwirtschaft-Artikelserie zu den genannten Themen
3. Weitere Analysen/Visualisierungen erstellen für allfällige weitere Folgen der Landwirtschaft-Serie

## Geplante Publikation
*Nach erfolgter Datenaktualisierung auf 2020*
### Serientitel: "Schaffhauser Landwirtschaft im Umbruch"
#### Titel Folge 1: "Immer mehr Bauernhöfe verschwinden"
Lead: "Die Anzahl der Bauernhöfe nimmt rasant ab, dafür werden sie immer grösser. Gleichzeitig wird die Nutzfläche von immer weniger Beschäftigten "beackert". Besonders betroffen sind Hallau, Beggingen, Merishausen, Neuhausen am Rheinfall und Buch."

![Image](1.0.Landwirtschaft/Rueckgang_LW_SH.png?raw=true)
![Image](1.0.Landwirtschaft/Beschäftigung_SH.png?raw=true)
#### Titel Folge 2: "Wenig 'Bio' bei der Schaffhauser Landwirtschaft"
Lead: Im Vergleich mit anderen Kantonen gehört die Schaffhauser Landwirtschaft in Sachen "Bio" zu den Schlusslichtern. Das sind die Gründe dafür und das will der Kanton dagegen tun.  

![Image](1.0.Landwirtschaft/Biobetriebe_Kantone.png?raw=true)
![Image](1.0.Landwirtschaft/Bio.png?raw=true)
#### Titel Folge 3: "Alles is(s)t Huhn"
Lead: "Der Fleischkonsum pro Kopf ist in der Schweiz zwar rückläufig, trotzdem stagniert die Zahl der in der Landwirtschaft gehaltenen Tiere. Die grosse Ausnahme ist das Geflügel, dessen Bestände stark wachsen. "Bio" ist das wenigste davon."  

![Image](1.0.Landwirtschaft/Tierhaltung_CH.png?raw=true)
![Image](1.0.Landwirtschaft/biohuhn.png?raw=true)
