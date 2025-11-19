<style>
    setCenter{
        justify-content: center;
    }
</style>

# Arbeitsplatz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz neu (1) - Kopie.jpg"/>
</p>

Der Menüpunkt „Arbeitsplatz“ bietet eine Reihe von Funktionen, um erstmals oder erneut einen Arbeitsplatz anzulegen, zu speichern und mehrere Arbeitsplätze entsprechend zu organisieren.

Sobald Sie den excav PILOT erstmals nutzen wollen und dafür die vorinstallierte App auf dem Tablet aufrufen, werden Sie direkt zu Beginn gebeten, einen ersten Arbeitsplatz anzulegen oder einen bereits vorhandenen Arbeitsplatz zu laden, um Informationen abspeichern zu können.

In diesem Beispiel wird davon ausgegangen, dass Sie den excav PILOT zum ersten Mal nutzen und einen Arbeitsplatz anlegen müssen, um mit den weiteren Funktionen fortfahren zu können.  


## Neuen Arbeitsplatz erstellen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 1.png"/>
</p>

Direkt zu Beginn werden Sie auf der primären Arbeitsansicht gebeten, einen neuen Arbeitsplatz anzulegen oder einen vorhandenen Arbeitsplatz zu laden. Sie finden diese Funktion jederzeit standardmäßig unter dem Startmenü. Sie können den Arbeitsplatz entweder direkt zu Beginn mit einer LandXML-Datei erstellen oder diese später über [Gelände](https://docs.excav.de/Gelände/Gelände/) im Designmenü laden.


## Hauptansicht Arbeitsplätze

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 2.png"/>
</p>

Im Beispiel im Bild oben wurden bereits zwei Arbeitsplätze zuvor angelegt. Der Prozess zum Anlegen des ersten Arbeitsplatzes ist derselbe wie für jeden weiteren Arbeitsplatz. Auf dieser Ebene haben Sie zudem die Möglichkeit, gezielt alle Bearbeitungsschritte der Datei zu speichern.  


## Namen für einen neuen Arbeitsplatz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 3.png"/>
</p>

Vergeben Sie dem Arbeitsplatz einen eindeutigen Namen – vor allem, wenn Sie viele Arbeitsplätze über ein excav-PILOT-System verwalten müssen. Der Name darf nicht identisch zu anderen Arbeitsplätzen sein und kein Leerzeichen enthalten. 


## Optional: Kalibrierung über CSV-Datei laden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 4.png"/>
</p>

Optional können Sie zu diesem Zeitpunkt eine CSV-Kalibrierungsdatei hochladen, um direkt eine sogenannte 7-Parameter-Transformation nach Helmert für das künftige Projekt zu erstellen.  

!!! info "7-Parameter-Transformation (nach Helmert)"
    Die 7-Parameter-Transformation (auch Helmert-Transformation genannt) ist ein mathematisches Verfahren, um Koordinatenpunkte von einem dreidimensionalen Bezugssystem in ein anderes zu überführen. Sie wird eingesetzt, wenn unterschiedliche Koordinatensysteme miteinander verbunden werden sollen. Die Transformation nutzt dabei sieben einzelne Parameter: drei Parameter für die Translation (Verschiebungen in x-, y- und z-Richtung), drei Parameter für die Rotation (Drehungen um die Achsen) und einen Parameter für den Maßstab (einheitliche Skalierung). Zusammenfassend beschreibt die Transformation, wie man einen 3D-Punkt durch Verschieben, Drehen und Skalieren vom Ausgangssystem ins Zielsystem überführen kann.



## Optional: DGM als LandXML-Datei laden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 5.png"/>
</p>

Um einen neuen Arbeitsplatz speziell im Dateiformat LandXML in der App anzulegen, haben Sie zwei Möglichkeiten: entweder in einem bestehenden Arbeitsplatz eine LandXML-Datei laden oder einen vollständig neuen Arbeitsplatz mithilfe einer vorhandenen LandXML-Datei erstellen.

!!! info "Umgang mit LandXML-Dateien"
    Um einen neuen Arbeitsplatz im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf den lokalen Speicher des Tablets hochladen. Anschließend müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Geo- und Höhenreferenzsystem machen, die Sie von Ihrem Planungs- oder Ingenieurbüro erhalten.

Art und Umfang der erforderlichen Angaben hängen maßgeblich von der Wahl des Koordinaten- und Georeferenzsystems ab (mehr dazu unter [Gelände](https://docs.excav.de/Gelände/Gelände/)). Sollten die eingegebenen Daten oder Einstellungen sowie die Beschaffenheit der LandXML-Datei nicht miteinander übereinstimmen, wird die App automatisch eine Fehlermeldung auslösen.


## Ursprung (Referenzpunkt) setzen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 6.png"/>
</p>

Für die Erstellung einer Arbeitsansicht in einem Projekt ist ein Ursprung (vormals Referenzpunkt) erforderlich. Der Ursprung muss nicht zwingend ein späterer Punkt auf dem Areal der Baustelle sein. Er wird als räumliche Referenz für ein neues Projekt benötigt. Sie können den Ursprung manuell durch Eingabe von Werten oder durch die Erfassung eines Punktes vor Ort bestimmen. 

Wichtig: Im Arbeitsplatz sind alle Punkte absolut (nicht relativ) zum Referenzpunkt gespeichert (sie verfügen über absolute Koordinaten und somit einen absoluten Bezugspunkt).


## Neuer aktiver Arbeitsplatz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz PNG 7.png"/>
</p>

Sie können einen zuvor gespeicherten Arbeitsplatz wieder laden und bearbeiten. In Ihrem ausgewählten Arbeitsplatz befinden sich alle folgenden Informationen, die über das Designmenü in der Hauptansicht (siehe das Füller-Symbol) angelegt wurden:

• Alle erfassten Punkte einschließlich Ursprung (vormals Referenzpunkt)

• Alle erfassten Strecken, Geraden und Formen wie Polyeder

• Die aktuell aktive Fläche mit aktiver Werkzeugecke

• Den aktuell geladenen und entsprechend ausgerichteten Bauplan


!!! Warning "Speichern von Daten erforderlich"
    Wenn Sie den Arbeitsplatz neu laden, werden alle bisher erfassten und eingestellten Punkte oder Flächen nicht gespeichert und die Daten gehen somit verloren. Speichern Sie zur Sicherheit Ihren aktuellen Arbeitsplatz nach jedem nennenswerten Bearbeitungsschritt, um Datenverluste zu vermeiden.



!!! info "Speicherung der Werkzeuge"
    Die erstellten Werkzeuge (z. B. Baggerschaufel oder andere Werkzeuge) werden zwar auf Ebene der App, jedoch nicht auf Ebene des einzelnen Arbeitsplatzes gespeichert. Auf diese Weise bleiben alle exakt kalibrierten Werkzeuge erhalten und müssen nicht in jedem Arbeitsplatz erneut kalibriert und hinterlegt werden. Zudem gehen die kalibrierten Maße nicht verloren, sollten Sie ohne Datenspeicherung den Arbeitsplatz wechseln.


## Hauptarbeitsansicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Arbeitsplatz neu (10).jpg"/>
</p>

Sobald ein erster oder weiterer Arbeitsplatz angelegt wurde (im Beispiel oben ohne eine LandXML-Datei), erscheint der GNSS-Sensor auf der primären Arbeitsansicht im Ursprungspunkt.

!!! info "Ursprung als Referenzpunkt"
    Der Ursprung dient als Nullpunkt, von dem aus alle weiteren Maße errechnet werden. Zu Beginn eines neuen Arbeitsplatzes bildet der Referenzpunkt den Mittelpunkt eines statischen Koordinatensystems. Hierfür bietet sich idealerweise eine Stelle auf der Baustelle an, die über den gesamten Bauverlauf verfügbar bleibt, sich nicht ändert, jederzeit gut zu erreichen ist und freie Sicht auf den Himmel bietet. 


<!-- BACKLOG

Der Menüpunkt „Arbeitsplatz“ bietet eine Reihe von Funktionen, um Arbeitsplätze anzulegen, zu speichern und zu organisieren. Er umfasst derzeit folgende Unterpunkte: Neuer Arbeitsplatz, Arbeitsplatz speichern, Arbeitsplatz speichern als, Arbeitsplatz aus LandXML, Arbeitsplatz aus DXF sowie Referenzpunkt verschieben. 

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

Wenn Sie den Arbeitsplatz neu laden, werden alle bisher erfassten und eingestellten Punkte oder Flächen nicht gespeichert und die Daten gehen somit verloren. Speichern Sie zur Sicherheit Ihren aktuellen Arbeitsplatz nach jedem größeren Bearbeitungsschritt, um Datenverluste zu vermeiden.


## Neuer Arbeitsplatz

Um einen neuen Arbeitsplatz anzulegen, müssen Sie einen neuen Referenzpunkt setzen. Beachten Sie den Hinweis, dass bisher ungespeicherte Änderungen verloren können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“. Nach dem Bestätigen mit „Ok“ setzen Sie den neuen Referenzpunkt.


## Arbeitsplatz speichern

Die Funktion "Arbeitsplatz speichern" nutzen Sie, um alle für den Arbeitsbereich der Baustelle relevanten Werte und Einstellungen dauerhaft zu speichern. Sie haben hierfür zwei Optionen. Entweder Sie erstellen eine neue Datei (Neu anlegen) oder überschreiben einen bereits existierenden Arbeitsplatz (Überschreiben). Abgespeichert werden folgende Informationen:

• Alle erfassten Punkte inklusive Referenzpunkt

• Alle erfassten Strecken, Geraden und Polyeder

• Die aktuell aktive Fläche mit eingestelltem Versatz und aktiver Werkzeugecke

• Den aktuell geladenen und entsprechend ausgerichteten Bauplan

Bitte beachten Sie, dass Sie alle Änderungen manuell erneut abspeichern müssen. Schließen Sie die App, dann gehen alle nicht abgespeicherten Änderungen verloren (Minimieren der App ist dagegen kein Problem und führt nicht zu Datenverlust). Ob Sie ungespeicherte Änderungen in Ihrem Arbeitsplatz haben, können Sie ganz unten im Funktionsbildschirm überprüfen.


## Arbeitsplatz als LandXML

Um einen neuen Arbeitsplatz speziell im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf das Tablet hochladen und lokal ablegen. Wenn Sie die Funktion Gelände auswählen, werden Sie gebeten über "+ XML importieren" eine LandXML-Datei vom Tablet auszuwählen. Als Nächstes müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Geo-Referenz- und Höhen-Referenzsystem machen, die Sie im Vorfeld vom Planungs- oder Ingenieuerbüro erhalten.

Über Art und Umfang der erforderlichen Angaben entscheidet maßgeblich die Wahl des Geo-Referenzsystems. Sollten die eingegebenen Daten oder Einstellungen sowie die Beschaffenheit der LandXML-Datei nicht miteinander übereinstimmen, wird automatisch eine Fehlermeldung ausgelöst.


## Referenzpunkt verschieben

Ein Referenzpunkt kann ebenfalls nachträglich verschoben werden. Beachten Sie den Hinweis, dass ungespeicherte Änderungen verloren gehen können. Vergeben Sie dem neuen Arbeitsplatz einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“.


## Referenzpunkt neu setzen

Diese Funktion erlaubt eine Neuermittlung des Referenzpunkts, falls erforderlich. Das Setzen des Referenzpunktes wird automatisch zu Beginn der Erstellung eines Arbeitsplatzes abgefragt.

!!! warning "Setzen des Referenzpunktes"

Wenn Sie den Referenzpunkt neu setzen, werden alle erfassten und eingestellten Punkte oder Flächen um die Differenz zwischen dem aktuellen Referenzpunkt und dem neuen Referenzpunkt verschoben und sind somit nicht mehr gültig.
Wenn die Basisstation neu gestartet wurde oder eine neue Positionserfassung durchgeführt wurde, kann durch erneutes Setzen des Referenzpunktes an der Stelle des alten die Arbeitsfläche wieder zur Baustelle synchronisiert werden. 

BACKLOG -->