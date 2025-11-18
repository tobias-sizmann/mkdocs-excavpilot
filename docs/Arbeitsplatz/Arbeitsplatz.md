<style>
    setCenter{
        justify-content: center;
    }
</style>

# Arbeitsplatz

Hinweis: Diese Seite befindet sich gerade in Bearbeitung.

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz neu (1) - Kopie.jpg"/>
</p>

Der Menüpunkt „Arbeitsplatz“ bietet eine Reihe von Funktionen, um erstmals oder erneut einen Arbeitsplatz anzulegen, zu speichern und mehrere Arbeitsplätze entsprechend zu organisieren.

Sobald Sie den excav PILOT erstmals nutzen wollen und dafür die vorinstallierte App auf dem Tablet aufrufen, werden Sie direkt zu Beginn gebeten einen ersten Arbeitsplatz anzulegen oder einen bereits vorhandenen Arbeitsplatz zu laden, um Informationen abspeichern zu können.

In diesem Beispiel wird davon ausgegangen, dass Sie den excav PILOT zum ersten Mal nutzen und einen Arbeitsplatz anlegen müssen, um mit den weiteren Funktionen fortfahren zu können.  


## Neuen Arbeitsplatz erstellen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 1.png"/>
</p>

Direkt zu Beginn werden Sie auf der primären Arbeitsansicht gebeten einen neuen Arbeitsplatz anzulegen oder einen vorhandnen Arbeitsplatz zu laden. Sie finden diese Funktion jederzeit standardmäßig unter dem Startmenü. Sie können den Arbeitsplatz entweder direkt zu Beginn oder später mithilfe einer reingeladenen LandXML-Datei erstellen.


## Hauptansicht Arbeitsplätze

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 2.png"/>
</p>

Im Beispiel im Bild oben wurden bereits zwei Arbitsplätze zuvor angelegt, der Prozess für das Anlegen des ersten Arbeitsplatzes ist der gleiche wie für einen weiteren Arbeitsplatz. 


## Namen für einen neuen Arbeitsplatz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 3.png"/>
</p>

Text   


## Optional: Kalibrierung über CSV-Datei laden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 4.png"/>
</p>

Text  


## Optional: DGM als LandXML-Datei laden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 5.png"/>
</p>

Um einen neuen Arbeitsplatz speziell im Dateiformat LandXML in der App anzulegen, haben Sie zwei Möglichkeiten: Entweder in einem bestehenden Arbeitsplatz eine LandXML-Datei reinladen oder einen gänzlich neuen Arbeitsplatz mithilfe einer vorhandenen LandXML-Datei erstellen.

!!! info "Umgang mit LandXML-Dateien"
    Um einen neuen Arbeitsplatz speziell im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf den lokalen Speicher des Tablets hochladen. Als Nächstes müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Georeferenz- und Höhenreferenzsystem machen, die Sie von Ihrem Planungs- oder Ingenieuerbüro erhalten.

Über Art und Umfang der erforderlichen Angaben entscheidet maßgeblich die Wahl des Koordinaten- und Georeferenzsystems (mehr dazu erfahren Sie unter [Gelände](https://docs.excav.de/Gelände/Gelände/)). Sollten die eingegebenen Daten oder Einstellungen sowie die Beschaffenheit der LandXML-Datei nicht miteinander übereinstimmen, wird die App automatisch eine Fehlermeldung auslösen.


## Ursprung (Referenzpunkt) setzen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 6.png"/>
</p>

Wichtig: Im Arbeitsplatz sind alle Punkte absolut (nicht relativ) zum Referenzpunkt gespeichert (sie haben absolute Koordinaten und folglich einen absoluten Bezugspunkt).


## Neuer aktiver Arbeitsplatz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 7.png"/>
</p>

Sie können einen zuvor abgespeicherten Arbeitsplatz wieder laden und bearbeiten. In Ihrem ausgewählten Arbeitsplatz befinden sich alle folgenden Informationen gespeichert, die über das Designmenü in der Hauptansicht (siehe das Füller-Symbol) angelegt worden sind:

• Alle erfassten Punkte inklusive des Ursprungs (vormals Referenzpunkt)

• Alle erfassten Strecken, Geraden und Formen wie Polyeder

• Die aktuell aktive Fläche mit aktiver Werkzeugecke

• Den aktuell geladenen und entsprechend ausgerichteten Bauplan


!!! Warning "Speichern von Daten erforderlich"
    Wenn Sie den Arbeitsplatz neu laden, werden alle bisher erfassten und eingestellten Punkte oder Flächen nicht gespeichert und die Daten gehen somit verloren. Speichern Sie zur Sicherheit Ihren aktuellen Arbeitsplatz nach jedem nennenswert größeren Bearbeitungsschritt, um Datenverluste zu vermeiden.



!!! info "Speicherung der Werkzeuge"
    Die erstellten Werkzeuge (z.B. Baggerschaufel oder andere Werkzeuge) werden zwar auf Ebene der App, jedoch nicht auf der Ebene des einzelnen Arbeitsplatzes selbst gespeichert. Auf diese Weise bleiben alle exakt einkalibrierten Werkzeuge erhalten und müssen nicht stets aufs Neue in jedem Arbeitsplatz neu kalibriert und hinterlegt werden. Zudem gehen die einkalibrierten Maße nicht verloren, sollten Sie ohne Datenspeicherung den Arbeitsplatz wechseln.


## Hauptarbeitsansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz neu (10).jpg"/>
</p>

Sobald ein erster oder weiterer Arbeitsplatz angelegt worden ist (im Beispiel oben ohne eine LandXML-Datei), erscheint der GNSS-Sensor auf der primären Arbeitsansicht im Ursprung.


<!--
<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 1.jpg"/>
</p>
-->

<!-- Der Menüpunkt „Arbeitsplatz“ bietet eine Reihe von Funktionen, um Arbeitsplätze anzulegen, zu speichern und zu organisieren. Er umfasst derzeit folgende Unterpunkte: Neuer Arbeitsplatz, Arbeitsplatz speichern, Arbeitsplatz speichern als, Arbeitsplatz aus LandXML, Arbeitsplatz aus DXF sowie Referenzpunkt verschieben. 

Die Ansicht des Arbeitsplatzmenüs bietet Zugang zu mehreren Arbeitsplätzen mit Angabe von Datum und Uhrzeit des letzten Bearbeitungsstandes. Ein Arbeitsplatz lässt sich neu erstellen, bearbeiten sowie löschen, falls nicht länger erforderlich. 

Beachten Sie beim Laden den Hinweis, dass ungespeicherte Änderungen verloren gehen können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“.

Sie können einen zuvor abgespeicherten Arbeitsplatz wieder laden und bearbeiten. In Ihrem ausgewählten Arbeitsplatz befinden sich alle folgenden Informationen gespeichert, die über das Designmenü (siehe das Füller-Symbol) angelegt worden sind:

• Alle erfassten Punkte inklusive Referenzpunkt

• Alle erfassten Strecken, Geraden und Polyeder

• Die aktuell aktive Fläche mit eingestelltem Versatz und aktiver Werkzeugecke

• Den aktuell geladenen und entsprechend ausgerichteten Bauplan

Die erstellten Werkzeuge (z.B. Baggerschaufel oder andere Werkzeuge) werden zwar auf Ebene der App, jedoch nicht auf der Ebene des einzelnen Arbeitsplatzes selbst gespeichert. Auf diese Weise bleiben alle exakt einkalibrierten Werkzeuge erhalten und müssen nicht stets aufs Neue in jedem Arbeitsplatz neu kalibriert und hinterlegt werden. Zudem gehen die einkalibrierten Maße nicht verloren, sollten Sie ohne Speicherung der Daten den Arbeitsplatz wechseln.

Wichtig: Im Arbeitsplatz sind alle Punkte absolut (nicht relativ) zum Referenzpunkt gespeichert (sie haben absolute Koordinaten und folglich einen absoluten Bezugspunkt).

!!! warning "Speichern von Daten erforderlich"

Wenn Sie den Arbeitsplatz neu laden, werden alle bisher erfassten und eingestellten Punkte oder Flächen nicht gespeichert und die Daten gehen somit verloren. Speichern Sie zur Sicherheit Ihren aktuellen Arbeitsplatz nach jedem größeren Bearbeitungsschritt, um Datenverluste zu vermeiden. -->

<!--
## Neuer Arbeitsplatz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 1.jpg"/>
</p>

Um einen neuen Arbeitsplatz anzulegen, müssen Sie einen neuen Referenzpunkt setzen. Beachten Sie den Hinweis, dass bisher ungespeicherte Änderungen verloren können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“. Nach dem Bestätigen mit „Ok“ setzen Sie den neuen Referenzpunkt.


## Arbeitsplatz speichern

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 2.jpg"/>
</p>

[//]: # (Maurice: Von der alten App. Bitte überarbeiten. siehe Kommentar oben)

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

Um einen neuen Arbeitsplatz speziell im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf das Tablet hochladen und lokal ablegen. Wenn Sie die Funktion Gelände auswählen, werden Sie gebeten über "+ XML importieren" eine LandXML-Datei vom Tablet auszuwählen. Als Nächstes müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Geo-Referenz- und Höhen-Referenzsystem machen, die Sie im Vorfeld vom Planungs- oder Ingenieuerbüro erhalten.

Über Art und Umfang der erforderlichen Angaben entscheidet maßgeblich die Wahl des Geo-Referenzsystems. Sollten die eingegebenen Daten oder Einstellungen sowie die Beschaffenheit der LandXML-Datei nicht miteinander übereinstimmen, wird automatisch eine Fehlermeldung ausgelöst.


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
Wenn die Basisstation neu gestartet wurde oder eine neue Positionserfassung durchgeführt wurde, kann durch erneutes Setzen des Referenzpunktes an der Stelle des alten die Arbeitsfläche wieder zur Baustelle synchronisiert werden. -->