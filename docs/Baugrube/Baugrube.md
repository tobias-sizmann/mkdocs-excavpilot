<style>
    setCenter{
        justify-content: center;
    }
</style>

# Baugrube

Im excav Pilot können Baugruben direkt im Feld aus Punktmessungen erstellt werden. Eine Baugrube besteht immer aus:

- einer horizontalen Sohle,
- einem optionalen Arbeitsraum um die Sohle,
- einer Böschung, definiert durch Böschungshöhe und Böschungswinkel

Eine Baugrube beschreibt somit einen vollständigen Aushubkörper, der aus beliebig vielen einzeln aufgenommenen Randpunkten erzeugt werden kann.

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Ansicht Baugrube (5).jpg"/>
</p>


## Neue Baugrube erstellen

Zur Erstellung einer neuen Baugrube öffnet man zunächst das Design-Menü, wählt dort den Eintrag Baugrube aus und klickt anschließend auf Neue Baugrube anlegen.

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Ansicht Baugrube (1).jpg"/>
</p>

1. Zuerst wird ein Name für die Baugrube vergeben, z. B. „Baugrube Haus A“, „Schacht Nord“ oder ähnlich. 

2. Als nächstes die Eckpunkte der **Sohle** mit dem aktuell aktiven Werkzeug aufnehmen oder bereits aufgenommene Punkte hinzufügen. Die Punkte müssen in der richtigen Reihenfolge entlang der Außenkante aufgenommen werden. Eine Baugrube benötigt mindestens drei Punkte, kann aber beliebig viele haben.

!!! info "Wichtig - Werkzeug vor Aufnahme auswählen" 
    Das verwendete [Messwerkzeug](https://docs.excav.de/Werkzeuge/Werkzeuge/) muss vor dem Start des Baugrubenassistenten ausgewählt sein.
    Beispiel: Wenn die Punkte mit dem [Messstab](https://docs.excav.de/Messstab/Messstab/) aufgenommen werden sollen, muss der Messstab vorher als Werkzeug aktiv sein. Gleiches gilt für die Aufnahme mit dem Löffel. Hier ist zu beachten, welche Ecke gerade aktiv ist.

3. Parameter der Baugrube definieren - nach Abschluss der Punktaufnahme erscheint die Eingabemaske für die Eigenschaften der Baugrube. 

     - **Höhenreferenz**: Es muss eine Referenzhöhe gewählt werden – entweder einen Punkt antasten oder zuvor aufgenommenen Punkt wählen.
     - **Solenhöhe zur Referenzhöhe**: Dieser Wert definiert die relative Solenhöhe der Baugrube bezogen auf die gewählte Referenz.
     - **Böschungshöhe**: Gibt die vertikale Höhe der Böschung an.
     - **Böschungswinkel**: Der Böschungswinkel kann in Grad oder Prozent eingetragen werden.
     - **Arbeitsraum**: Optional kann ein zusätzlicher Arbeitsraum um die Sohle definiert werden

!!! info "Beispiel: Baugrube mit konkreten Werten"
    Stellen wir uns vor, auf der Baustelle ist die Höhe eines Gullideckels bekannt. Dieser soll als Höhenreferenz dienen. Die geplante Baugrubensohle soll 1.00 m unterhalb dieses Gullideckels liegen.
    Die gewünschte Baugrubentiefe beträgt 2.00 m (bedeutet Böschungshöhe 2.00 m). Da der Boden eher locker ist, wird ein Böschungswinkel von 45° gewählt. Zusätzlich soll für Dämmung und Arbeitsfreiheit ein Arbeitsraum von 60 cm um die Baugrube hinzugefügt werden.
    
    Damit ergeben sich anhand diesem Beispiel folgende Werte:

     - Höhenreferenz: Gullideckel
     - Sohlenhöhe zur Referenz: −1.00 m
     - Böschungshöhe: 2.00 m
     - Böschungswinkel: 45° 
     - Arbeitsraum: 60 cm rund um die Sohle

Nach Eingabe aller Parameter wird die Baugrube mit OK bestätigt und erstellt.

## Baugrubenübersicht

Nach dem Anlegen erscheint die Baugrube in der Übersichtsliste.
Über den Pfeil ▼ können die Details der Baugrube angezeigt werden. Diese sind über das Zahnrad oben rechts modifizierbar.

In der Baugrubenübersicht kann die Baugrube über das Auge-Symbol im 3D-Modell ein- oder ausgeblendet werden. Mit dem Stift-Symbol lässt sich die Baugrube bearbeiten, sodass alle zuvor definierten Parameter jederzeit angepasst werden können. Über den Mülleimer kann die ausgewählte Baugrube gelöscht werden.

!!! info "Hinweis zum Volumen"
    Das angezeigte Volumen ist das verdichtete Volumen. Das Volumen wird bis zur angegebenen Böschungshöhe berechnet. Metaphorisch gesprochen: die Baugrube wird mit Wasser bis zur oberen Böschungskante eingelassen - das vom Wasser eingenommene Volumen entspricht dem in der App berechneten Volumen. 
    
    Reale Bodenverhältnisse können entsprechend abweichen. Für den Aushub muss ein Auflockerungsfaktor berücksichtigt werden.


<!--
## Titel

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Ansicht Baugrube (2).jpg"/>
</p>

Text in Bearbeitung

!!! info "Titel"
    Text

!!! Warning "Titel"
    Text

<br>

## Titel

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Ansicht Baugrube (3).jpg"/>
</p>

Text in Bearbeitung

!!! info "Titel"
    Text

!!! Warning "Titel"
    Text

<br>

## Titel

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Ansicht Baugrube (4).jpg"/>
</p>

Text in Bearbeitung

!!! info "Titel"
    Text

!!! Warning "Titel"
    Text

-->
<!-- BACKLOG

Unter dem Menüpunkt „Baugrube“ erhalten Sie die Möglichkeit eine Baugrube zu erstellen und zu speichern. Um eine Baugrube zu erstellen, müssen Sie drei Punkte erfassen und speichern sowie die Werte zur Tiefe zur Referenz in cm / m, Tiefe der Baugrube in cm / m, den Böschungswinkel in Grad / % sowie den Arbeitsraum in cm / m angeben. Erstellen Sie die Baugrube und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“. Unter Einstellungen (Zahnradsymbol rechts oben) haben Sie die Möglichkeit die Informationen zu zahlreichen Angaben im Hinblick auf die Anzahl der Punkte, Tiefe zur Referenz, Tiefe der Baugrube, Arbeitsraum und das berechnete Volumen darstellen zu lassen oder bei Bedarf auszublenden. 

BACKLOG -->