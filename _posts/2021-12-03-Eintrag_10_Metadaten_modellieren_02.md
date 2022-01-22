---
title: "Eintrag 10 - Metadaten modellieren und Schnittstellen nutzen (2/2)"
date: 2021-12-03
---

### Metadaten modellieren und Schnittstellen nutzen (2/2)
Bei der letzten Vorlesung haben wir noch die exportierten Metadaten-Dateien (von Koha, dSpace und ArchivesSpace), welche noch nicht alle den gleichen Metadatenstandard besitzen, in den Metadatenstandard MARC21 umgewandelt. Heute ergänzen wir die Daten noch mit Daten aus Tabellen, wie beispielsweise aus Excel-Datein. Diese Daten müssen oft erst noch etwas geordnet und bereinigt und in einen gemeinsamen Standard umgewandelt werden, bevor sie in eine gemeinsame Datenbank eingespiesen werden können. 

### Transformation von Metadaten mit OpenRefine
Das Programm verfügt über eine grafische Oberfläche (wie zB Microsoft Excel) - somit braucht man keine umfassenden Programmierkenntnisse, um es bedienen zu können. Die Daten sollen mit dem Programm analysiert, bereinigt, konvertiert und sogar angereichert werden. Dies ist für Datensammlungen wie beispielsweise Bibliotheken sehr nützlich, da es sich oft um sehr grosse Datensätze handelt, bei deren ursprünglicher Erstellung schnell ein Fehler unterlaufen sein könnte. Da das Programm auf dem eigenen Rechner installiert und ausgeführt sind, werden die bearbeiteten Daten «vertraulich» und sicher behandelt. Es handelt sich hier nicht um eine cloudbasierte Software. 

OpenRefine wir nicht nur in der Bibliotheksbranche eingesetzt, sondern auch in Archiven, im Bereich Data Science und Semantic Web usw. Vor allem Tabellendaten wie beispielsweise XLS, CSV und TSV werden von OpenRefine als Format unterstützt. Auch XML und JSON kann bearbeitet werden. Handelt es sich um XML mit komplexeren Hierarchien wie EAD, müssen unter Umständen noch zusätzliche Tools ergänzt werden. 

Es gibt verschiedene Einsatzmöglichkeiten von OpenRefine. Einerseits lassen sich damit Datenlieferungen untersuchen, andererseits kann man damit die Qualität der vorhandenen Daten verbessern, indem man die Daten vereinheitliche und bereinigt. Zudem können Abgleichungen mit Normdaten vorgenommen werden. 

### OpenRefine
Das Installieren der Software war sehr einfach, da wir die Befehle kopieren konnten. Der Zugriff auf das Programm über einen Webbrowser ist ebenfalls von Vorteil. Nachdem wir über einen Link Beispieldaten in OpenRefine geladen haben, bildet OpenRefine damit eine Tabelle. Mich würde es noch wundern, wie genau der Datensatz ausgesehen hat, den wir importiert haben, um zu sehen, wie genau OpenRefine die Daten abbildet, ob etwas nicht abgebildet werden kann oder etwas inkorrekt importiert/dargestellt wird. Das Programm scheint simpel aufgebaut zu sein und es sieht auf den ersten Blick recht Übersichtlich aus. Was mich etwas stört, ist dass wenn man in der Tabelle scrollt, die Spaltenüberschriften verschwinden. Evtl. Gibt es eine Einstellung, um die erste Zeile einzufrieren, aber bis jetzt habe ich dazu noch nichts gesehen. Für die nachfolgenden Übungen, die wir lösen werden, sind anscheinend bereits absichtlich einige Fehler eingebaut worden.


### Installation VuFind
Für mich wäre es von Vorteil gewesen, wenn wir die Installation gemeinsam in der Vorlesung durchgeführt hätten. Bei Fragen hätten wir uns sogleich an die Dozierenden wenden können also irgendwo alleine stecken zu bleiben und dann beispielsweise Emails senden zu müssen. Zudem ist die Installation recht Zeitaufwändig. Ich kenne mich kaum mit Befehlen auf der Kommandozeile aus und habe einfach sozusagen blind copy-paste von der verlinkten Webseite übernommen, ohne wirklich zu verstehen, was nun endlos lange im Terminal geladen wird. Gerade der Befehl «sudo apt-get dist-upgrade» hat endlose Zeilen von Code ausgelöst und kaum mehr aufgehört. Aus der Erklärung vom gemeinsamen Dokument ging zudem nicht hervor, ob wir dieses update/upgrade überhaupt brauchen…




