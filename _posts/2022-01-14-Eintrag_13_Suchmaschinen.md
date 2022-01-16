---
title: "Eintrag 13 - Linked Data»
date: 2022-01-14
---

Es geht dem Endspurt zu - die letze Vorlesung zu BAIN, und die erste Vorlesung im neuen Jahr. Über die Festtage hatte ich genügend Zeit, um die letzten beiden Vorlesungen, welche ich verpasst hatte, nachzuholen und um die Übungen in Ruhe durchzuarbeiten und nachvollziehen zu können. 

### Nachtrag zu Discovery Systemen - Marktüberblick
Jährlich werden von Marshall Breeding ein Report zu den aktuellsten Library-Systems (es finden sich darin Bibliothekssysteme und auch Discovery-Systeme) erstellt und im ALA Magazin veröffentlicht. Zum internationalen Marktführer gehört die Software Primo von Ex Libris. Eine Alternative dazu wäre beispielsweise OCLC mit WorldCat Discovery. Wie wir gelernt haben, besteht die Funktionalität von Discovery-Systemen aus der Software (beispielsweise unser Interface mit VuFind) sowohl auch aus den Daten (der hinterlegte Index). Suchindexe werden kommerziell meist separat verkauft, darin finden sich zB Metadaten zu den Medien. Zu den Open Source Produkten gehören eben VuFind. Hierzu gibt es jedoch keinen eigenen Artikelindex - wir haben uns ja selbst einen erstellt. 

Wie sieht es in der Schweiz aus?
Durch SLSP (Swiss Library Service Platform) wurde grossflächig Ex Libris Alma (inkl. Discovery-System Primo VE) an den teilnehmenden Bibliotheken eingeführt. Das dazugehörige Rechercheportal (die Plattform, über welches die Nutzenden Medien suchen und bestellen können) heisst swisscovery. 

### Evaluation der Lehrveranstaltung
Gemeinsam in der Vorlesung haben wir noch die Feedbacks über die Vorlesungen diskutiert. Wie sich herausstellte, hatten sich zwei Lager gebildet. Persönlich finde ich das Modul sehr anspruchsvoll und technisch ausgelegt. Da ich selbst nicht viel Wissen von Bibliotheken mitbringe, war für mich vieles neu oder unverständlich. Für künftige Veranstaltungen wäre es toll, mehr explorative Übungen einzubauen (anstatt nur blind zu copy-pasten) und für die Studierenden, die keinen Bibliotheks-/Archivhintergrund mitbringen, mehr Beispiele und Erklärungen zu zeigen. 

### Linked Data (moderne Form zur Strukturierung von Daten)
Es gibt zwei Datenmodelle (für Metadaten) die noch in Entwicklung sind:
Alt: MARC21 -> neu: Bibframe (Bibliothek)
Alt: EAD -> neu: RiC (Archiv)

Bibframe wird künftig MARC21 ersetzen. Bibframe basiert teilweise auf FRBR (Functional Requirements for Bibliographic Records) sowie RDA (Resource Description and Access). Neu gilt das «Linked Data Paradigmen», was bedeutet, dass nicht mehr alle Informationen in einen einzelnen Datensatz verpackt werden, sondern einzeln abgespeichert und dann miteinander verlinkt werden - so werden Redundanzen und Doppelspurigkeiten vermieden.
Bibframe wird so in Model (was wird beschrieben) und Vocabulary (wie wird etwas beschrieben) unterschieden. 

Bibframe Model = saubere Unterteilung in die Ebenen Work / Instance / Item. Ein Datensatz ist eine Entität. Jede Entität (Work, Instance, Item) besitzt Eigenschaften, die teilweise hierarchisch strukturiert sind. 

RiC (Records in Context) basiert ebenfalls auf Linked-Data Prinzipien. Auch hier werden nun einzelne Entitäten erstellt, die zueinander in Beziehung stehen. So können neu zwischen Entitäten auch mehrfache  Beziehungen erstellt werden (keine strikte Baumstruktur mehr wie bei ISAD-G). 








