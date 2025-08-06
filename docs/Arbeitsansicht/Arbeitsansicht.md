<style>
    setCenter{
        justify-content: center;
    }
</style>

# Arbeitsansicht

## Kopfleiste, Frontalansicht und Seitenansicht
<p align="center" width="100%">
  <img width="100%" src="/images_docs/arbeitsansicht1.jpg"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Batterieanzeige Sensor und Anzeige** - Akkulaufzeit c.a. 16 Stunden, je nach GNSS-Empfang und LED-Helligkeit des Anzeigekreuzes; voll aufgeladen in 2,5h Stunden; per Klick auf das Batterie-Icon wird Ihnen die exakte Akkuprozentanzeige eingeblendet. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Qualität der Orientierung** - Gibt an, ob der Sensor weiß, in welche Himmelsrichtung er gerade schaut. 

  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid grey; display: inline-block; margin-right: 8px;"></span>
      <span>Sensor nicht verbunden</span>
    </span>

  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid red; display: inline-block; margin-right: 8px;"></span>
      <span>schlechte Orientierung</span>
    </span> 

  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid yellow; display: inline-block; margin-right: 8px;"></span>
      <span>halbwegs genau - c.a. 5°</span>
    </span> 

  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid green; display: inline-block; margin-right: 8px;"></span>
      <span>sehr genau - c.a. 1°</span>
    </span>

Der Sensor errechnet die Orientierung mithilfe von Bewegung, d.h. sollte die Orientierung schlecht sein, dann bewegen Sie den Löffel ein wenig vor und zurück bis die Qualität besser wird. Bei schlechtem GNSS-Empfang kann es schwierig sein grüne Orientierung dauerhaft zu erreichen. 

!!! info
      Wenn Sie Ihren Löffel längere Zeit nicht bewegen, kann es sein, dass der Sensor die Orientierung verliert. Er sollte Sie aber schnell wieder finden, wenn Sie die Arbeiten fortsetzen.  

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Empfangsqualität GNSS** - Gibt an, wie gut der GNSS-Empfang des Sensors ist. 

<span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid grey; display: inline-block; margin-right: 8px;"></span>
      <span>Sensor nicht verbunden</span>
</span>

<span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid red; display: inline-block; margin-right: 8px;"></span>
      <span>kein GNSS-Empfang</span>
</span>

<span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid yellow; display: inline-block; margin-right: 8px;"></span>
      <span>schlechter GNSS-Empfang - float</span>
    </span> 
  
  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid green; display: inline-block; margin-right: 8px;"></span>
      <span>guter GNSS-Empfang - fix</span>
    </span>

!!! warning "Wichtig"
    Der Sensor benötigt freie Sicht zum Himmel, um GNSS-Signale empfangen zu können.
    Umliegende Strukturen wie Metall, Bäume, Hauswände oder auch der menschliche Körper können den Empfang stören oder sogar vollständig blockieren.
    Leichte Störungen lassen sich in der Regel kompensieren, jedoch ist ein zuverlässiger Empfang unter bestimmten Bedingungen nicht möglich – etwa in Waldschneisen, bei tieferen Kanalarbeiten, unter Dächern oder bei Arbeiten unter Wasser.

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Verbindungszustand NTRIP-RTK-Korrektur** - RTK-Korrektur ist notwendig, um mit GNSS Zentimetergenauigkeit zu erzielen. Die Farbgebung gibt an, ob Verbindung zu einem Korrekturdatendienstleister besteht. 

  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid grey; display: inline-block; margin-right: 8px;"></span>
      <span>nicht verbunden</span>
  </span>

  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid red; display: inline-block; margin-right: 8px;"></span>
      <span>Verbindung fehlgeschlagen</span>
  </span> 

  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid blue; display: inline-block; margin-right: 8px;"></span>
      <span>Verbindung wird aufgebaut</span>
  </span> 

  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid green; display: inline-block; margin-right: 8px;"></span>
      <span>verbunden</span>
  </span>

!!! warning "Wichtig"
    Sie benötigen Internet auf Ihrem Tablet, um sich zu verbinden. Entweder Sie nutzen eine SIM-Karte mit mobilem Datenvolumen oder Sie verbinden sich mit einem Wlan (z.B. Hotspot). 

Genauere Informationen finden Sie unter [NTRIP](https://docs.excav.de/NTRIP/NTRIP/).

**<span style="color: red; font-weight: bold;">5: &nbsp;</span> Höhenabweichung zur Sollhöhe** - Zeigt an, wie weit die Löffelschneide – genauer gesagt die ausgewählte Löffelecke (siehe Punkt 7) – von der Sollhöhe entfernt ist, also von der Oberfläche des aktiven Geländes (z. B. einer Fläche oder Baugrube). 

Beispiel: In Abb. 1 liegt die Löffelschneide 50 cm oberhalb der Sollhöhe der aktiven horizontalen Fläche (vgl. Punkt 8) und ist dementsprechend nach unten zu korrigieren. 

**<span style="color: red; font-weight: bold;">6: &nbsp;</span> Neigungsabweichung zur Sollneigung** - Zeigt an, ob die Löffelschneide parallel zur Sollneigung, also zur Neigung des aktiven Geländes, ausgerichtet ist. 

Beispiel: In Abbildung 1 ist die Löffelschneide noch nicht vollständig parallel zur Horizontalen und muss leicht nach rechts korrigiert werden. 

**<span style="color: red; font-weight: bold;">7: &nbsp;</span> Aktive Werkzeugecke** - Die aktuell aktive Werkzeugecke (von der Fahrerkabine aus: linke Ecke, Mitte, rechte Ecke) wird mit einem roten Quadrat markiert und hat zwei entscheidende Funktionalitäten:

1. **Höhenabweichung zur Sollhöhe** - Die Höhenabweichung zur Sollhöhe wird immer von der aktiven Werkzeugecke berechnet. Dies ist vor allem zu beachten, wenn Sie z.B. eine Böschung rausziehen!

2. **Punkte erfassen mit Werkzeugecke** - Wenn Sie mit dem Löffel [Punkte auf der Baustelle erfassen](https://docs.excav.de/Punkte/Punkte/) möchten, dann wird immer die aktuell aktive Werkzeugecke zur Punkterfassung herangezogen. Wenn die x- und y-Koordinate des Punktes von Relevanz ist, dann empfehlen wir die dem Sensor nächstgelegene Löffelecke zu wählen (Bsp.: rechte Ecke, wenn Sensor auf der rechten Seite des Löffels angebracht ist), da dann kleine Kalibrierungsfehler am geringsten ins Gewicht fallen. Wenn Sie nur eine Höhenreferenz benötigen, dann empfehlen wir die Mitte als Werkzeugecke. Denn bei älteren Löffeln sind die Schneiden an den Seiten oft ein wenig abgenutzt. 

Sie können die Werkzeugecke wechseln, indem Sie auf das Werkzeug in der Frontalansicht tippen.

**<span style="color: red; font-weight: bold;">8: &nbsp;</span> Sollhöhe - frontaler Schnitt zum Gelände** - Frontaler Schnitt des aktives Geländes; die rote Linie visualisiert die Sollhöhe (genauere Ausführung folgt..)

**<span style="color: red; font-weight: bold;">9: &nbsp;</span> Sollhöhe - seitlicher Schnitt zum Gelände** - Seitlicher Schnitt des aktives Geländes; die grüne Linie visualisiert die Sollhöhe (genauere Ausführung folgt..)


## Hauptarbeitsbereich
<p align="center" width="100%">
  <img width="100%" src="/images_docs/arbeitsansicht2.jpg"/>
</p> 

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Absolute Höhe** - Absolute Höhe der aktiven Werkzeugecke im DHHN2016 Höhenbezugssystem. (genauere Ausführung folgt..)

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Himmelsrichtung** - Ohne Fixierung wird die momentane Himmelsrichtung der Blickrichtung des Werkzeugs dynamisch angezeigt. Durch einen Klick kann die Ausrichtung auf Norden fixiert werden – ähnlich wie bei Google Maps.

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Perspektive | 2D oder 3D Ansicht** - Wechsel zwischen 2D-Vogelperspektive und 3D-Perspektive der Baustelle

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Werkzeug wechseln** - Schnelltaste zum [Werkzeug wechseln]() ohne die Arbeitsansicht verlassen zu müssen

**<span style="color: red; font-weight: bold;">5: &nbsp;</span> Punkt erfassen** - Schnelltaste zum [Punkte erfassen]() ohne die Arbeitsansicht verlassen zu müssen

**<span style="color: red; font-weight: bold;">6: &nbsp;</span> Höhenreferenz wählen** - Hier können Sie Gelände für die Berechnung der Höhenreferenz aktivieren und deaktivieren. (Genauere Ausführung folgt..)

**<span style="color: red; font-weight: bold;">7: &nbsp;</span> [Designmenü]()** - Öffnet das Designmenü; dort finden Sie alle Funktionen rund um das Aufmaß und Nachbilden Ihrer Baustelle, wie z.B. [Erstellen von Flächen]() oder das [Einspielen von DGMs]().

<!--
Der Arbeitsbereich setzt sich aus mehreren Ansichten zusammen, die Aufschluss über die exakte Lage des Sensors und des Werkzeugs im Raum, den Akkuladestand der Systemeinheiten, die Konnektivität sowie zu wichtigen weiterführenden Menüpunkten bietet.

Der Akkustand der LED-Anzeige und des Sensors werden dauerhaft angezeigt. Achten Sie darauf, dass die Akkustände der einzelnen Geräte nicht unter 10 % fallen, da sich dies bei Sensor und ggf. der optionalen Basisstation negativ auf die Performanz und somit Genauigkeit auswirken kann. Eine volle Akkuladung reicht für ca. 16 Stunden Einsatzdauer. Die Ladezeit der Geräte beläuft sich in etwa auf 2,5 Stunden.


## Frontalansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht linksoben neu.jpg"/>
</p>

Die linke obere Ansicht in der Arbeitsansicht unterhalb der Kopfleiste visualisiert die aktiv genutzte Baggerschaufel oder das Werkzeug in einer frontalen 3D-Ansicht (aus der Kabine):

- Die Baggerschaufel oder das Werkzeug werden entsprechend der Höhen- und Seitenverhältnisse dargestellt.

- Das Quadrat zeigt die ausgewählte Werkzeugecke an. Von diesem Punkt aus wird der Abstand zur Fläche / zum Geländemodell (hier als Linie dargestellt) berechnet.

- Der rote Strich stellt die Höhe der erstellten Fläche im Geländemodell dar.

## Seitenansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht linksoben neu.jpg"/>
</p>

Die rechte obere Ansicht in der Arbeitsansicht unterhalb der Kopfleiste visualisiert die Baggerschaufel oder das Werkzeug in einer 3D-Ansicht von der Seite:

- Die Baggerschaufel oder das Werkzeug werden entsprechend der Höhen- und Seitenverhältnisse dargestellt.

- Der grüne Strich stellt die Höhe der erstellten Fläche im Geländemodell dar.

## Hauptarbeitsbereich

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Hauptbereich neu.jpg"/>
</p>

Der primäre Arbeitsplatz informiert den Nutzer über die exakte Position der Baggerschaufel oder des Werkzeugs in Bezug zum Referenzpunkt (REF) und den von Ihnen erfassten Punkten auf der Baustelle. Die aktuelle Höhe nach DHHN (Deutsches Höhenhauptnetz) der ausgewählten Ecke der Baggerschaufel oder des Werkzeugs wird links oben in Meter angezeigt.

Die Höhe des Referenzpunktes wird durch ein festes Gitternetz dargestellt, wobei jedes Quadrat eine 1 x 1 Meter Fläche beschreibt. Sie können der Bewegung der Baggerschaufel oder des Werkzeugs im Raum frei folgen und jederzeit in die primäre Ansicht tiefer rein- sowie herauszoomen. Die Baggerschaufel oder das Werkzeug werden entsprechend der eingegebenen Schaufel- oder Werkzeugbreite dreidimensional in Dunkelgrau dargestellt. Die ausgewählte Werkzeugecke wird dreidimensional durch einen transparenten Würfel dargestellt, analog zum roten Quadrat an der Werkzeugecke in den Nebenansichten. 

Sie können eigene Baupläne sowie digitale Geländemodelle in der Arbeitsansicht hochladen. Mehr Informationen hierzu finden Sie nachfolgend in der App unter [Bauplan](../Bauplan/Bauplan.md) und [Gelände](../Gelände/Gelände.md).

## Ansicht der Höhen- und Neigungsabweichung

Die Höhen- und Neigungsabweichung erscheint in der oben links in der Arbeitsansicht angezeigt, wenn eine Fläche oder in Geländemodell aktiv ist. Die Farbgebung entspricht analog derselben der LED-Lichtquellen des LED-Anzeigekreuzes.

## Ansicht Anpassung der primären Arbeitsansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Nord neu.jpg"/>
</p>

Über die auf der rechten Seite der Ansicht befindlichen mittleren Buttons können Sie die Koordinate Absolut-Nord aktivieren oder deaktivieren. Durch Absolut-Nord können Sie die Ansicht des Gitternetzes fixieren oder am Werkzeug ausrichten.

Sie können die primäre Arbeitsansicht wahlweise von 2D auf 3D wechseln und umgekehrt. PDF-Baupläne werden nur und der 2D-Ansicht angezeigt. Für DGMs bietet sich die 3D-Ansicht an. 

## Ansicht Buttons der primären Arbeitsansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Menü 1 neu.jpg"/>
</p>

Über mehrere Buttons auf der primären Arbeitsansicht können Sie die laufenden Tätigkeiten im Arbeitsplatz schnell und in wenigen Schritten anpassen.

Über den Button mit dem **Werkzeug-Symbol** öffnet sich eine Auswahl der aktuell verfügbaren Werkzeuge. Dadurch können Sie schnell nach Bedarf das Werkzeug ändern sowie zum standardmäßig hinterlegten Messstab wechseln.

Über den Button mit dem **Geolokalisations-Symbol** öffnet sich eine Auswahl zur Erfassung von Punkten. Hier können Sie über die Funktion „GNSS-Punkt“ einen neuen Punkt von der aktuellen Position aus erfasst oder über die Funktion „Manueller Punkt“ einen Punkt durch die Eingabe seiner absoluten Koordinaten einlesen. Weiter Informationen erhalten Sie unter [Punkte](../Punkte/Punkte.md)

Über den nachfolgenden Button mit dem **Pfeil-Symbol** können Sie einfache Flächen, Baugruben und Geländemodelle aktiv schalten. Dadurch wird die Höhen- und Neigungsabweichung vom Werkzeug zur aktiven Geländestruktur sowohl in der Arbeitsansicht als auch auf dem LED-Anzeigekreuz angezeigt.

Über den Button mit dem **Tintenfüller-Symbol** öffnet sich das Arbeitsmenü mit einer Auswahl von Funktionen für die Organisation der Arbeit auf der Baustelle. Die Funktionen werden im Abschnitt „Arbeitsmenü“ näher erläutert. -->