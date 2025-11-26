<style>
    setCenter{
        justify-content: center;
    }
</style>

# System einrichten

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 0.png"/>
</p>

Lesen Sie sich bitte die folgenden Unterpunkte für die Einrichtung des Systems sorgfältig durch und starten Sie anschließend die excav PILOT App auf dem mitgelieferten Tablet. Vergewissern Sie sich, dass die einzelnen Geräte gemäß dem späteren Abschnitt „System aufbauen“ mit korrekter Ausrichtung am Maschinenarm und dem jeweiligen Werkzeug angebracht wurden.

Es gibt eine ausführliche [Videoanleitung auf YouTube](https://www.youtube.com/watch?v=0_yEPTznHgQ){:target="\_blank"}, in der ein komplettes erstmaliges Setup im Detail durchgeführt und erklärt wird. Wir raten Erstnutzern, bei der Systemeinrichtung des excav PILOT auf die Videoanleitung zurückzugreifen und den Leitfaden nur unterstützend zu verwenden.


## excav PILOT App öffnen und starten

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 1.png"/>
</p>

Im ersten Schritt muss das Tablet mit der excav PILOT App gestartet werden. Gegebenenfalls müssen Sie es zunächst aufladen. Sobald Sie das System erstmals einrichten möchten, müssen Sie die ersten Schritte in der App genau befolgen. Bevor Sie zum Beispiel einen Arbeitsplatz anlegen oder laden können, müssen die Geräte und NTRIP im Startmenü eingerichtet werden.

Beim ersten Systemstart werden Ihnen direkt zwei Hinweise auf dem Tablet angezeigt:

!!! Warning "Sensor nicht verbunden"
    Sie können über das Startmenü unter „Geräte“ den GNSS-Sensor mit dem dazugehörigen Tablet des excav PILOT verknüpfen. Schalten Sie dafür den GNSS-Sensor ein und lassen Sie anschließend nach der Sensoreinheit suchen.

Weitere Informationen hierzu finden Sie unter [Geräte](../Geräte/Geräte.md) im Startmenü.

!!! Warning "Kein Arbeitsplatz aktiv"
    Um all Ihre Aktionen und Arbeitsschritte speichern zu können, benötigen Sie einen aktiven Arbeitsplatz. Legen Sie entweder einen neuen Arbeitsplatz an oder laden Sie einen bereits vorhandenen Arbeitsplatz.

Weitere Informationen hierzu finden Sie unter [Arbeitsplatz](../Arbeitsplatz/Arbeitsplatz.md) im Startmenü.

Das Tablet wird mit der excav PILOT App einsatzbereit mitgeliefert. Die Geräte wurden vorab testweise mit der App des Tablets gekoppelt. Um loszulegen und die Geräte zu koppeln, benötigen Sie auf dem Tablet eine aktive Bluetooth-Verbindung sowie eine Internetverbindung über mobile Daten, da die Kommunikation beider Geräte zum Tablet über Bluetooth erfolgt. Standardmäßig können zwei Geräte verbunden werden: der GNSS-Sensor und das LED-Anzeigekreuz.

Bevor Sie mit anderen Schritten fortfahren können, müssen Sie die Geräte zunächst einschalten. Gegebenenfalls müssen beide Geräte vor der ersten Einrichtung aufgeladen werden.  


## Geräte anschalten und verbinden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 2.png"/>
</p>

Betätigen Sie bei beiden Geräten (GNSS-Sensor und LED-Anzeigekreuz) den An-/Aus-Button auf der Unterseite, bis dieser grün aufleuchtet. Die Geräte können nur erkannt und per Bluetooth mit dem Tablet gekoppelt werden, wenn sie eingeschaltet sind und über ausreichend Akkuleistung verfügen (Ladestand idealerweise oberhalb von 20 %). Beginnen Sie am besten mit dem GNSS-Sensor, aktivieren Sie ihn und lassen Sie die App nach der Sensoreinheit scannen. Im Normalfall sollte der GNSS-Sensor sofort erkannt werden und sich problemlos verbinden lassen.


## GNSS-Sensor auswählen und verbinden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 3.png"/>
</p>

Es wird zuerst die Sensoreinheit angezeigt, die dem System bereits bekannt war bzw. zuletzt verbunden war. In der Regel wurde zuvor nur ein GNSS-Sensor verbunden, der folglich wieder vorgeschlagen wird. Betätigen Sie „Scannen“ und wählen Sie den angezeigten Sensor aus.

Die Verbindung kann jederzeit manuell wieder aufgehoben werden. Sollte die Verbindung eines oder mehrerer Geräte fehlschlagen, prüfen Sie bitte zuerst den Akkustand der entsprechenden Geräte (idealerweise über 20 %) und ob sie tatsächlich eingeschaltet sind. Stellen Sie sicher, dass der Sensor nicht bereits mit einem anderen Tablet gekoppelt ist und für ein anderes excav-PILOT-System eingesetzt wird. Platzieren Sie den GNSS-Sensor möglichst in der Nähe des Tablets und schalten Sie den Sensor ggf. mehrfach aus und wieder ein, bis der Verbindungsaufbau gelingt.


## LED-Anzeigekreuz auswählen und verbinden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 4.png"/>
</p>

Das Verfahren für das LED-Anzeigekreuz ist das gleiche: Betätigen Sie den orangenen Button „Scannen“ und wählen Sie das LED-Anzeigekreuz aus. Stellen Sie sicher, dass dieses nicht bereits mit einem anderen Tablet gekoppelt ist und für ein anderes System eingesetzt wird. Falls es zu Schwierigkeiten beim Verbindungsaufbau kommen sollte, prüfen Sie, ob der MAC-Wert übereinstimmt. Platzieren Sie das LED-Anzeigekreuz möglichst in der Nähe des Tablets und schalten Sie es ggf. mehrfach aus und wieder ein, bis der Verbindungsaufbau gelingt.

Ist der Verbindungsaufbau mit beiden Geräten gelungen, erscheinen diese mit dem MAC-Wert (auf der Rückseite der einzelnen Geräte ersichtlich) im Gerätefenster. Die graue Anzeige der Buttons „Trennen“ bedeutet, dass beide Geräte (einschließlich des optionalen LED-Anzeigekreuzes) erfolgreich verbunden wurden und ggf. wieder getrennt werden können.


## NTRIP für Korrekturdaten einrichten

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 6.png"/>
</p>

Das excav PILOT System erlaubt den Zugriff auf externe RTK-Korrekturdaten über eine NTRIP-Verbindung (engl. Networked Transport of RTCM via Internet Protocol). Der GNSS-Sensor erhält somit in Echtzeit Korrekturdaten für präzise Erdarbeiten auf der Baustelle im Zentimeterbereich. Die NTRIP-Funktion wird benötigt, um externe RTK-Korrekturdaten von einem Anbieter für GNSS-Dienste zu beziehen und auf Referenzstationen zugreifen zu können, ohne selbst eine eigene Basisstation vor Ort aufbauen und korrekt betreiben zu müssen.

Durch die Verbindung über NTRIP wird das 3D-GNSS-Assistenzsystem excav PILOT mobil und flexibel einsetzbar, ohne dass jede Maschine eigene Vermessungstechnik oder eine Basisstation benötigt – ein großer Vorteil gegenüber konventionellen Assistenzsystemen im Bau. Um NTRIP nutzen zu können, müssen Sie zuerst eine NTRIP-Verbindung in der App einrichten. Fahren Sie nach der Kopplung der Geräte unter „NTRIP“ fort, um dort die erste Verbindung einzurichten.


## NTRIP-Verbindung und Position des GNSS-Sensors

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 8.png"/>
</p>

Für die Einrichtung der NTRIP-Verbindung benötigen Sie eine Reihe von Angaben und Daten, die Sie für diesen Zweck über excav als Dienstleister erhalten. Eine wichtige Voraussetzung ist ein mobiler Internetzugang. Damit das Tablet die externen Korrekturdaten über NTRIP abrufen kann, muss eine Datenverbindung vorhanden sein (z. B. über Mobilfunk oder SIM-Karte).

Klicken Sie auf den Button „+ Hinzufügen“, um erstmals eine NTRIP-Verbindung anlegen zu können. Füllen Sie die Eingabefelder mit den verfügbaren Daten aus und vergeben Sie einen geeigneten Namen – insbesondere dann, wenn später mehrere NTRIP-Verbindungen eingerichtet werden. Tragen Sie alle erforderlichen Zugangsdaten des NTRIP-Dienstes ein: Hostname des NTRIP-Servers, Portnummer, Mountpoint, Benutzername und Passwort (falls erforderlich).

Wählen Sie den passenden Mountpoint bzw. Standort-Korrekturdienst. Prüfen Sie die Verbindung: Es sollte angezeigt werden, dass der NTRIP-Client verbunden ist und Korrekturdaten empfängt. 

!!! info "Tipps für guten NTRIP-Empfang"
    Achten Sie auf guten Mobilfunkempfang auf der Baustelle. Wenn die Verbindung zu langsam, brüchig oder anderweitig instabil ist, kann der NTRIP-Dienst nicht zuverlässig arbeiten. Wählen Sie den Mountpoint möglichst nah an der Baustelle, damit die Korrekturdaten eine geringere Latenz und bessere Genauigkeit aufweisen.

!!! info "Zweitsensor als optionale Basisstation"
    Falls keine Mobilfunkverbindung vorhanden ist, kann eine lokale Basisstation oder ein Hotspot nötig sein. Zukünftig kann ein optional erhältlicher Zweitsensor als stationäre Basisstation für eigene Korrekturdaten eingesetzt werden.

!!! Warning "NTRIP zunächst sorgfältig testen"
    Nach der Einrichtung von NTRIP sollte ein Testlauf erfolgen: Sensor montieren, Werkzeug kalibrieren, Korrekturdaten aktivieren und prüfen, ob sich die Werkzeuge präzise entsprechend dem digitalen Modell in der excav App verhalten.

Geben Sie zuletzt die exakten Positionsdaten (engl. Latitude / Longitude) des eingeschalteten GNSS-Sensors ein. Die erreichbare Lagegenauigkeit wird je nach Korrekturdatendienstleister mit ca. 1–3 cm angegeben. Der bekannteste Dienstleister auf dem deutschen Markt ist SAPOS.


## Geräte an der Baumaschine anbringen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Placeholder System einrichten 10.png"/>
</p>

Wenn Sie die Einrichtung erfolgreich abgeschlossen haben, können Sie mit dem Systemaufbau fortfahren. Weitere Informationen finden Sie im nächsten Schritt der Anleitung: [System aufbauen](https://docs.excav.de/System aufbauen/System aufbauen/)


<!-- BACKLOG

Text

BACKLOG -->