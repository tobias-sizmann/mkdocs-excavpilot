<style>
    setCenter{
        justify-content: center;
    }
</style>

# Werkzeuge
<a id="werkzeuge1"></a>
<figure>
  <img width="100%" src="/images_docs/werkzeuge1.jpg"/>
  <figcaption>Abb. 1: Menü => Werkzeuge</figcaption>
</figure>


Es ist vorab zu erwähnen, dass beim excav PILOT anders als bei herkömmlichen Assistenzsystemen bzw. Baggersteuerungen das GNSS-Modul direkt am Werkzeug montiert wird. Demnach wissen wir nichts über die eigentliche Baumaschine (weder Stiel noch Rumpf) und erfassen nur das Werkzeug selbst 3D im Raum.

Vorteil: Sie können ohne Probleme innerhalb von Minuten zwischen Baumaschinen wechseln und auch Anbau-Features wie z.B. **Tiltrotator** sind kein Problem. 

Sie müssen entsprechend dem Sensor mitteilen, wie das Werkzeug genau aussieht, auf dem er sich aktuell befindet. Je genauer er das weiß, desto bessere Ergebnisse erhalten Sie. 

## Unterstützte Werkzeuge 

Aktuell werden folgende Werkzeuge für Baumaschinen im excav PILOT unterstützt:  

1. **Rover-Stab** als standardmäßig hinterlegtes Werkzeug für das Aufmessen der Baustelle vor Beginn der Erdarbeiten oder um Punkte möglichst präzise zu erfassen

2. **Löffel** - hier ist darauf zu achten, dass eine Mindestbreite notwendig ist, damit der GNSS-Sensor eine geeignete Stelle auf dem Löffel findet. Löffel mit einer Breite größer 60 cm sind in aller Regel unproblematisch. Bei schmalen Grabenraumlöffeln und/ oder Löffeln mit verbauter Hydraulik muss ggf. ein wenig getrickst werden. 

3. **Schaufel von Radlader oder Kompaktlader** - beim Kompaktlader empfehlen wir die Einmessung der Schaufel mittels Antastverfahren

4. **Schild** - sowohl kleine Drei-Wege-Schilder und Sechs-Wege-Schilder am Bagger als auch Planierschilder von Raupen. Kalibrierung nur mittels Antastverfahren empfohlen, da es bei Schildern schwierig ist die für das Einmessverfahren benötigte Nullneigung des Sensors zu ermitteln.

Mit etwas Erfahrung können Sie auch speziellere Werkzeuge einkalibrieren wie z.B. **Planierbalken** oder **Ramme**. Diese werden allerdings aktuell noch nicht als solche in der App unterstützt und müssen als Löffel angelegt werden. 

## Zwei Möglichkeiten für die Kalibrierung

1. [Einmessverfahren](https://docs.excav.de/Kalibrierung/Kalibrierung/) - Sie bestimmen z.B. mithilfe eines Zollstocks oder per Lasermessung die Breite, Höhe und Einrückung des Löffels und die Nullneigung des Sensors. 

2. [Antastverfahren](https://docs.excav.de/Kalibrierung/Kalibrierung/) - Einmessung des Werkzeugs per GNSS. Sie erfassen und markieren einen Basispunkt auf der Baustelle - z.B. mit Sprühfarbe oder Sie wählen einen markanten Stein und erfassen diesen Punkt anschließend auch mit beiden Werkzeugecken. 

Detaillierte Ausführungen zu den beiden Verfahren finden Sie auf den jeweiligen Unterseiten. 


## Rover-Stab kalibrieren

Der Rover-Stab ist standardmäßig als Werkzeug in der App hinterlegt. 

!!! warning "Wichtig!"
    Bitte verwenden Sie alle vier Komponenten des Rover-Stabs, ansonsten stimmt die Vorabkalibrierung nicht!

Falls Sie Ihren eigenen Rover-Stab mit abweichender Länge kalibrieren möchten, dann muss die Länge von der Stab-Spitze parallel laufend bis zur Gehäuseunterkante des Sensors gemessen werden.

## Werkzeug wechseln und Werkzeugecke wechseln

<figure>
  <img width="100%" src="/images_docs/werkzeuge2.jpg"/>
  <figcaption>Abb. 2: Werkzeug wechseln (<span style="color: red; font-weight: bold;">1</span>) und Werkzeugecke wählen (<span style="color: red; font-weight: bold;">2</span>)</figcaption>
</figure>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Werkzeug wechseln** - Achten Sie darauf, dass das in der App aktive Werkzeug auch immer mit dem tatsächlich im Einsatz befindlichen Werkzeug übereinstimmt. Über den in obiger Abbildung (Abb. 2) mit <span style="color: red; font-weight: bold;">1</span> markierten Button können Sie das Werkzeug mit nur einem Klick wechseln ohne die Arbeitsansicht verlassen zu müssen (sofern bereits kalibriert). Alternativ können Sie auch immer über den Reiter "Werkzeuge" im Menü Ihr Werkzeug auswählen. (siehe [Abbildung 1](#werkzeuge1))

Hierzu ist anzumerken, dass wir das Abspeichern und erneute Laden von Werkzeugen nur empfehlen, wenn Sie mit [Metallrahmen](https://docs.excav.de/Metallrahmen/Metallrahmen/) auf Ihren Löffeln arbeiten, da der Sensor beim Laden des Werkzeugs immer an genau die selbe Position auf dem Löffel gesetzt werden muss. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Werkzeugecke wechseln** - Die aktive Werkzeugecke (von der Fahrerkabine aus: linke Ecke, Mitte, rechte Ecke) hat zwei entscheidende Funktionalitäten: 

1. **Höhenabweichung zur Sollhöhe** - Die Höhenabweichung zur Sollhöhe wird immer von der aktiven Werkzeugecke berechnet. Dies ist vor allem zu beachten, wenn Sie z.B eine Böschung rausziehen!

2. **Punkte erfassen mit Werkzeugecke** - Wenn Sie mit dem Löffel [Punkte auf der Baustelle erfassen](https://docs.excav.de/Punkte/Punkte/) möchten, dann wird immer die aktuell aktive Werkzeugecke zur Punkterfassung herangezogen. Wenn die x- und y-Koordinate des Punktes von Relevanz ist, dann empfehlen wir die dem Sensor nächstgelegene Löffelecke zu wählen (Bsp.: rechte Ecke, wenn Sensor auf der rechten Seite des Löffels angebracht ist), da dann kleine Kalibrierungsfehler am geringsten ins Gewicht fallen. Wenn Sie nur eine Höhenreferenz benötigen, dann empfehlen wir die Mitte als Werkzeugecke. Denn bei älteren Löffeln sind die Schneiden an den Seiten oft ein wenig abgenutzt. 

Sie können die Werkzeugecke wechseln, indem Sie auf das Werkzeug in der Frontalansicht tippen. Siehe <span style="color: red; font-weight: bold;">2</span> in Abbildung 2. 

