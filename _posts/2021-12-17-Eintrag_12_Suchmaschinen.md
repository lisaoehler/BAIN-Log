---
title: "Eintrag 12 - Suchmaschinen und Discovery-Systeme»
date: 2021-12-17
---



### Allgemeines
Die letzte Vorlesung vor Weihnachten - wir befinden uns im Endspurt. Ziel ist es, am Ende der Vorlesung sämtliche bis jetzt erstellten (und umgewandelten) Datensätze in VuFind einzuspeisen. 

### Nachtrag zu Metadaten modellieren und Schnittstellen nutzen
Metadaten-Management ist nicht nur ein Randthema für Systembibliothekare, sondern wird auch vermehrt in anderen Bereichen eingesetzt und angewendet. Wir haben bis jetzt OpenRefine als Tool kennengelernt. Es zeichnet sich vor allem durch die grafische Oberfläche von anderen Tools ab, da Transformationsergebnisse direkt sichtbar werden. Dies macht die Benutzung durch Beginner einfacher, da man sofort sieht, was passiert. Es können verschiedene Skriptsprache für (komplexe) Transformationen angewendet werden, wie beispielsweise GREL, Jython und Clojure. Der Schwerpunkt liegt auf der Datenanreicherung. Es lassen sich natürlich auch noch weitere Dinge mit OpenRefine umsetzen. Natürlich gibt es auch noch weitere Tools - alternative Software sind Catmandu, Metafacture und MarcEdit. 

### Suchmaschinen und Discovery-Systeme
In der letzten Vorlesung haben wir uns noch alle VuFind auf unseren virtuellen Maschinen installiert - dies hat so weit auch geklappt. VuFind ist eine weltweit verbreitete Software. Je nach Institution sieht der Auftritt der jeweiligen Webseiten etwas anders aus, da es sich um eine Open-Source Software handelt und man jeweils seine eigenen Anpassungen bzw. Erweiterungen vornehmen kann. 

Funktion von Suchmaschinen am Beispiel von Solr
Solr ist ebenfalls eine Open-Source Lösung in Form einer Suchfunktion. Damit kann beispielsweise Volltextsuche oder Facettensuche betrieben werden. Solr ist (soweit ich dies korrekt verstanden habe) ein Teil vom Discovery-System VuFind (wurde in VuFind integriert). Das Konkurrenzprodukt von Solr ist Elasticsearch, ebenfalls Open Source. 
Als erstes muss bei einem geplanten Import zuerst definiert werden, welche Felder überhaupt existieren sollten bzw. welche Datentypen (Text, Zahlen, Boolsche Werte etc.) diese enthalten sollen (anhand eines Schemas). Die Benutzeroberfläche wird in der Regel von einer anderen Software bereitgestellt, in unserem Fall von VuFind. 

Was ist der Unterschied zwischen einer Datenbank (MySQL) und einem Suchindex (Solr)? Bei Solr steht die (semantische) Suche (Retrieval) der Daten im Vordergrund. Die Daten sind statisch und es handelt sich um flache Dokumente, die abgelegt sind. Bei MySQL, also einer Datenbank, handelt es sich um relational Datensätze, die veränderlich sind. Im Fokus steht die Aufbewahrung (Storage) der Daten. 

Nun gibt es eine Gruppenübung - Unterschiede von Suche in VuFind Vs Suche in Solr
Die Ansichten unterscheiden sich (OPAC vs Metadaten), wobei bei Solr Detailinformationen gleich mutangezeigt werden. Bei VuFind muss dazu noch ein Klick mehr getätigt werden. Hyperlinks sind bei beiden hinterlegt, jedoch nur bei VuFind aktiv (anklickbar). Je nach Suchbegriff werden bei beiden +/- die gleiche Anzahl von Treffern ausgegeben. Bei VuFind erleichtert die grafische Oberfläche das Lesen der Inhalte, bei Solr muss man sich zuerst an den Code gewöhnen.

In der nächsten Gruppenarbeit laden (und entdecken) wir dann noch unsere Beispieldaten bzw. die von uns zuvor in MARCXML konvertierten Daten. 





