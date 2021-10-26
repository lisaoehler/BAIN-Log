---
title: "Eintrag 03 - Funktionen und Aufbau von Bibliothekssystemen (1/2)"
date: 2021-10-01
---



Nachdem wir in der letzen Vorlesung die Grundlagen für das Modul besprochen haben, geht es heute weiter mit der ersten Theorie. Damit wir alle starten können, mussten wir jedoch zuerst noch unser Git auf der virtuellen Maschine prüfen. 

### Von Gabeln und Klonen
Als Einstiegsübung und zur Repetition der ersten Vorlesung befassten wir uns noch einmal mit GitHub und unserer Shell. Ziel der Übung war es, ein bereits vorhandenes Repository von GitHub auf das eigene Verzeichnis unserer virtuellen Maschine zu kopieren. Danach könnten wir lokal Änderungen an einem der Dokumente vornehmen und in einem zweiten Schritt die Änderungen wieder in das originale Repository, welches wir kopiert haben, zurücksenden. Hört sich in der Theorie einfach an, war in der Umsetzung jedoch bereits kompliziert. 

Der Vorteil dieser Aktion ist, dass verschiedene Leute gemeinsam an einem Projekt arbeiten können, so dass es einen gemeinsamen Redaktionsworkflow gibt. Durch die Methode von GitHub ist so zudem die Versionierung der einzelnen Änderungen sichergestellt.

Bei dieser Übung haben wir zudem eine Reihe neuer GitHub-Begriffe gelernt, hier einige Beispiele:
«fork» um eine Kopie des Repositories zu erstellen
«clone» um ge-«forkte» Dateien herunterzuladen
«commit» um Änderungen (mit Notiz) hochzuladen
«pull-request» um die Übernahme der Änderungen anzufragen

All dies haben wir über unsere Shell in der virtuellen Maschine gemacht. Dazu haben wir eine Reihe neuer Befehle kennengelernt, welche ich hier nicht nochmals wiedergeben werde. Es war eine tolle Übung, um uns mit der Shell und auch GitHub besser vertraut zu machen. Mir fällt es bereits einfacher, mich durch mein Repository zu navigieren und mich generell auf der Plattform zu bewegen.

### Theorieteil
Nach der praktischen Übung geht es weiter mit dem ersten Theorieteil des Moduls. Wir widmen uns dem Thema Bibliothekssysteme. Dazu befassen wir uns zuerst mit dem Metadatenstandard MARC21 (für Bibliotheken) und danach mit der Installation des Koha-Programms für unsere virtuelle Maschine.

Von vorherigen Modulen ist mir noch geblieben, dass MARC (MAchine Readable Cataloging) in den 60ern entwickelt wurde. Dabei gibt es verschiedene nationale Formate wie zB USMARC. Die Orientation (Fokus) von MARC liegt bei Informationsobjekten vom Typ Buch. Zudem war der Inhalt der Katalogisate beschränkt, da sie zuerst auf Katalogkarten und später digital (jedoch mit beschränkter Feldlänge) angelegt wurden. Ob dies heute immer noch so ist, weiss ich nicht. Die verschiedenen Auslegungen von MARC wurden dann 1999 in MARC21 vereint und zusammengefasst. 

Verglichen mit anderen Standards, wie zB Dublin Core, scheint MARC21 viel umfangreicher zu sein. Zudem ist das Format für Leute, die nicht viel mit diesen Standards zu tun haben, eher schwer verständlich. MARC21 scheint sich spezifisch für Bibliotheken zu eignen, wohin Dublin Core auch für andere Branchen eingesetzt werden könnte.

Zuletzt noch zu Koha - soweit ich verstanden habe, benützen wir dieses Programm um Bibliothekssoftware zu simulieren. Der Download war simpel und sobald man in den Browser wechselt, konnte man der online-Anleitung folgen. Diese scheint jedoch nicht ganz up-to-date zu sein, da es einige kleine Differenzen gab (zB gab es bei der Passwortwahl für den Admin strengere Vorgaben oder es wurden zT mehr Felder zum Auswählen zur Verfügung gestellt). 
