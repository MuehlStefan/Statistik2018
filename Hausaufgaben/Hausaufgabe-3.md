# Hausaufgabe 3

## Aufgabe 3.1
Berechnen Sie die Standardabweichung und den Mittelwert für das erreichte Lebesalter der Autoren in **Ihrem** Datensatz (d.h. nicht von den spanischen Autoren). Sie sollten die Daten in Pandas einlesen, aber die Pandas-Funktionen (Series.mean() und Series.std()) **nicht** verwenden, sondern die nativen Funktionen von Python (len, sum, einfache mathematische Kalkulation...; Sie dürfen jedoch sqrt von math benützen (import math; sqrt()).

## Aufgabe 3.2
Sammeln Sie einen weiteren Datensatz.

1. Suchen Sie ein Theaterstück in XML-TEI aus. Beispiele für Quellen:

* Deutsch: https://textgridrep.org/
* Englisch (Shakespeare): http://www.folgerdigitaltexts.org
* Französich: https://github.com/cligs/theatreclassique
* Spanisch: https://github.com/GHEDI/BETTE/tree/master/corpus
* Latein/Altgriechisch: http://www.perseus.tufts.edu/

Beispiel für Theaterstück in XML-TEI (Galdos, *Electra*):
* https://github.com/pielstroem/Statistik2018/blob/master/Datensaetze/bette006_Galdos_Electra.xml

2. Erzeugen Sie eine Tabelle, in der jede Zeile einer Person entspricht, mit folgenden Spalten:

* id
* label (Name der Person)
* gender
* role (protagonist, lover, antagonist, other)
* importance (primary, secondary, minor)
* per\_mes\_sps (Anzahl von Sprechakten dieser Person; dafür berechnen bzw. zählen wir wie viele sp (oder speaker) Elemente diese Person spricht

Sie können selber definieren, wie Sie die Werte für *role* (*protagonist, lover, antagonist, other*) und *importance* (*primary, secondary, minor*) den Personen zuteilen.

Beispiel für Tabelle:

https://github.com/pielstroem/Statistik2018/blob/master/Datensaetze/bette006_Galdos_Electra_nodes%3Dcharacters.csv

3. Lesen Sie die Daten in Pandas ein und zeigen Sie das Dataframe an. Berechnen Sie den Mittelwert von per\_mes\_sps des Theaterstücks (dieses Mal gerne mit .mean()).

Abgabeformat:
Nachname\_Nr\_Titel.pdf
Abgabetermin ist der 16.5.2018.
An: jose.calvo@uni-wuerzburg.de

