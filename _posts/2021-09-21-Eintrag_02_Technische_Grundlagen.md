---
title: "Eintrag 02 - Dies ist die Ergänzung zum Thema Technische Grundlagen"
date: 2021-09-21
---


Nachdem ich nun im ersten Beitrag dieser Lerntagebuchserie über meine allgemeine Einstellung zum Modul BAIN berichtet habe, lege ich nun den Fokus auf den tatsächlichen Inhalt der ersten Vorlesung. Nach der Einführung und einer kurzen Orientation über das Thema des Moduls konnten wir bereits selbst etwas ausprobieren und interaktiv am Unterricht teilhaben, was etwas neues ist.

Wir arbeiten während den Vorlesungen alle zusammen als Gruppe an einem gemeinsamen Dokument, welches online im Browser für uns verfügbar ist. Um Inhalte zu ergänzen verwenden wir Markup. Wie schon erwähnt, baut dieses Modul auf mehreren Grundlagenmodulen auf. Diese liegen nun doch schon mehrere Semester zurück, zudem besuchte ich einige der Module noch im Studiengang Digital Business Management, ich vertraue nun darauf, keine allzu grossen Lücken zu haben.

Wichtig ist, dass wir in dieser Vorlesung die Virtuelle Maschine zum laufen bringen und und mit der command-line vertraut machen. Im Verlauf des Studiums haben wir bereits mehrere solcher virtuellen Maschinen mit horizon installiert. Wobei manche einwandfrei und andere überhaupt nicht funktionierten… Aber heute scheint alles zu funktionieren. Vor allem die Möglichkeit, die Virtuelle Maschine über den Browser zu öffnen, ist sehr toll. In einem anderen Modul, in dem wir auch eine Virtuelle Maschine benützen und über den VMClient auf unserem Laptop zugreifen müssen, hängt mein Bildschirm immer. 

### Nun, was habe ich in der heutigen Vorlesung gelernt?
Das wichtigste, was ich von der heutigen Vorlesung mitgenommen habe, ist die ausführliche Erklärung im Umgang mit der Unix Shell. Dies wurde uns zuvor nicht so genau erklärt und entsprechend erlebte ich heute mehrere «Ahas».  Zur Übung verwendeten wir die Lerneinheiten der Library Carpentry (Lesson zur Unix Shell). Um künftig schnell spicken zu können, gebe ich folgend einige Befehle wieder:

Wenn wir die Shell öffnen und sie bereit für neue Prompts ist, sollte ein $ auf der Zeile erscheinen. 

##### Navigation

Befehl | Beschreibung 
--- | --- 
pwd | Zeigt an, wo im Directory (unseres Laptops) wir uns befinden
ls | Gibt Liste mit allen Ordnern und Dokumenten aus, auf dessen Ebene wir gerade sind
ls -l | Gibt uns noch Zusatzinformationen an (zB owner der Datei)
ls -lh | Gibt uns zudem noch Grösse der Dateien an (in kb, b…)
cd DateiX | So kommen wir tiefer in unsere Ordnerstruktur hinein (tiefer in die Hierarchie hinein)
cd .. | Um wieder einen Schritt nach oben zu wechseln
cd | ohne einen Ordnernamen nach cd landen wir auf unseren Desktop zurück


##### Einfaches Arbeiten mit Dokumenten und Ordnern

Zuerst wechseln wir an den Ort, an dem wir etwas neues einfügen möchten. 
Zb: cd Desktop/Dokumente/BAIN

Befehl | Beschreibung 
--- | --- 
mkdir | gefolgt von einem Namen erstellt einen neuen Ordner
mkdir Aufgaben | erstellt also einen Ordner namens «Aufgaben»
cat Beispiel.txt | Angewendet auf eine Textdatei wird uns der gesamte Text ausgegeben
head Beispiel.txt | so erhalten wir nur den ersten Teil des Textes
tail Beispiel.txt | so erhalten wir nur den letzten Teil des Textes
mv Beispiel.txt neuerName.txt | bewegt einen neuen Namen auf die Datei (alt -> neu)
mv Beispiel.txt Aufgaben | bewegt die Textdatei in einen Ordner (auf Höhe des Directory)
cp Beispiel.txt BeispielKopie.txt | Erstellt eine Kopie des gewählten Dokuments


Dies scheinen mir für den Anfang die wichtigsten Befehle zu sein, um mich hier in der Shell zurechtzufinden. 
