# Über dieses Projekt
Die Basis dieser Analyse ist der von kiva.org auf kaggle.com zur Verfügung gestellte Datensatz [^1]. Diese Daten werden in einem ersten Schritt aufbereitet und mit KPIs angereichert. Anschließend wird eine Betrachtung im EDA-Stil durchgeführt. Dabei werden insgesamt drei Diagramme erstellt, angepasst und analysiert. Die Analyse des letzten Diagramms enthält Ansatzpunkte für weitere Schritte. Darüber hinaus wurde aus diesem letzte Diagramm auch ein einfaches, interaktives Dashboard erstellt.

Der Code besteht aus 3 Jupyter Notebook Dateien:
1. 1_kiva_Ausgangssituation:<br>
   Hier ist die Fragestellung sowie das Business und Data Understanding enthalten. Diese Punkte bilden die Grundlage der Analyse.
2. 2_kiva_Aufbereitung:<br>
   In diesem Dokument werden die Daten eingelesen, aufbereitet und mit weiteren Infos in Form von KPIs angereichert. Inhalt der Aufbereitung ist dabei die Handhabung von Duplikaten, Synonymen und fehlenden Werte sowie die Speicherplatzoptimierung des Datensatzes. Am Ende wird dieser als pickle Datei gespeichert, um im nächsten Dokument wieder eingelesen werden zu können.
3. 3_kiva_EDA_und_Dashboard:<br>
   Nach der Datenaufbereitung wird in diesem Schritt die eigentliche Analyse durchgeführt. Dabei wird zunächst ein Thema identifiziert. Anschließend werden die Diagramme erstellt, um dieses Thema genauer zu beleuchten. Dabei bauen die Grafiken aufeinander auf.

Hinweis: Dieses Projekt ist im Zuge des Data Analytics Kurses von alfatraining als Abschlussprojekt entstanden.

# Genutzte Bibliotheken
Der Code ist komplett Python (3.11.3) basiert und in Jupyter Notebook (6.5.4) geschrieben. Die genutzten Bibliotheken und deren Versionen können der Datei requirements.txt entnommen werden.

# Benutzung
Installiere ggf. die oben aufgeführten Versionen und Bibliotheken. Führe jetzt den Code von 2_kiva_Aufbereitung.ipynb Zelle für Zelle von oben nach unten aus. Anschließend führe den Code von 3_kiva_EDA_und_Dashboard.ipynb ebenfalls Zelle für Zelle von oben nach unten aus.<br>
Im Anschluss kann in den Diagrammen gezoomt und gescrollt werden. Außerdem kann oben links im Dashboard der Sichtbereich der Karte in einer Auswahlliste manuell eingestellt werden. Hinweis: Das Dashboard öffnet sich in einem neun Browser Tab! Wenn das nicht der Fall ist, dann kann ganz unten in der 3_kiva_EDA_und_Dashboard Datei ein Link dazu gefunden werden.

# Zukunft dieses Projektes
Wie oben bereits erwähnt, enthält das letzte Diagramm Ansatzpunkte für weitere Analysen. Diese könnten im Hinblick von Thema 1 weiter verfolgt und grafisch untersucht werden. Außerdem gibt es zu Beginn der Datei 3_kiva_EDA_und_Dashboard.ipynb einen Überblick über zusätzliche Ideen und Fragestellungen, die weitere Themen bilden und ebenfalls untersucht werden könnten.<br>
Ich bin nicht sicher, ob etwas davon passieren wird oder mein Fokus sich auf die Auswertung anderer Datensätze richten wird.

[^1]: [Kaggle Kiva Datensatz](https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding)