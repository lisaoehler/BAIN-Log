---
title: "Eintrag 09 - Metadaten modellieren und Schnittstellen nutzen (1/2)«
date: 2021-12-02
---

Einleitender Satz 

### Überblick über heutiges Thema
Wir werden heute mit den Metadaten arbeiten, die wir in Koha und Archivespace eingegeben haben. Ich hoffe, dass ich mit der Vorlesung mithalten kann, da ich Koha das letzte Mal nicht öffnen konnte und mir jetzt evtl. gewisse Inhalte fehlen. Zudem «harvesten» wir gewisse Daten von Koha und co. worauf ich bereits gespannt bin.

### Metadaten modellieren und Schnittstellen nutzen

BILD

Wie wir auf dem Bild sehen, stehen wir noch am Anfang. Wir haben in den letzten Vorlesungen Koha, ArchivesSpace und dSpace näher kennengelernt und die OAI-PMH Schnittstelle aktiviert. Nun müssen wir aus allen Systemen unsere Metadaten exportieren und danach (gegen Ende des Kurses) zusammenführen. Die Schwierigkeit hierbei ist, dass in den drei Systemen jeweils andere Metadatenstandards verwendet werden (MARC21-XML, EAD und Dublin Core). So müssen wir die zwei unpassenden Metadatenstandards jeweils mit der Software marcEdit in MARC21-XML umwandeln. 

Nun schauen wir uns die exportieren Daten von dSpace an. Bei mir hat der Export geklappt und ich habe die erste Zeile mit dem Code aus der Vorlesung ersetzt. Da ich erstaunt wäre, wenn mein Koha heute mitmacht, bin ich doch sehr froh darum, dass die Dozierenden für alle Systeme Beispieldaten bereitgestellt haben. 

### Austauschprotokolle für Metadaten (OAI-PMH, SRU)
Wir besprechen, was es alles für Übertragungsprotokolle (=Schnittstellen) im Bereich von Archiven und Bibliotheken gibt. Die meistverbreiteten sind: 
- Z39.50 (Library of Congress, hierzu braucht es Spezialsoftware)
- SRU (Search/Retrieve via URL (also im Browser abrufbar), ebenfalls Library of Congress)
- OAI-PMH (Open Archives Initiative Protocol for Metadata Harvesting)

Erstere beiden eignen sich gut für den Einzeldatenabruf oder die Livesuche, wohingegen OAI-PMH sich für einen Gesamtdatenabzug oder tägliche Aktualisierung eignet.

### Harvesten
Harvesten = Herunterladen von Daten (in unserem Fall von OAI-PMH Schnittstellen)

Wir öffnen die virtuelle Maschine und das Terminal. Wie gedacht, öffnet sich mein Koha nicht (Service unavailable). Hier werde ich also bei der Vorlesung zuschauen und dann für spätere Übungen die Beispieldaten verwenden. Ich speichere mir eines der Beispiele als XML-Datei auf der virtuellen Maschine ab. ArchivesSpace lädt noch. Ich erhalte nach einem neuen Laden der Browser-Seite folgende Meldung: «Parameter required but no value provided», was anscheinend OK ist. Bevor wir mit dem Exportieren der Metadaten beginnen können, müssen wir noch die entsprechende Software dazu (VuFindHarvest) auf unserer virtuellen Maschine installieren. Wir geben alle Befehle über das Terminal ein, so weit scheint bei mir alles funktioniert zu haben und das Programm ist erfolgreich installiert. 

Die Befehle zu ArchivesSpace haben soweit funktioniert und ich konnte sie auch einfach anpassen, dazu habe ich mir die Codezeile vom gemeinsamen Dokument in ein leeres TextEdit Dokument kopiert und die einzelnen Teile entsprechend überschrieben. Dies hat sehr geholfen, da ich mir bei der Kommandozeile immer etwas unsicher bin und nicht ausersehen einen Befehl auslösen möchte. Was mir noch unklar ist, ist wo genau hin ich jetzt etwas exportiert haben - in der Kommandozeile habe ich den Ort «archivesspace» definiert, aber ich habe bereits mehrere Ordner mit diesem Namen auf meiner virtuellen Maschine. Und innerhalb der nächsten paar Minuten konnte mir die Frage bereits durch die Dozierenden beantwortet werden, wir haben einen neuen Ordner namens «vufinderharvest» bei uns im Home. Da findet sich auch mein Ordner «archivesspace», in dem sich drei Dateien finden.

### Crosswalks
Hier lernen wir, wie wir Daten mit einem Metadatenstandard in Daten mit einem anderen Metadatenstandard umwandeln können (=Konvertieren -> hier «Crosswalk»). Schwierig ist hier, dass keine oder nur so wenige wie möglich Informationen verloren gehen oder nicht korrekt umgewandelt werden können. Wichtig ist, dass wir beim Mapping definieren, welche Felder von beiden Standards zusammengehören, wir stellen also neue Regeln auf. 

Nach einigem hin- und her habe ich es auch geschafft, je eine Datei von dSpace und ArchivesSpace umzuwandeln in MARCXML (bei ArchivesSpace brauchte es 2 Schritte).

 
