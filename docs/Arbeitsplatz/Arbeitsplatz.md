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

Der Menüpunkt „Arbeitsplatz“ bietet eine Reihe von Funktionen, um Arbeitsplätze anzulegen, zu speichern und zu organisieren. Er umfasst derzeit folgende Unterpunkte: Neuer Arbeitsplatz, Arbeitsplatz speichern, Arbeitsplatz speichern als, Arbeitsplatz als LandXML, Arbeitsplatz als DXF sowie Referenzpunkt verschieben.

Die Ansicht des Arbeitsplatzmenü bietet Zugang zu mehreren Arbeitsplätzen mit Angabe von Datum und Uhrzeit des letzten Bearbeitungsstandes. Ein Arbeitsplatz lässt sich neu erstellen, bearbeiten sowie löschen, falls nicht länger erforderlich. Beachten Sie beim Laden den Hinweis, dass ungespeicherte Änderungen verloren gehen können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“.

Sie können einen zuvor abgespeicherten Arbeitsplatz wieder laden und bearbeiten. In Ihrem ausgewählten Arbeitsplatz befinden sich folgende Informationen:

• Alle erfassten Punkte inklusive Referenzpunkt

• Alle erfassten Strecken, Geraden und Polyeder

• Die aktuell aktive Fläche mit eingestelltem Versatz und aktiver Werkzeugecke

• Den aktuell geladenen und entsprechend ausgerichteten Bauplan

• Alle erstellten Werkzeuge (z.B. Baggerschaufel oder andere)

Wichtig: Im Arbeitsplatz sind alle Punkte relativ zum Referenzpunkt gespeichert (sie haben keine absoluten Koordinaten und folglich keinen absoluten Bezugspunkt) und der Referenzpunkt wird in Relation zur Basisstation erfasst (falls vorhanden). Das bedeutet, dass Sie beim Laden des Arbeitsplatzes zwei Möglichkeiten haben:
Sie haben seit den letzten Arbeiten die Basisstation nicht bewegt (z.B. über die Mittagspause haben Sie das System ausgeschaltet). Dann können Sie, ohne den Referenzpunkt neu zu setzen direkt dort weiterarbeiten, wo Sie aufgehört haben.

Können Sie auf wenige Millimeter genau bestimmen, wo sich die Basisstation, während der letzten Arbeiten zuvor befunden hat? Wenn nicht empfehlen wir, den Referenzpunkt erneut zu vermessen, indem Sie mit dem Messstab so genau wie möglich den Referenzpunkt der letzten Arbeiten antasten und erfassen. Die neue Position der Basisstation führt dann nicht zu Fehlern.

!!! warning "Positionsfehler der Basisstation"

Sollten Sie die Basisstation nicht wieder auf exakt dieselbe Position wie zuvor setzen und auch den Referenzpunkt nicht neu antasten, dann verschieben sich alle im betreffenden Arbeitsplatz aufgenommenen Punkte um die Distanz zwischen der derzeitigen und der vorherigen Position der Basisstation. Dieser Positionsfehler zieht sich dann durch alle weiteren Arbeiten. Sind Sie sich unsicher, dann setzen Sie den Referenzpunkt neu. Die Position der Basisstation ist egal.

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

[//]: # (todo: Bei LandXML muss kein RefPunkt gesetzt werden. Bitte hier vollständig auf das Einlesen von LandXML eingehen. Wichtig ist hier vor allem der Schritt "XML-Metadaten". Was muss der User hier machen?)

Um einen neuen Arbeitsplatz speziell im Format LandXML anzulegen, müssen Sie XXX. 

- Erklärung Einlesen von LandXML

- Schritt XML-Metadaten

- Erklärung Aufgabe User 

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
