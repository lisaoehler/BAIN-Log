---
title: "Eintrag 07 - Repository-Software für Publikationen und Forschungsdaten"
date: 2021-11-19
---

Wir haben uns in den vergangenen Vorlesungen nun ausführlich mit den Funktionen und dem Aufbau von Archiv- und Bibliothekssystemen beschäftig. Weiter geht es nun mit Repository-Software für Publikationen und Forschungsdaten.

### Begriffe Web und Cloud (Begriffsklärung)
Web-basierte Systeme können ausschliesslich über einen Web-Browser bedient werden (wie Koha), wohingegen cloud-basierte Systeme zwar auch über einen Web-Browser bedient werden können, das System selbst jedoch nicht bei den Benutzern selbst auf einem Server liegt. Das entsprechende Programm ist auf dem Server des Herstellers abgelegt und die Kunden (Nutzer) greifen alle auf diesen zu. Die Nutzenden sehen bei sich aber ihre eigene Umgebung und haben ihre eigenen spezifischen Einstellungen, so dass man eigentlich nicht merken sollte, dass das Programm nicht auf dem eigenen Server abgelegt ist. 

### Nachtrag zu Funktionen und Aufbau von Archivsystemen - Marktüberblick
Ein Beispiel für eine Software ist wie beim letzten Mal erwähnt ArchivesSpace, dies ist in der Schweiz aber anscheinend (noch) nicht so weit verbreitet. Hier gibt es den Dienstleister docuteam welcher unterschiedliche Angebote für Archive bietet. Ein Beispiel ist AtoM, ebenfalls eine OpenSource Software die man kostenlos austesten kann. Weiter gibt es noch eine Reihe von kommerziellen Produkten. Beispiele hierfür sind scopeArchiv und CMI AIS. 

### Unterschiede zwischen Bibliotheks- und Archivsystemen
Bibliotheken und Archive haben unterschiedliche Grundprinzipien. Bibliotheken besitzen Medien, die für den täglichen Gebrauch und zur Unterhaltung gedacht sind. Es werden hier keine Originale, Sonden teilweise sogar mehrere Kopien des gleichen Exemplars aufbewahrt. Entsprechend orientiert sich Software für Bibliothekssysteme an den Medien selbst - denn die Kunden wollen schnell zu ihren Produkten kommen. Wie bereits angesprochen werden auch unterschiedliche Metadatenformate verwendet, hier für Bibliotheken MARC21.
In einem Archiv liegt der Fokus auf der Aufbewahrung von Einzelstücken und Kulturgütern. Wichtig sind hier vor allem der Entstehungszusammenhang - es werden auch mehrere Dokumente in Verbindung zueinander, beispielsweise ein Geschäft oder ein Dossier, aufbewahrt anstatt einfach nur einzelne Medien. Kunden (also Nutzer) kommen hier nicht her, um regelmässig ein Buch auszuleihen, sondern um Recherchen zu betreiben. So wird der Bestand in einem Archiv nicht 24/7 benützt, sondern steht oft still. Software für Archivsysteme orientieren sich so an analogen Findmitteln und Metadatenformat ist hier EAD.

### Repository-Software für Publikationen und Forschungsdaten
Hier folgt eine kurze Repetition zu Open Access  und Open Data: Generell sind Open Access Publikationen wie Journalbeiträge oder Forschungspapiere, die i.d.R. als Zweitveröffentlichung der breiten Öffentlichkeit frei zugänglich gemacht wird. Die Artikel finden sich meist in fachspezifischen Open-Access-Repositorien. Open Data sind Forschungsdaten, meist Primärdaten, sie ebenfalls zugänglich gemacht werden. So können beispielsweise Experimente überprüft werden oder es können von Dritten weitere Forschungen zu gleichen oder weiteren Themen betrieben werden. Die Daten werden in Forschungsdaten-Repositorien gesammelt. 

Da es sich hierbei um unterschiedliche grosse Datengrössen handelt, unterscheiden sich die Softwares voneinander. Wir legen den Fokus in der Vorlesung auf DSpace. Interessant ist, dass man durch eine Erweiterung auch Forschungsinformationen (=Infos über Forschende selbst, Projekte, Patente etc) mit DSpace verwalten kann. 

Was ist DSpace? DSpace ist eine Software für die Verwaltung von Publikationen und Forschungsdaten. Der verwendete Metadatenstandard ist Qualified Dublin Core. Es gibt bereits mehrere Versionen von DSpace, wir werden mit dem kostenfreien Browserinterface arbeiten. Die zwei Übungen haben einwandfrei funktioniert. Um externen Systemen zu ermöglichen, in dSpace hinterlegte Metadaten abzurufen, verwenden wir OAI-PMH. 
