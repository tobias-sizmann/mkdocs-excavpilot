<style>
    setCenter{
        justify-content: center;
    }
</style>

# Arbeitsplatz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 1.jpg"/>
</p>

[//]: # (todo: Bitte nochmal komplett überarbeiten. kurze Anmerkungen: Anstatt "Arbeitsplatz als LandXML/DXF" bitte "Arbeitsplatz aus LandXML/DXF". Der Arbeitsplatz wird aus diesen Dateien generiert und in ein systemeigenes Format überführt.; Werkzeuge sind in einem Arbeitsplatz nicht mehr abgespeichert. Diese werden jetzt separat gespeichert. Ein Arbeitsplatz speichert alles, was du im Designmenü (Füllersymbol in der Arbeitsansicht) sehen kannst.; Es gibt aktuell keine Basisstation. Alle Punkte werden jetzt nicht mehr relativ, sondern absolut erfasst.;  )

[//]: # (Peter: Arbeitsplatz aus LandXML/DXF / Werkzeuge nicht in Arbeitsplatz gespeichert / Infos über Design Menü / Basisstation entfernt / Alle Punkt absolut, statt relativ)

Der Menüpunkt „Arbeitsplatz“ bietet eine Reihe von Funktionen, um Arbeitsplätze anzulegen, zu speichern und zu organisieren. Er umfasst derzeit folgende Unterpunkte: Neuer Arbeitsplatz, Arbeitsplatz speichern, Arbeitsplatz speichern als, Arbeitsplatz aus LandXML, Arbeitsplatz aus DXF sowie Referenzpunkt verschieben.

Die Ansicht des Arbeitsplatzmenü bietet Zugang zu mehreren Arbeitsplätzen mit Angabe von Datum und Uhrzeit des letzten Bearbeitungsstandes. Ein Arbeitsplatz lässt sich neu erstellen, bearbeiten sowie löschen, falls nicht länger erforderlich. Beachten Sie beim Laden den Hinweis, dass ungespeicherte Änderungen verloren gehen können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“.

Sie können einen zuvor abgespeicherten Arbeitsplatz wieder laden und bearbeiten. In Ihrem ausgewählten Arbeitsplatz befinden sich alle folgenden Informationen gespeichert, die über das Designmenü (siehe das Füller-Symbol) angelegt worden sind:

• Alle erfassten Punkte inklusive Referenzpunkt

• Alle erfassten Strecken, Geraden und Polyeder

• Die aktuell aktive Fläche mit eingestelltem Versatz und aktiver Werkzeugecke

• Den aktuell geladenen und entsprechend ausgerichteten Bauplan

Die erstellten Werkzeuge (z.B. Baggerschaufel oder andere Werkzeuge) werden zwar auf Ebene der App, jedoch nicht auf der Ebene des einzelnen Arbeitsplatzes selbst gespeichert. Auf diese Weise bleiben alle exakt einkalibrierten Werkzeuge erhalten und müssen nicht stets aufs Neue in jedem Arbeitsplatz neu kalibriert und hinterlegt werden. Zudem gehen die einkalibrierten Maße nicht verloren, sollten Sie ohne Speicherung der Daten den Arbeitsplatz wechseln.

Wichtig: Im Arbeitsplatz sind alle Punkte absolut (nicht relativ) zum Referenzpunkt gespeichert (sie haben absolute Koordinaten und folglich einen absoluten Bezugspunkt).

!!! warning "Speichern von Daten erforderlich"

Wenn Sie den Arbeitsplatz neu laden, werden alle bisher erfassten und eingestellten Punkte oder Flächen nicht gespeichert und die Daten gehen somit verloren. Speichern Sie zur Sicherheit Ihren aktuellen Arbeitsplatz nach jedem größeren Bearbeitungsschritt, um Datenverluste zu vermeiden.


## Neuer Arbeitsplatz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 1.jpg"/>
</p>

Um einen neuen Arbeitsplatz anzulegen, müssen Sie einen neuen Referenzpunkt setzen. Beachten Sie den Hinweis, dass bisher ungespeicherte Änderungen verloren können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“. Nach dem Bestätigen mit „Ok“ setzen Sie den neuen Referenzpunkt.


## Arbeitsplatz speichern

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 2.jpg"/>
</p>

[//]: # (todo: Von der alten App. Bitte überarbeiten. siehe Kommentar oben)

Die Funktion "Arbeitsplatz speichern" nutzen Sie, um alle erfassten – für den Arbeitsbereich der Baustelle relevanten – Werte und Einstellungen dauerhaft zu speichern. Sie haben hierfür zwei Optionen. Entweder Sie erstellen eine neue Datei (Neu anlegen) oder überschreiben einen bereits existierenden Arbeitsplatz (Überschreiben). Abgespeichert werden folgende Informationen:

• Alle erfassten Punkte inklusive Referenzpunkt

• Alle erfassten Strecken, Geraden und Polyeder

• Die aktuell aktive Fläche mit eingestelltem Versatz und aktiver Werkzeugecke

• Den aktuell geladenen und entsprechend ausgerichteten Bauplan

• Alle erstellten Werkzeuge (z.B. Baggerschaufel oder andere)

Bitte beachten Sie, dass Sie alle Änderungen manuell erneut abspeichern müssen. Schließen Sie die App, dann gehen alle nicht abgespeicherten Änderungen verloren (Minimieren der App ist dagegen kein Problem und führt nicht zu Datenverlust). Ob Sie ungespeicherte Änderungen in Ihrem Arbeitsplatz haben, können Sie ganz unten im Funktionsbildschirm überprüfen.


## Arbeitsplatz als LandXML

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 3.jpg"/>
</p>

[//]: # (Peter: Aspekt LandXML überarbeitet, die Erklärung im Detail unter "Gelände")

Um einen neuen Arbeitsplatz speziell im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf das Tablet hochladen und lokal ablegen. Wenn Sie die Funktion Gelände auswählen, werden Sie gebeten über "+ XML importieren" eine LandXML-Datei vom Tablet auszuwählen. Als Nächstes müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Geo-Referenz- und Höhen-Referenzsystem machen, die Sie im Vorfeld vom Planungs- oder Ingenieuersbüro erhalten.

Über Art und Umfang der erforderlichen Angaben entscheidet maßgeblich die Wahl des Geo-Referenzsystems. Sollten die eingebenen Daten oder Einstellungen sowie die Beschaffenheit der LandXML-Datei nicht miteinander übereinstimmen, wird automatisch eine Fehlermeldung ausgelöst. 


**Auswahloption: Referenzsystem ETRS89/UTM**

Für das Geo-Referenzsystem sind folgende Angaben erforderlich: 

- Referenzsystem: Wählen Sie die Option ETRS89/UTM aus

- Layout: NorthEastAlt (Zone: 32 / 33) / EastNorthAlt (Zone: 32 / 33)/ NorthZonedEastAlt / ZonedEastNorthAlt

Für das Höhen-Referenzsystem sind folgende Angaben erforderlich: 

- Referenzsystem: Wählen Sie zwischen den Optionen DHHN und Ellipsoid aus


**Auswahloption: Referenzsystem DHDN/GK3**

Für das Geo-Referenzsystem sind folgende Angaben erforderlich: 

- Referenzsystem: Wählen Sie die Option DHDN/GK3 aus

- Layout: HochRechtsAlt (Zone: 2 / 3/ 4) / RechtsHochAlt (Zone: 2 / 3 / 4) / HochZonedRechtsAlt / ZonedRechtsHochAlt

- Bundesland: Auswahl des betreffenden Bundeslandes

Für das Höhen-Referenzsystem sind folgende Angaben erforderlich: 

- Referenzsystem: Wählen Sie zwischen den Optionen DHHN und Ellipsoid aus


**Vorgang XML kalibrieren**

Punkte oder Punktewolken in LandXML-Dateien sind zwar absolut als reale Punkte auf der Erde referenziert, doch es können etwaige Fehler und Abweichungen auftreten, wodurch Abweichungen zwischen den vordefinierten LandXML-Punkten und realen Punkten später mittels des Messstabs auf der Baustelle möglich sind. Über die Funktion XML kalibrieren können Sie bestimmen, dass reale Punkte auf der Baustelle genutzt werden, um die Bauplanansicht der LandXML-Datei daran auszurichten. Der Punkt bzw. die Punkte innerhalb der LandXML-Datei werden um die Differenz entsprechend verschoben. Wählen Sie mindestens einen Punkt aus, damit dieser mit einem eingmessenen Punkt der Wahl in Übereinstimmung gbracht wird.   

Beachten Sie den Hinweis, dass ungespeicherte Änderungen verloren können. Vergeben Sie dem neuen Arbeitsplatz unter „Bezeichnung“ einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“. Wählen Sie im Anschluss die gewünschte LandXML-Datei aus, die zuvor auf das Tablet hochgeladen worden ist.


## Arbeitsplatz als DXF

<p align="center" width="100%">
<img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 4.jpg"/>
</p>

[//]: # (todo: Ist noch Beta und sollte hier erstmal entfernt werden.)

Um einen neuen Arbeitsplatz speziell im Format DXF anzulegen, müssen Sie einen neuen Referenzpunkt setzen. Beachten Sie den Hinweis, dass ungespeicherte Änderungen verloren können. Vergeben Sie dem neuen Arbeitsplatz unter „Bezeichnung“ einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“. Wählen Sie im Anschluss die gewünschte DXF-Datei aus, die zuvor auf das Tablet hochgeladen worden ist.


## Referenzpunkt verschieben

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Referenzpunkt.jpg"/>
</p>

Ein Referenzpunkt kann ebenfalls nachträglich verschoben werden. Beachten Sie den Hinweis, dass ungespeicherte Änderungen verloren gehen können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“.
