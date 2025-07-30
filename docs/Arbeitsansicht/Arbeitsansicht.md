<style>
    setCenter{
        justify-content: center;
    }
</style>

# Arbeitsansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht.jpg"/>
</p>

Nach erfolgreicher Einrichtung des Systems gelangen Sie direkt zur primären Arbeitsansicht, welche die wichtigsten Informationen über die präzise Position der Baggerschaufel oder des Werkzeugs im Raum sowie in Bezug zur Arbeitsfläche bietet und Sie bei Ihren Arbeiten visuell unterstützt. Der Sensor bzw. das Werkzeug werden in der App dreidimensional im Raum dargestellt.
Der Arbeitsbereich setzt sich aus mehreren Ansichten zusammen, die Aufschluss über die exakte Lage des Sensors und des Werkzeugs im Raum, den Akkuladestand der Systemeinheiten, die Konnektivität sowie zu wichtigen weiterführenden Menüpunkten bietet.

Über die Buttons in der primären Arbeitsansicht gelangen Sie zu den Dropdown-Menüs, welche wichtige Funktionen und Einstellungsmöglichkeiten für den Umgang mit dem System beinhalten.

[//]: # (todo: Ab hier die Bilder so anpassen, dass entweder nur die angesprochenen Elemente zu sehen sind oder die Elemente visuell hervorgehoben werden. Am Besten vorher einen Löffel kalibrieren, sodass dieser in der Arbeitsansicht zu sehen ist.)

## Topbar

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Kopfleiste.jpg"/>
</p>

Die Topbar stellt folgende Werte kontinuierlich dar:

- den Ladestand des LED-Anzeigekreuz 
- den Ladestand des Sensors 
- die Qualität der Orientierung:

    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid red; display: inline-block; margin-right: 8px;"></span>
      <span>nicht vorhanden</span>
    </span> | 
    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid yellow; display: inline-block; margin-right: 8px;"></span>
      <span>ungenau</span>
    </span> | 
    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid green; display: inline-block; margin-right: 8px;"></span>
      <span>vorhanden</span>
    </span>

- die GNSS-Qualität des Sensors:

    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid red; display: inline-block; margin-right: 8px;"></span>
      <span>kein GNSS-Empfang</span>
    </span> | 
    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid yellow; display: inline-block; margin-right: 8px;"></span>
      <span>schlechter GNSS-Empfang</span>
    </span> | 
    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid green; display: inline-block; margin-right: 8px;"></span>
      <span>guter GNSS-Empfang</span>
    </span>

- das Vorhandensein von NTRIP-Korrekturdaten:

    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid red; display: inline-block; margin-right: 8px;"></span>
      <span>Verbindung abgebrochen</span>
    </span> | 
    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid blue; display: inline-block; margin-right: 8px;"></span>
      <span>verbinde mit Korrekturdaten-Dienst</span>
    </span> | 
    <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid green; display: inline-block; margin-right: 8px;"></span>
      <span>verbunden</span>
    </span>


Durch das Drücken auf die Symbol-Icons erhalten Sie nähere Informationen zu den angezeigten Werten.

Der Akkustand der LED-Anzeige und des Sensors werden dauerhaft angezeigt. Achten Sie darauf, dass die Akkustände der einzelnen Geräte nicht unter 10% fallen, da sich dies bei Sensor und ggf. der optionalen Basisstation negativ auf die Performanz und somit Genauigkeit auswirken kann. Eine volle Akkuladung reicht für ca. 16 Stunden Einsatzdauer. Die Ladezeit der Geräte beläuft sich in etwa auf 2,5 Stunden.


## Frontalansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht linksoben.jpg"/>
</p>

Die linke obere Ansicht in der Arbeitsansicht unterhalb der Kopfleiste visualisiert die aktiv genutzte Baggerschaufel oder das Werkzeug in einer frontalen 3D-Ansicht (aus der Kabine):

- Die Baggerschaufel oder das Werkzeug werden entsprechend der Höhen- und Seitenverhältnisse dargestellt.

- Das Quadrat zeigt die ausgewählte Werkzeugecke an. Von diesem Punkt aus wird der Abstand zur Fläche / zum Geländemodell (hier als Linie dargestellt) berechnet.

- Der rote Strich stellt die Höhe der erstellten Fläche im Geländemodell dar.

## Seitenansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht rechtsoben.jpg"/>
</p>

Die rechte obere Ansicht in der Arbeitsansicht unterhalb der Kopfleiste visualisiert die Baggerschaufel oder das Werkzeug in einer 3D-Ansicht von der Seite:

- Die Baggerschaufel oder das Werkzeug werden entsprechend der Höhen- und Seitenverhältnisse dargestellt.

- Der grüne Strich stellt die Höhe der erstellten Fläche im Geländemodell dar.

## Hauptarbeitsbereich

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Hauptbereich.jpg"/>
</p>

Der primäre Arbeitsplatz informiert den Nutzer über die exakte Position der Baggerschaufel oder des Werkzeugs in Bezug zum Referenzpunkt (REF) und den von Ihnen erfassten Punkten auf der Baustelle. Die aktuelle Höhe nach DHHN (Deutsches Höhenhauptnetz) der ausgewählten Ecke der Baggerschaufel oder des Werkzeugs wird links oben in Meter angezeigt.

Die Höhe des Referenzpunktes wird durch ein festes Gitternetz dargestellt, wobei jedes Quadrat eine 1x1 Meter Fläche beschreibt. Sie können der Bewegung der Baggerschaufel oder des Werkzeugs im Raum frei folgen und jederzeit in die primäre Ansicht tiefer rein- sowie rauszoomen. Die Baggerschaufel oder das Werkzeug werden entsprechend der eingegebenen Schaufel- oder Werkzeugbreite dreidimensional in Dunkelgrau dargestellt. Die ausgewählte Werkzeugecke wird dreidimensional durch einen transparenten Würfel dargestellt, analog zum roten Quadrat an der Werkzeugecke in den Nebenansichten. 

Sie können eigene Baupläne sowie digitale Geländemodelle in der Arbeitsansicht hochladen. Mehr Informationen hierzu finden Sie nachfolgend in der App unter [Bauplan](../Bauplan/Bauplan.md) und [Gelände](../Gelände/Gelände.md).

[//]: # (todo: Der folgende Abschnitt muss entfernt werden. Existiert nicht mehr. Dagegen wird jetzt die Höhen- und Neigungsabweichung in der Bildschirmecke oben links angezeigt, wenn eine Fläche / Geländemodell aktiv gesetzt wird. Dies muss entsprechend ergänzt werden.)
## Ansicht der Höhen- und Neigungsabweichung

Die Höhen- und Neigungsabweichung erscheint in der oben links in der Arbeitsansicht angezeigt, wenn eine Fläche oder in Geländemodell aktiv ist. Die Farbgebung entspricht analog derselben der LED-Lichtquellen des LED-Anzeigekreuz. 

## Ansicht Anpassung der primären Arbeitsansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Nord.jpg"/>
</p>

Über die auf der rechten Seite der Ansicht befindlichen mittleren Buttons können Sie die Koordinate Absolut-Nord aktivieren oder deaktivieren. Durch Absolut-Nord können Sie die Ansicht des Gitternetzes fixieren oder am Werkzeug ausrichten.

Sie können die primäre Arbeitsansicht wahlweise von 2D auf 3D wechseln und umgekehrt. PDF-Baupläne werden nur und der 2D-Ansicht angezeigt. Für DGMs bietet sich die 3D-Ansicht an. 

## Ansicht Buttons der primären Arbeitsansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Menü 1.jpg"/>
</p>

Über mehrere Buttons auf der primären Arbeitsansicht können Sie die laufenden Tätigkeiten im Arbeitsplatz schnell und in wenigen Schritten anpassen.

Über den Button mit dem **Werkzeug-Symbol** öffnet sich eine Auswahl der aktuell verfügbaren Werkzeuge. Dadurch können Sie schnell nach Bedarf das Werkzeug ändern sowie zum standardmäßig hinterlegten Messstab wechseln.

Über den Button mit dem **Geolokalisations-Symbol** öffnet sich eine Auswahl zur Erfassung von Punkten. Hier können Sie über die Funktion „GNSS-Punkt“ einen neuen Punkt von der aktuellen Position aus erfasst oder über die Funktion „Manueller Punkt“ einen Punkt durch die Eingabe seiner absoluten Koordinaten einlesen. Weiter Informationen erhalten Sie unter [Punkte](../Punkte/Punkte.md)

Über den nachfolgenden Button mit dem **Pfeil-Symbol** können Sie einfache Flächen, Baugruben und Geländemodelle aktiv schalten. Dadurch wird die Höhen- und Neigungsabweichung vom Werkzeug zur aktiven Geländestruktur sowohl in der Arbeitsansicht als auch auf dem LED-Anzeigekreuz angezeigt.

Über den Button mit dem **Tintenfüller-Symbol** öffnet sich das Arbeitsmenü mit einer Auswahl von Funktionen für die Organisation der Arbeit auf der Baustelle. Die Funktionen werden im Abschnitt „Arbeitsmenü“ näher erläutert.
