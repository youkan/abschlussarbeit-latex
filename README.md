Liebe Nutzerin, lieber Nutzer dieser Vorlage,

diese Vorlage soll dir helfen deine Abschlussarbeit (Bachelor, Master,
Diplom,...) zu schreiben. Sie ist von der Typografie her an Deutschland
angepasst, die Titelseite ist speziell für das Corporate Design der Universität
Ulm entstanden.


Benutzung

Im oberen Teil der diplom.tex Datei sind von dir diverse Daten einzusetzen,
Name und Matrikelnummer, Titel der Arbeit, alles was später benötigt wird. In
Zeile 99 findet sich ein Todo, hier ist noch das Institut einzusetzen.
Kommentiere die richtige Fakultät ein.

In Zeile 141 zeigt ein Kommentar, das ab hier die eigentlichen Kapitel der
Arbeit eingebunden werden sollen. Ein Beispielkapitel ist in der Vorlage
enthalten (einleitung.tex).

Kurz vor dem Ende der Datei hat es noch auskommentierte Zeilen für die
verschiedenen Bibliografiestile. Diese sind nach DIN, verwende einfach den, der
in deinem Institut eingesetzt wird oder dir am besten gefällt.


Das TeXen

Meist wirst du einen Editor verwenden, der dir einiges an Unterstüzung bietet.
Die Vorlage ist für pdflatex optimiert, dein Editor sollte direkt ein PDF
erzeugen.


Dateiformate

Die Vorlage ist als UTF8 gespeichert, es hat noch eine Version in iso8859-1 und
mac. Die meisten Editoren können mittlerweile UTF8, falls es partout nicht geht
kannst du einfach die Datei diplom.tex löschen und eine der anderen beiden
umbennen. Dann solltest du noch in Zeile 26 bis 28 anpassen, in welchem Format
die Datei ist. Folgende Programme lassen sich direkt mit UTF8 nutzen:

Linux: kile, Texmaker, gedit (mit plugins) Mac: TeX-Shop Windows: Texmaker

je nach Programm muss noch eingestellt werden, dass die Dateien in UTF8 sind
(Texmaker, Tex-Shop).

UTF8 wurde gewählt, weil dieses Format Umlaute und Sonderzeichen direkt
unterstützt. Auch deutsche Anführungszeichen lassen sich ohne Sonderbefehle
nutzen.


Ulm 24.3.2009  Guido de Melo


# abschlussarbeit-latex

This repo contains a template to typeset your BSc or MSc thesis. It was developed primarily for computer science students at the university of Ulm, Germany.

# Willkommen!

Liebe Nutzerin, lieber Nutzer dieser Vorlage,

diese Vorlage soll dir helfen deine Abschlussarbeit (Bachelor, Master, Diplom,...) zu schreiben. Sie ist von mir speziell für das Corporate Design der Universität Ulm angepasst worden.


## Benutzung

Im oberen Teil der diplom.tex Datei sind von dir diverse Daten einzusetzen, Name und Matrikelnummer, Titel der Arbeit, alles was später benötigt wird. Kommentiere die richtige Fakultät ein.

Danach zeigt ein Kommentar, das ab hier die eigentlichen Kapitel der Arbeit eingebunden werden sollen. Ein Beispielkapitel ist in der Vorlage enthalten (einleitung.tex).

Kurz vor dem Ende der Datei hat es noch auskommentierte Zeilen für die verschiedenen Bibliografiestile. Diese sind nach DIN, verwende einfach den, der in deinem Institut eingesetzt wird oder dir am besten gefällt.


## Das TeXen

Meist wirst du einen Editor verwenden, der dir einiges an Unterstüzung bietet. Die Vorlage ist für pdflatex optimiert, dein Editor sollte direkt ein PDF erzeugen.


## Dateiformate

Die Vorlage ist mit dem Zeichensatz UTF-8 gespeichert. Das ist der Zeichensatz der überall verwendet werden sollte, denn damit lassen sich alle Sprachen der Welt schreiben. Außerdem ist es angenehmer direkt ä zu schreiben als \"{a} oder ähnliches. Auch echte deutsche Anführungszeichen lassen sich ohne Sonderbefehle nutzen („“).

Die meisten Editoren können mittlerweile UTF8, z.B. TexMaker, kile, gedit. Da TexMaker Anfängerfreundlich und einfach zu bedienen ist hier noch kurz die Anleitung für seine Benutzung. Stell im Menü unter Options > Configure Texmaker unter Editor das "Editor Font Encoding" auf UTF-8. Lade die Datei diplom.tex und lasse sie mit einem Klick auf den Kopf "pdflatex" oben durch TeX laufen. Anschließend kannst du das Ergebnis mit einem PDF-Betrachter ansehen.


## Zu guter Letzt

Diese Vorlage kann frei von dir verwendet und geändert werden. Falls du Vorschläge hast oder einen Fehler findest kannst du mir eine Mail schicken.

Viel Spaß beim TeXen und viel Erfolg mit deiner Abschlussarbeit!
Guido de Melo


# License
Wird noch ergänzt.