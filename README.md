# Persoenlicher Konto-Tracker

**Dieses Tool wurde mit Python und R entwickelt, um persoenlicher Kontodaten zu verfolgen und personalisierte Finanzberichte zu erstellen. Mit diesem Tool kann man jede Ein- und Auszahlung erfassen und Berichte generieren, damit sich ein Einblick in die aktuelle finanzielle Situation geben laesst.**

## Installation und Ausfuehrung

Um dieses Tool zu installieren und auszufuehren, sollte man wie folgt vorgehen:

1. "Fork" und klonen dieses Projekt auf den lokalen Computer.
2. Installieren Python und R, falls die nicht bereits auf dem Computer sind.
3. Fuehren das Skript **init.py** aus, um eine .csv Datei fuer die Eingabe der Kontodaten zu generieren.
   > **Beachten den Kommentar in Zeile 15!**
   >
   > Fuer jeden Monat dieses Script einmal neu auszufuehren, um eine neue .csv Datei fuer diesen Monat zu generieren. 
4. Beachten die Kommentare im Skript **input.py** und aendern die entsprechende Code nach dem Bedarf.
   > **Zeile 10, 13, 16, 29, 38!**
5. Fuehren das Skript **input.py** aus, um die Kontodaten einzugeben.
6. Fuehren abschliessend das Skript **report.R** aus, um die Finanzberichte zu generieren.
   > In diesem Ordner sollte dementsprechend eine neue .pdf Datei generiert werden, in dem sich ein paar schoene Diagramme befinden sollten.

[![Beispiel Bericht](/Users/a11/Desktop/GitHub/Konto_Trace/beispiel.png)](https://github.com/qnChuan/Konto_Trace/blob/master/beispiel.png)

## Mitwirkung und Kontakt

Wenn Sie Vorschläge oder Feedback zu diesem Tool haben oder einen Beitrag dazu leisten möchten, kontaktieren Sie uns bitte oder reichen Sie einen Pull-Request ein. Unsere Kontaktinformationen lauten wie folgt:

- E-Mail: ...
- GitHub: ...


<!-- License:
...
e
Trace für jede Einzahlung und 
Auszahlung der Konten und Karten.

Ziel ist zu erreichen, dass man genau
weißt, wofür das Geld ein- und aus-
zählt, indem man jeden Tag dies Script kurz verwendet. Danach wird man am Ende des Monats...oder Jahrende individuelle Finanzreport kriegen

// format, highlight, color...

python and r...

Steps:
    1. run init.py
    2. lese die Kommentare in input.py duch und danach run input.py
        was kann/soll modifiziert werden
    3. Im Ordner kann man generierte pdf öffnen -->