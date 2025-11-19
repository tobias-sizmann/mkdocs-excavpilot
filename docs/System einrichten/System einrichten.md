<style>
    setCenter{
        justify-content: center;
    }
</style>

# System einrichten

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 0.png"/>
</p>

Lesen Sie sich bitte die folgenden Unterpunkte für die Einrichtung des Systems sorgfältig durch und starten Sie anschließend die excav PILOT App auf dem mitgelieferten Tablet. Vergewissern Sie sich bitte, dass die einzelnen Geräte gemäß dem späteren Abschnitt „System aufbauen“ mit korrekter Ausrichtung am Maschinenarm und dem jeweiligen Werkzeug angebracht wurden.

Es gibt eine ausführliche [Videoanleitung auf YouTube](https://www.youtube.com/watch?v=0_yEPTznHgQ){:target="\_blank"}, in der ein komplettes erstmaliges Setup im Detail durchgeführt und erklärt wird. Wir raten Erstnutzern, bei der Systemeinrichtung des excav PILOT auf die Videoanleitung zurückzugreifen und den Leitfaden nur unterstützend zu verstehen.


## excav PILOT App öffnen und starten

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 1.png"/>
</p>

Im ersten Schritt muss das Tablet mit der excav PILOT App aufgesetzt werden. Sobald Sie das System erstmals einrichten möchten, müssen Sie die ersten wichtigen Schritte in der App genau befolgen. Bevor Sie einen neuen Arbeitsplatz anlegen oder laden können, müssen die Geräte und NTRIP im Startmenü oben links eingerichtet werden. 

Beim ersten Systemstart werden zwei Hinweise auf dem Tablet angezeigt:

!!! Warning "Sensor nicht verbunden"
    Sie können über das Startmenü unter Geräte den GNSS-Sensor mit dem dazugehörigen Tablet des excav PILOT verknüpfen. Schalten Sie dafür den GNSS-Sensor an und suchen Sie anschließend nach der Sensoreinheit.

Weitere Informationen hierzu finden Sie unter [Geräte](../Geräte/Geräte.md) im Startmenü.

!!! Warning "Kein Arbeitsplatz aktiv"
    Um alle Ihre Fortschritte speichern zu können, benötigen Sie einen aktiven Arbeitsplatz. Legen Sie sich entweder einen neuen Arbeitsplatz an, oder laden Sie einen bereits vorhandenen Arbeitsplatz hoch.

Weitere Informationen hierzu finden Sie unter [Arbeitsplatz](../Arbeitsplatz/Arbeitsplatz.md) im Startmenü.

Das Tablet wird mit der excav PILOT App einsatzbereit mitgeliefert. Die Geräte wurden vorab mit der App des Tablets testweise gekoppelt. Um zu Starten und die Geräte zu koppeln benötigen Sie auf dem Tablet eine aktive Bluetooth-Verbindung sowie eine akive Internetverbindung über WLAN (mobil verfügbare Daten), da die Kommunikation beider Geräte zum Tablet über Bluetooth Low Energy erfolgt. Es können standardmäßig zwei Geräte, den für die Arbeit unabdingbare GNSS-Sensor und das als Hilfestellung dienende LED-Anzeigekreuz verbunden werden. 

Bevor Sie mit anderen Schritten fortfahren können, müssen Sie die Geräte zunächst einschalten. 

## Geräte anschalten und verbinden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 2.png"/>
</p>

Betätigen Sie von beiden Geräten (GNSS-Sensor und LED-Anzeigekreuz) den An/Aus-Button auf der Unterseite der Geräte bis dieser grün aufleuchtet. Die Geräte können selbstverständlich nur erkannt und per Bluetooth mit dem Tablet gekoppelt werden, wenn diese auch angeschaltet sind und über ausreichend Akkuleistung (am besten über 20%) verfügen. Beginnen Sie zunächst mit dem GNSS-Sensor, aktivieren Sie ihn und lassen Sie die App nach der Sensoreinheit scannen. Im Normalfall sollte der GNSS-Sensor sofort erkannt werden und sich problemlos ankoppeln lassen.


## GNSS-Sensor auswählen und verbinden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 3.png"/>
</p>

Es wird die Sensoreinheit zuerst angezeigt, die dem System bereits bekannt war bzw. zuletzt verbunden war. Im Normalfall wurde nur in Sensor zuvor verbunden und wird folglich wieder vorgeschlagen. Betätigen Sie "Scannen" und wählen Sie den angezeigten Sensor aus. 

Die Verbindung kann jederzeit manuell wieder aufgehoben werden. Sollte die Verbindung eines oder mehrerer Geräte fehlschlagen, prüfen Sie bitte zuerst den Akkustand der entsprechenden Geräte (idealerweise üpber 20%) und ob sie eingeschaltet sind. Stellen Sie sicher, dass der Sensor nicht bereits mit einem anderen Tablet gekoppelt ist und für ein anderes System eingesetzt wird. Platzieren Sie den Sensor möglichst in Nähe zum Tablet und schalten Sie den Sensor ggf. mehrfach aus und wieder an bis der Verbindungsaufbau gelingt.


## LED-Anzeigekreuz auswählen und verbinden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 4.png"/>
</p>

Das Verfahren für das LED-Anzeigekreuz it das gleiche: Betätigen Sie den orangenen Button "Scannen" und wählen Sie das LED-Anzeigekreuz aus. Stellen Sie sicher, dass dieser nicht bereits mit einem anderen Tablet gekoppelt ist und für ein anderes System eingesetzt wird. Falls es zu Schwierigkeiten beim Verbindungsaufbau kommen sollte prüfen Sie, ob der MAC-Wert übereinstimmt. Platzieren Sie das LED-Anzeigekreuz möglichst in Nähe zum Tablet und schalten Sie den Sensor ggf. mehrfach aus und wieder an bis der Verbindungsaufbau gelingt.


## Alle Geräte einsatzbereit

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 5.png"/>
</p>

Ist der Verbindungsaufbau mit beiden Geräten gelungen, erscheinen diese mit dem MAC-Wert (auf der Rückseite der einzelnen Geräte ersichtlich) im Gerätefenster. Die Angabe des Buttons "Trennen"bedeutet, dass beide Geräte (darunter das optionale LED-Anzeigekreuz) erfolgreich verbunden worden sind und ggf. wieder getrennt werden können. 


## NTRIP für Korrekturdaten einrichten

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 6.png"/>
</p>

Das excav PILOT System erlaubt den Zugriff auf externe RTK-Korrekturdaten über eine NTRIP-Verbindung (engl. Networked Transport of RTK Internet Protocol). Der GNSS-Sensor erhält somit in Echtzeit Korrekturdaten für präzise Erdarbeiten auf der Baustelle im Zentimeterbereich. Die NTRIP-Funktion wird benötigt, um externe RTK-Korrekturdaten von einem Anbieter für GNSS-Dienste zu beziehen und auf eine Referenzstationen zugreifen kann, ohne dass man selbst eine eigene Basisstation mitbringen, aufbauen und korrekt betreiben muss.

Durch die Verbindung über NTRIP wird das 3D-GNSS-Assistenzsystem excav PILOT mobil und flexibel einsetzbar, ohne dass jede Maschine eigene Vermessung oder eine Basisstation benötigt – ein großer Vorteil gegenüber konventionellen Assistenzsystemen im Bau. Um NTRIP nutzen zu können, müssen Sie zuerst eine NTRIP-Verbindung auf der App einrichten. Fahren Sie nach der Kopplung der Geräte im Startmenü unter NTRIP fort, um dort die erste Verbindung einzurichten.

## NTRIP-Verbindung und Position des GNSS-Sensors

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 8.png"/>
</p>

Für die Einrichung der NTRIP-Verbindung benötigen Sie eine Reihe von Angaben und Daten, die Sie für diesen Zweck über excav als Dienstleister erhalten.  

Eine wichtige Erfordernis ist ein Internetzugang. Damit das Tablet die externen Korrekturdaten über NTRIP abrufen kann, muss eine Datenverbindung vorhanden sein (z. B. Mobilfunk oder SIM-Karte). excav bietet hierzu einen SIM-Karten-Service, um eine Datenverbindung zu ermöglichen. 


Klicken Sie auf den Button "+ Hinzufügen", um erstmals eine NTRIP-Verbindung anlegen zu können. Füllen Sie die Eingabefelder mit den verfügbaren Daten aus und vergeben Sie einen geeigneten Namen, insbesondere wenn später mehrere NTRIP-Verbindungen eingerichtet werden. Tragen Sie alle erforderlichen Zugangsdaten des NTRIP-Dienstes ein: Hostname des NTRIP‐Server / Portnummer / Mountpoint / Benutzername und Passwort (falls erforderlich). Wählen Sie den passenden Mountpoint bzw. Standort‐Korrekturdienst. Prüfen Sie die Verbindung: Es sollte angezeigt werden, dass der NTRIP-Client verbunden ist und Korrekturdaten empfängt. 

!!! info "Tipps für guten NTRIP-Empfang"
    Achten Sie auf guten Mobilfunk‐Empfang auf der Baustelle. Wenn die Verbindung zu langsam oder instabil ist, kann der NTRIP-Dienst nicht zuverlässig arbeiten. Wählen Sie den Mountpoint möglichst nahe an der Baustelle, damit die Korrekturdaten eine geringere Latenz aufweisen und bessere Genauigkeit haben.

!!! info "Zweitsensor als optionale Basisstation"
    Falls keine Mobilverbindung vorhanden ist, kann eine lokale Basisstation oder Hotspot nötig sein. Zukünftig kann ein optionaler Zweitsensor als stationäre Basisstation für eigene Korrekturdaten eingesetzt werden.

!!! Warning "NTRIP zunächst sorgfältig testen"
    Nach der Einrichtung von NTRIP sollte ein Testlauf erfolgen: Sensor montieren, Werkzeug kalibrieren, Korrekturdaten aktivieren und prüfen, ob die Werkzeuge sich präzise entsprechend dem digitalen Modell in der App verhalten.

Geben Sie zuletzt die exakten Positionsdaten (engl. Latitude / Longitude) des eingeschalteten GNSS-Sensors ein. Die erreichbare Lagegenauigkeit wird je nach Korrekturdatendienstleister mit ca. 1 - 3 cm angegeben. Der bekannteste Dienstleister auf dem deutschen Markt ist SAPOS.


## Geräte an der Baumaschine anbringen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 10.png"/>
</p>

Text in Bearbeitung

Hier mehr erfahren im nächsten Schritt der Anleitung: [System aufbauen](https://docs.excav.de/System aufbauen/System aufbauen/)
