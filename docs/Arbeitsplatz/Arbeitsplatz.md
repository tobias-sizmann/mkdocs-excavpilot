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

[//]: # (Peter: Arbeitsplatz aus LandXML/DXF / Werkzeuge nicht in Arbeitsplatz gespeichert / Infos über Design Menü / Thema Basisstation entfernt / Alle Punkte absolut, statt relativ)

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

[//]: # (Peter: Thema Werkzeuge entfernt)

Die Funktion "Arbeitsplatz speichern" nutzen Sie, um alle für den Arbeitsbereich der Baustelle relevanten Werte und Einstellungen dauerhaft zu speichern. Sie haben hierfür zwei Optionen. Entweder Sie erstellen eine neue Datei (Neu anlegen) oder überschreiben einen bereits existierenden Arbeitsplatz (Überschreiben). Abgespeichert werden folgende Informationen:

• Alle erfassten Punkte inklusive Referenzpunkt

• Alle erfassten Strecken, Geraden und Polyeder

• Die aktuell aktive Fläche mit eingestelltem Versatz und aktiver Werkzeugecke

• Den aktuell geladenen und entsprechend ausgerichteten Bauplan

Bitte beachten Sie, dass Sie alle Änderungen manuell erneut abspeichern müssen. Schließen Sie die App, dann gehen alle nicht abgespeicherten Änderungen verloren (Minimieren der App ist dagegen kein Problem und führt nicht zu Datenverlust). Ob Sie ungespeicherte Änderungen in Ihrem Arbeitsplatz haben, können Sie ganz unten im Funktionsbildschirm überprüfen.


## Arbeitsplatz als LandXML

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 3.jpg"/>
</p>

[//]: # (Peter: Aspekt LandXML überarbeitet, die Erklärung im Detail unter "Gelände")

Um einen neuen Arbeitsplatz speziell im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf das Tablet hochladen und lokal ablegen. Wenn Sie die Funktion Gelände auswählen, werden Sie gebeten über "+ XML importieren" eine LandXML-Datei vom Tablet auszuwählen. Als Nächstes müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Geo-Referenz- und Höhen-Referenzsystem machen, die Sie im Vorfeld vom Planungs- oder Ingenieuersbüro erhalten.

Über Art und Umfang der erforderlichen Angaben entscheidet maßgeblich die Wahl des Geo-Referenzsystems. Sollten die eingebenen Daten oder Einstellungen sowie die Beschaffenheit der LandXML-Datei nicht miteinander übereinstimmen, wird automatisch eine Fehlermeldung ausgelöst.


## Referenzpunkt verschieben

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Referenzpunkt.jpg"/>
</p>

Ein Referenzpunkt kann ebenfalls nachträglich verschoben werden. Beachten Sie den Hinweis, dass ungespeicherte Änderungen verloren gehen können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“.


## Referenzpunkt neu setzen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Referenzpunkt.jpg"/>
</p>

Diese Funktion erlaubt eine Neuermittlung des Referenzpunkts, falls erforderlich. Das Setzen des Referenzpunktes wird automatisch zu Beginn der Erstellung eines Arbeitsplatzes abgefragt.

!!! warning "Setzen des Referenzpunktes"

Wenn Sie den Referenzpunkt neu setzen, werden alle erfassten und eingestellten Punkte oder Flächen um die Differenz zwischen dem aktuellen Referenzpunkt und dem neuen Referenzpunkt verschoben und sind somit nicht mehr gültig.
Wenn die Basisstation neu gestartet wurde oder eine neue Positionserfassung durchgeführt wurde, kann durch erneutes Setzen des Referenzpunktes an der Stelle des alten die Arbeitsfläche wieder zur Baustelle synchronisiert werden.
