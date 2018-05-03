# Hausaufgabe 3

## 1
Berechnen Sie die Standardabweichung und den Mittelwert des Anzahls von gelebten Jahren von **Ihren** Autoren (d.h. nicht von den spanischen Autoren). Sie sollten die Daten in Pandas einlesen, aber die Pandas funktionen (Series.mean() und Series.std()) **nicht** verwenden, sondern die native Funktionen von Python (len, sum, einfache mathematische Kalkulation...; Sie dürfen doch sqrt von math benützen (import math; sqrt()).

## 2
Sie sollen einen anderen Datensatz sammeln.

1. Suchen Sie ein Theaterstück in XML-TEI aus. Beispiele für Quellen:

* Deutsch: https://textgridrep.org/
* Englisch (Shakespeare): http://www.folgerdigitaltexts.org
* Französich: https://github.com/cligs/theatreclassique
* Spanisch: https://github.com/GHEDI/BETTE/tree/master/corpus

Beispiel für Theaterstück in XML-TEI (Galdos, *Electra*):
* https://github.com/pielstroem/Statistik2018/blob/master/Datensaetze/bette006_Galdos_Electra.xml

2. Erzeugen Sie eine Tabelle, in der jede Reihe eine Person entspricht, mit folgenden Spalten:

* id
* label (Name der Person)
* sex
* role (protagonist, lover, antagonist, other)
* importance (primary, secondary, minor)
* per\_mes\_sps (Anzahl von Sprechakten dieser Person; dafür berechnen bzw. zählen wir wie viele sp (oder speaker) Elemente diese Person spricht

Beispiel für Tabelle:

https://github.com/pielstroem/Statistik2018/blob/master/Datensaetze/bette006_Galdos_Electra_nodes%3Dcharacters.csv

3. Lesen Sie die Daten in Pandas ein und zeigen Sie das Dataframe an. Berechnen Sie den Mittelwert von per\_mes\_sps des Theaterstücks (dieses Mal gerne mit .mean()).

Abgabeformat:
Nachname\_Nr\_Titel.pdf
Abgabetermin ist der 16.5.2018.
An: jose.calvo@uni-wuerzburg.de

