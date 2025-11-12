<style>
    setCenter{
        justify-content: center;
    }
</style>

# Gelände

Hinweis: Diese Seite befindet sich gerade in Bearbeitung.

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände (19).jpg"/>
</p>

Das Einlesen und die Nutzung von Digitalen Geländemodellen (DGM) im LandXML-Format für eine vollständig in 3D visualisierte Arbeitsweise auf der Baustelle ist eine der Hauptfunktionen der excav App-Anwendung. Nutzer können sich jederzeit entscheiden, ob sie Baupläne als PDF in der zweidimensionalen Ansicht oder mithilfe von DGM im LandXML-Format sogar im dreidimensionalen Raum für ein intuitives und immersives Arbeitserlebnis. 

!!! info "Dateiformat LandXML"

LandXML ist ein gängiges Dateiformat zum Austauschen von georeferenzierten Objekten zwischen Anwendungen. Die XML-Anwendung erlaubt damit die Übermittlung von Objekten mit Attributen, Distanzrelationen und Geometrien zwischen verschiedenen Endgeräten, insbesondere für die Geodäsie und Tiefbauanwendungen. Da die Vermessungsdaten georeferenziert sind, erscheinen die Inhalte der Datei lediglich dann sichtbar auf dem Bildschirm des Tablets, wenn sich der Nutzer mit dem GNSS-Sensor innerhalb des dafür georeferenzierten Areals befindet.

Da die Baupläne einer LandXML-Datei nicht wie bei einer PDF-Datei ohne jede Georeferenzierung auskommen und bereits in 2D einfach aus der Vogelperspektive darstellbar sind, erfordert der Import eines DGM ein grundlegendes Verständnis für die Vermessung in der Geodäsie. 

!!! info "Bezug von geodätischen Plänen"

Sie erhalten georeferenzierte Baupläne als LandXML oder in vergleichbaren Dateiformaten typischerweise von einem Ingenieurs- oder Planungsbüro sowie ggf. intern vom fachkundigen Spezialisten. Über diese erhalten Sie notwendige Informationen zum Koordinatensystem, Georeferenzsystem und erforderlichem Format, um die Datei korrekt darzustellen. 


## Import eines digitalen Geländemodells

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände (1) - Kopie.jpg"/>
</p>

Um einen neuen Arbeitsplatz speziell im Dateiformat LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf das Tablet hochladen und dort lokal ablegen. Wenn Sie die Funktion Gelände im Designmenü auswählen, werden Sie gebeten über "+ XML importieren" eine LandXML-Datei vom lokalen Speicher des Tablets auszuwählen. Für DGM steht aktuell (Stand November 2025) nur das Dateifomat LandXML zur Verfügung. Folglich ist diese Auswahloption unter der Funktion Gelände voreingestellt.   


## Koordinaten- und Georeferenzsysteme

### Koordinatensysteme

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände aktuell (5) - Kopie 2.png"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Koordinatensysem** | Wählen Sie hier das Ihnen mitgeteilte Koordinatensystem für die LandXML-Datei aus. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Georeferenzsystem** | Wählen Sie hier das Ihnen mitgeteilte Georeferenzsystem (basierend zuvor auf Punkt 1) für die LandXML-Datei aus. 

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Format** | Wählen Sie hier das Ihnen mitgeteilte Format (basierend zuvor auf Punkt 2) für die LandXML-Datei aus. 



Ein Koordinatensystem ist ein länderspezifisch oder weltweit einheitliches Bezugssystem zur Bestimmung von Positionen auf der Erdoberfläche. Es basiert auf dem Modell eines Erdellipsoid, das die Form der Erde mathematisch exakt beschreibt, und definiert Breiten- und Längengrade als Koordinaten. Hierdurch lassen sich Orte auf der Erdoberfläche eindeutig durch geografische Breite (Latitude) und geografische Länge (Longitude) angeben.

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Universal Transverse Mercator (UTM)** | Das UTM-System (englisch Universal Transverse Mercator) ist ein global anwendbares und weltweit einheitlich angewandtes Koordinatensystem. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Gauss-Krüger (DE)** | Das Gauss-Krüger-Koordinatensystem (DE) ist ein in Deutschland traditionell verwendetes Abbildungssystem, welches zunehmend durch UTM abgelöst wird. 

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Gauss-Krüger (AT)** | Das Gauss-Krüger-Koordinatensystem (AT) ist das frühere amtliche Koordinatensystem von Österreich, welches ebenfalls zunehmend durch UTM abgelöst wird. 

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Geodätisches Koordinatensystem (Geodetic)** | Geodetic verwendet ein mathematisches Erdmodell, das die Form und Größe der Erde als Rotationsellipsoid beschreibt und präzise Berechnung geografischer Koordinaten auf der Erdoberfläche ermöglicht.

Weitere länderspezifische Koordinatensysteme werden zusätzlich zum europa- und weltweit anerkannten und angewandten UTM-System schrittweise implementiert.

!!! info "Koordinatensystem Universal Transverse Mercator (UTM)"

Das UTM-Koordinatensystem ist ein weltweit einheitliches, rechtwinkliges Koordinatensystem zur genauen Positionsbestimmung. Es basiert auf einer Abbildung des Erdellipsoids in 60 Meridianzonen, die jeweils 6° breit sind und durch eine transversale Mercatorprojektion dargestellt werden. Jede Zone besitzt ein eigenes Koordinatennetz mit Ost- (Rechtswert) und Nordwert (Hochwert) in Metern, wodurch Entfernungen direkt messbar sind. Das UTM-System wird häufig in topografischen Karten, GPS-Geräten und geografischen Informationssystemen (GIS) verwendet, da es präzise, metrisch und weltweit standardisiert ist. In Deutschland wird meist das auf dem ETRS89-Referenzellipsoid basierende UTM-System genutzt.

!!! info "Koordinatensystem Gauss-Krüger (DE)"

Das Gauss-Krüger-Koordinatensystem ist ein in Deutschland traditionell verwendetes rechtwinkliges Abbildungssystem, das auf der transversalen Mercatorprojektion basiert. Die Erdoberfläche wird dabei in 3° breite Meridianstreifen unterteilt, in denen Positionen durch Rechts- (Ost-) und Hochwerte (Nordwerte) in Metern angegeben werden. Grundlage ist mehrheitlich das Bessel-Ellipsoid und das Datum Potsdam (DHDN). Das System wurde lange für amtliche topografische Karten und Vermessungen genutzt, wird heute jedoch zunehmend durch das UTM-Koordinatensystem ersetzt, das international einheitlicher und GPS-kompatibler ist.


!!! info "Koordinatensystem Gauss-Krüger (AT)"

Das Gauss-Krüger-Koordinatensystem (AT) ist das frühere amtliche Koordinatensystem Österreichs, das auf der transversalen Mercatorprojektion basiert. Es teilt die Erdoberfläche in 3° breite Meridianstreifen, innerhalb derer Positionen durch Rechts- und Hochwerte in Metern angegeben werden. Als Bezugsellipsoid dient das Bessel-Ellipsoid, und als geodätisches Datum wurde das MGI (Militärgeografisches Institut) verwendet. Das System war lange Zeit Grundlage für amtliche Kartenwerke und Vermessungen in Österreich, wurde jedoch inzwischen durch das UTM-Koordinatensystem mit dem Referenzrahmen ETRS89 ersetzt, das eine europaweit einheitliche Georeferenzierung ermöglicht. Aufgrund des Vertriebs des excav PILOT in Österreich findet das Koordinatensystem Gauss-Krüger (AT) ebenfalls Verwendung als Option i der App.


!!! info "Geodätisches Koordinatensystem (Geodetic)"

Das geodätische Koordinatensystem beschreibt die Lage von Punkten auf der Erdoberfläche anhand geografischer Breite, geografischer Länge und Höhe über einem Referenzellipsoid. Es basiert auf einem Referenzsystem, das die Form und Orientierung des Erdellipsoids festlegt. Solche Systeme ermöglichen eine präzise, einheitliche Positionsbestimmung auf der Erde.

<br>

### Georeferenzsysteme

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände aktuell (11) - Kopie.jpg"/>
</p>

Ein geodätisches Referenzsystem dient der eindeutigen Lagebestimmung von Punkten auf der Erdoberfläche. Es definiert, wie geografische Koordinaten (Breite, Länge und Höhe) auf ein mathematisches Erdmodell, meist ein Referenzellipsoid, bezogen werden und somit einem festen Bezugssystem zur Erde. Das Europäische Terrestrische Referenzsystem 1989 (ETRS89) zum Beispiel ist das offizielle geodätische Referenzsystem für Europa. Es ist in diesem Fall an die eurasische Kontinentalplatte gebunden und bleibt somit im europäischen Raum stabil, wodurch präzise und zeitlich konsistente Lageangaben innerhalb von Europa gewährleistet sind.


Weiteres Beispiel: UTM32-GRS80-Ellipsoid für UTM (global)

Das UTM32-GRS80-Ellipsoid kombiniert das UTM-Koordinatensystem (Zone 32) mit dem GRS80-Ellipsoid als Referenzmodell der Erde. Es wird verwendet, um Punkte innerhalb dieser Zone präzise zu positionieren, wobei Breite, Länge und Höhe auf dem GRS80-Ellipsoid basieren.


Weiteres Beispiel: GK2(De)-Bessel1841-Ellipsoid für Gauss-Krüger (DE)

Das Bessel1841-Ellipsoid ist ein historisches Erdmodell und beschreibt die Erdform als Rotationsellipsoid. In Deutschland diente es als Grundlage des Gauß-Krüger-Koordinatensystems (GK2 bzw. GK-System), das für topografische Karten und Vermessungen verwendet wurde.


Weitere spezifische Georeferenzsysteme (in Abhängigkeit von europa- und weltweit anerkannten und angewandten Koordinatensystemen wie UTM) werden schrittweise in der App implementiert.

<br>

### Formate

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände aktuell (16) - Kopie.jpg"/>
</p>

Die Formate Northing, Easting, Altitude (NEA) oder Easting, Northing, Altitude (ENA) beschreiben die Koordinaten in einem kartesischen oder projektiven Georeferenzsystem:

**Easting** (Ostwert): Abstand eines Punktes in Ost-Richtung von einem definierten Bezugspunkt oder Meridian.

**Northing** (Nordwert): Abstand eines Punktes in Nord-Richtung von einem definierten Bezugspunkt oder Äquator.

**Altitude** (Höhe): Vertikale Höhe eines Punktes über einem Referenzniveau, z. B. dem Meeresspiegel oder einem Referenzellipsoid.

Die Reihenfolge Northing, Easting, Altitude (NEA) oder Easting, Northing, Altitude (ENA) hängt vom verwendeten Koordinatensystem ab, beeinflusst aber nicht die Lage des Punktes.


Im Folgenden werden alle zu den Koordinatensystemen dazugehörigen Georeferenzsysteme einzeln inklusive der verfügbaren Auswahloption für die Formate NEA und ENA aufgezählt.

<br>

#### Georeferenzsysteme für Universal Transverse Mercator (global)

**UTM32-GRS80-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

**UTM33-GRS80-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

**UTM34-GRS80-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

**UTM32-GRS80-GCG16** | Formate: Northing Easting Altitude / Easting Northing Altitude

**UTM33-GRS80-GCG16** | Formate: Northing Easting Altitude / Easting Northing Altitude

**UTM34-GRS80-GCG16** | Formate: Northing Easting Altitude / Easting Northing Altitude

**UTM32-GRS80-EGG15** | Formate: Northing Easting Altitude / Easting Northing Altitude

**UTM33-GRS80-EGG15** | Formate: Northing Easting Altitude / Easting Northing Altitude

**UTM34-GRS80-EGG15** | Formate: Northing Easting Altitude / Easting Northing Altitude

<br>

#### Georeferenzsysteme für Gauss-Krüger (Deutschland)

**GK2(De)-Bessel1841-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

**GK3(De)-Bessel1841-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

**GK4(De)-Bessel1841-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

**GK5(De)-Bessel1841-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

<br>

#### Georeferenzsysteme für Gauss-Krüger (Österreich)

**GKM28(At)-Bessel1841-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

**GKM31(At)-Bessel1841-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

**GKM34(At)-Bessel1841-Ellipsoid** | Formate: Northing Easting Altitude / Easting Northing Altitude

<br>

#### Georeferenzsysteme für Geodätisches Koordinatensystem (Geodetic)

**Geodetic-GRS80-Ellipsoid** | kein weiteres Format erforderlich (keine Auswahloption möglich)



<!-- [//]: #

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz Gelände.jpg"/>
</p>

Unter dem Menüpunkt „Gelände“ erhalten Sie die Möglichkeit eingelesene dreidimensionale Geländemodelle im gewünscht Dateiformat zu laden, einzusehen oder auch ggf. wieder zu löschen.

## Arbeitsplatz als LandXML

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 3.jpg"/>
</p>

Um einen neuen Arbeitsplatz speziell im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf das Tablet hochladen und lokal ablegen. Wenn Sie die Funktion Gelände auswählen, werden Sie gebeten über "+ XML importieren" eine LandXML-Datei vom Tablet auszuwählen. Als Nächstes müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Geo-Referenz- und Höhen-Referenzsystem machen, die Sie im Vorfeld vom Planungs- oder Ingenieuerbüro erhalten.

Über Art und Umfang der erforderlichen Angaben entscheidet maßgeblich die Wahl des Geo-Referenzsystems. Sollten die eingegebenen Daten oder Einstellungen sowie die Beschaffenheit der LandXML-Datei nicht miteinander übereinstimmen, wird automatisch eine Fehlermeldung ausgelöst. 


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

Punkte oder Punktewolken in LandXML-Dateien sind zwar absolut als reale Punkte auf der Erde referenziert, doch es können etwaige Fehler und Abweichungen auftreten, wodurch Abweichungen zwischen den vordefinierten LandXML-Punkten und realen Punkten später mittels des Messstabs auf der Baustelle möglich sind. Über die Funktion XML kalibrieren können Sie bestimmen, dass reale Punkte auf der Baustelle genutzt werden, um die Bauplanansicht der LandXML-Datei daran auszurichten. Der Punkt bzw. die Punkte innerhalb der LandXML-Datei werden um die Differenz entsprechend verschoben. Wählen Sie mindestens einen Punkt aus, damit dieser mit einem eingemessenen Punkt der Wahl in Übereinstimmung gebracht wird.   

Beachten Sie den Hinweis, dass ungespeicherte Änderungen verloren können. Vergeben Sie dem neuen Arbeitsplatz unter „Bezeichnung“ einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“. Wählen Sie im Anschluss die gewünschte LandXML-Datei aus, die zuvor auf das Tablet hochgeladen worden ist. -->