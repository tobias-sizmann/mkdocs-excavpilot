<style>
    setCenter{
        justify-content: center;
    }
</style>

# Geländemodelle (LandXML)

Der excav Pilot ermöglicht das Laden und Anzeigen digitaler Geländemodelle direkt auf dem Bagger. Der Fahrer bekommt sowohl das 3D-Gelände als auch seine aktuelle Position im Modell visualisiert.
Für den 3D-Import wird derzeit ausschließlich das LandXML-Format unterstützt.

LandXML ist ein offener XML-basierter Standard zur Beschreibung vermessungstechnischer Daten (georeferenzierte Geländemodelle, Oberflächen, Linien, Korridore, Punkte, usw.). Unterstützte Inhalte sind derzeit:

- Surfaces (Geländeoberflächen)
- Lines / Breaklines / Curves (z. B. Böschungskanten, Achsen)
- Points (CgPoint)

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände (19).jpg"/>
</p>

!!! info "Wie bekomme ich LandXML-Dateien auf das Tablet?"

    Es gibt mehrere Möglichkeiten, Dateien auf das Android-Tablet zu bekommen:

       - USB / Direktübertragung ( USB-Stick, Laptop, …)
       - Cloud Dienste mit Android App (Google Drive, OneDrive, Dropbox, …)
       - Download über Browser (Chrome)
       - E-Mailprogramm (GMail, Outlook, …)
       - Bluetooth

## Import von XML-Dateien

Es gibt zwei Möglichkeiten eine XML-Datei vom Tablet in die excav PILOT App zu importieren. Wenn Sie noch keinen [Arbeitsplatz](https://docs.excav.de/Arbeitsplatz/Arbeitsplatz/) für dieses Modell haben, können Sie beim Erstellen des neuen Arbeitsplatzes direkt das XML laden. Falls Sie bereits einen Arbeitsplatz für die Baustelle haben, können Sie ein Modell über das [Designmenü -> Gelände]() hinzufügen.

In beiden Fällen müssen danach drei Parameter gesetzt werden:

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Gelände Auswahl (1).png"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span>** Koordinatensystem (Projection)

- Universal Transverse Mercator (UTM)

        gängige Zone in Deutschland: UTM-32, im Osten ggf. UTM-33

- Gauss-Krüger (GK) 

        gängige Zone in Deutschland: Zone 3, im Westen häufiger Zone 2, im Osten Zone 4 und selten 5

- GROVAC (Tschechien)
- Geodätisch (Breite/Länge)

!!! info 
    Je nach dem, welche Korrekturdatenquelle/-dienst genutzt wird, muss dies berücksichtigt werden. SAPOS arbeitet z.B. im ETRS89.

**<span style="color: red; font-weight: bold;">2: &nbsp;</span>** CRS (Coordinate Reference System)

Hier ist die entsprechende Pipeline auszuwählen, mit der das Modell erstellt wurde. Sollte die benötigte Pipline hier nicht vorhanden sein, wenden Sie sich bitte an uns!

!!! info
    Wenn z.B. in Deutschland mit einem Modell mit SAPOS in UTM gearbeitet wird, ist hier die entsprechende Zone (z.B. UTM32, UTM33, UTM34, …) mit dem Raumbezugssystem (z.B. GRS80, WGS84, …) und dem Ellipsoid / Geoidmodell (z.B.GCG16, …) auszuwählen. In Deutschland wird in den allermeisten Fällen 

**<span style="color: red; font-weight: bold;">3: &nbsp;</span>** Format

Hier ist die Reihenfolge anzugeben, in der die Daten in der XML-Datei aufgelistet sind. Der erste Wert aus der Datei wird entsprechend oberhalb des Projektions-Feldes angezeigt. Hierbei spielt es bei UTM keine Rolle, ob das Kurz- oder Langformat genutzt wird. Northing entspricht dem Hochwert, Easting dem Rechtswert und Altitude der Höhe.

!!! info
    Der Rechtswert (East/E) gibt die Entfernung vom Mittelmeridian einer UTM-Zone nach Osten (positiv) oder Westen (negativ, aber mit 500.000 m Offset, um immer positive Werte zu haben) an und wird in Metern gemessen, während der Hochwert (North/N) die Entfernung vom Äquator nach Norden in Metern angibt. In Deutschland ist die Unterscheidung einfach, da der Hochwert 7-stellig ist. Der Rechtswert kann 6 oder 8-stellig sein, je nachdem, ob die Zone (32, 33, …) vorne an den Rechtswert angehängt ist oder nicht.

## Nachjustierung über CgPoints

Sofern in dem Modell CgPoints hinterlegt sind und diese einen bekannten Bezug zu vorliegenden Punkten auf der Baustelle, kann das Modell anhand beliebig vieler CgPoints nochmals eingemessen werden. Das Modell wird hiermit aber nur verschoben und nicht rotiert oder skaliert. Anhand der errechneten Residuen kann die Einmessung kontrolliert werden.

## Häufige Fragen

!!! question "Ich habe mein Geländemodell auf das Tablet übertragen, finde es aber beim Import nicht."
    Tippen Sie oben links auf das Hamburger-Menü (die drei horizontalen Linien) und navigieren Sie anschließend zu dem Ordner, in dem Sie die Datei gespeichert haben. 

!!! question "Mein LandXML ist nach dem Import nicht sichtbar."
    Das LandXML ist georeferenziert. Wenn Ihre aktuelle Sensorposition weit von den Koordinaten der Datei entfernt ist, wird das Modell nicht im sichtbaren Bereich angezeigt. Klicken Sie auf den "Karte zentrieren"-Button (seitlich rechts in der Ansicht, dritter von oben), um zum Ursprung des Geländemodells zu springen.

!!! question "Mein LandXML enthält keine Höhen."
    Die .xml-Datei muss TIN surfaces enthalten. CoordGeom-Inhalte wie z.B. Lines oder Curves sind lediglich grafische Geometrien. Höheninformationen eingeschlossener Flächen werden nicht berechnet. Wenden Sie sich ggf. an den zuständigen Software-Berater Ihres CAD-Programms und beschreiben Sie, dass Sie mit einer Punktwolke eine Oberfläche als trianguliertes Netz erzeugen möchten.

!!! question "Funktionieren auch andere Dateiformate wie DXF oder DWG?"
    Nein, aktuell unterstützen wir nur LandXML. Längerfristig soll auch DXF unterstützt werden. Die meisten CAD-Programme, die Ihnen ein DXF erzeugen können, unterstützen auch LandXML.

<!-- Das Einlesen und die Nutzung von Digitalen Geländemodellen (DGM) im LandXML-Format für eine vollständig in 3D visualisierte Arbeitsweise auf der Baustelle ist eine der Hauptfunktionen der excav App-Anwendung. Nutzer können sich jederzeit entscheiden, ob sie Baupläne als PDF in der zweidimensionalen Ansicht oder mithilfe von DGM im LandXML-Format im dreidimensionalen Raum für ein intuitives und immersives Arbeitserlebnis verwenden möchten. 

!!! Warning "Richtige Einstellungen für LandXML"
    LandXML ist ein gängiges Dateiformat zum Austausch georeferenzierter Objekte zwischen Softwareprogrammen. Es ermöglicht die Übermittlung von Objekten mit Attributen, Distanzrelationen und Geometrien zwischen Endgeräten, insbesondere für Anwendungen im Tiefbau, Straßenbau oder im Garten- und Landschaftsbau.
    
    Um die LandXML-Datei in der excav PILOT App richtig darzustellen, muss bekannt sein, mit welchen Einstellungen im Hinblick auf das Koordinatensystem, das Georeferenzsystem und das Format der LandXML-Datei im CAD-Programm gearbeitet wurde. Nur so lassen sich Fehler in der Darstellung oder Fehlermeldungen vermeiden. 
  
!!! info "Inhalte bei Georeferenzierung"
    Da die Vermessungsdaten georeferenziert sind, erscheinen die Inhalte der Datei nur dann auf dem Bildschirm des Tablets, wenn sich der Nutzer mit dem GNSS-Sensor innerhalb des entsprechenden referenzierten Areals befindet.

!!! info "Bezug von geodätischen Plänen"
    Sie erhalten georeferenzierte Baupläne als LandXML oder in vergleichbaren Dateiformaten typischerweise von einem Ingenieurs- oder Planungsbüro sowie ggf. intern von einem Spezialisten. Von diesen erhalten Sie die notwendigen Informationen zum Koordinatensystem, Georeferenzsystem und Format, um die LandXML-Datei korrekt darzustellen. 


## Import eines digitalen Geländemodells

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände (1) - Kopie.jpg"/>
</p>

Um einen neuen Arbeitsplatz speziell im Dateiformat LandXML in der App anzulegen, haben Sie grundsätzlich zwei Möglichkeiten: Entweder laden Sie in einem bestehenden Arbeitsplatz eine LandXML-Datei hoch oder Sie erstellen einen neuen Arbeitsplatz mithilfe einer LandXML-Datei. 

Im ersten Schritt müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei auf das Tablet hochladen und dort lokal ablegen. Wenn Sie in einem bestehenden Arbeitsplatz eine LandXML-Datei einladen und die Funktion Gelände im Designmenü auswählen, werden Sie gebeten, über „+ XML importieren“ eine Datei aus dem lokalen Speicher auszuwählen. 


## Koordinaten- und Georeferenzsysteme

### Koordinatensysteme

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Gelände Auswahl (1).png"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Koordinatensystem** | Wählen Sie hier das zugrunde liegende Koordinatensystem aus. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Georeferenzsystem** | Wählen Sie hier ein geeignetes Georeferenzsystem aus.  

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Format** | Wählen Sie hier das erforderliche Format für die LandXML-Datei aus. 

Ein Koordinatensystem ist ein länderspezifisches oder weltweit einheitliches Bezugssystem zur Bestimmung von Positionen auf der Erdoberfläche. Es basiert auf dem Modell eines Erdellipsoids, das die Form der Erde mathematisch beschreibt, und definiert Breiten- und Längengrade als Koordinaten. Hierdurch lassen sich Orte auf der Erdoberfläche eindeutig durch geografische Breite (engl. latitude) und geografische Länge (engl. longitude) angeben.

!!! info "Koordinatensystem Universal Transverse Mercator (UTM)"
    Das UTM-Koordinatensystem ist ein weltweit einheitliches, rechtwinkliges Koordinatensystem zur genauen Positionsbestimmung. Es basiert auf einer Einteilung des Erdellipsoids in 60 Meridianzonen, die jeweils 6° breit sind und durch eine transversale Mercatorprojektion dargestellt werden. Jede Zone besitzt ein eigenes Koordinatennetz mit Ost- (Rechtswert) und Nordwert (Hochwert) in Metern, wodurch Entfernungen direkt messbar sind. Das UTM-System wird häufig in topografischen Karten, GPS-Geräten und geografischen Informationssystemen (GIS) verwendet, da es präzise, metrisch und weltweit standardisiert ist. In Deutschland wird überwiegend das auf dem ETRS89-Referenzellipsoid basierende UTM-System genutzt. 

!!! info "Koordinatensystem Gauss-Krüger (DE)"
    Das Gauss-Krüger-Koordinatensystem ist ein in Deutschland traditionell verwendetes rechtwinkliges Abbildungssystem, das auf der transversalen Mercatorprojektion basiert. Die Erdoberfläche wird in 3° breite Meridianstreifen unterteilt, in denen Positionen durch Rechtswerte (Ostwerte) und Hochwerte (Nordwerte) in Metern angegeben werden. Grundlage ist mehrheitlich das Bessel-Ellipsoid und das Datum Potsdam (DHDN). Es wird heute weiterhin neben dem zunehmend häufiger genutzten UTM-Koordinatensystem eingesetzt.

    Alle UTM-Zonen in Deutschland (WGS84 / ETRS89): 

    - UTM-Zone 31
    - UTM-Zone 32
    - UTM-Zone 33

!!! info "Koordinatensystem Gauss-Krüger (AT)"
    Das Gauss-Krüger-Koordinatensystem (AT) ist das amtliche Koordinatensystem Österreichs, das auf der transversalen Mercatorprojektion basiert. Als Bezugsellipsoid dient das Bessel-Ellipsoid, und als geodätisches Datum wurde das MGI (Militärgeografisches Institut) verwendet.

    Alle UTM-Zonen in Österreich (WGS84 / ETRS89): 

    - UTM-Zone 32
    - UTM-Zone 33

!!! info "Krovak (North Oriented) - Tschechien"
    Das Krovak-Koordinatensystem ist eine speziell für Tschechien entwickelte, schiefachsige konforme Kegelprojektion, die die Landesfläche möglichst verzerrungsarm abbildet. Es basiert traditionell auf dem Bessel-Ellipsoid und wird weiterhin neben dem zunehmend verbreiteten UTM-System genutzt.

    Alle UTM-Zonen in Tschechien (WGS84 / ETRS89): 

    - UTM-Zone 33
    - UTM-Zone 34

!!! info "Geodätisches Koordinatensystem (Geodetic)"
    Das geodätische Koordinatensystem beschreibt die Lage von Punkten auf der Erdoberfläche anhand geografischer Breite, geografischer Länge und Höhe über einem Referenzellipsoid. Es basiert auf einem Referenzsystem, das die Form und Orientierung des Erdellipsoids festlegt und ermöglicht eine präzise, einheitliche Positionsbestimmung.

<br>

### Georeferenzsysteme

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Gelände Auswahl (2).png"/>
</p>

Ein geodätisches Referenzsystem dient der eindeutigen Lagebestimmung von Punkten auf der Erdoberfläche. Es definiert, wie geografische Koordinaten (Breite, Länge, Höhe) auf ein mathematisches Erdmodell – meist ein Referenzellipsoid – bezogen werden. So entsteht ein festes Bezugssystem, wie beispielsweise das Europäische Terrestrische Referenzsystem 1989 (ETRS89) als das offizielle geodätische Referenzsystem für Europa. Es ist an die eurasische Kontinentalplatte gebunden und daher im europäischen Raum stabil, wodurch präzise und zeitlich konsistente Lageangaben gewährleistet sind.

Zwei mögliche Beispiele sind UTM32-GRS80-Ellipsoid für UTM (global) oder GK2(De)-Bessel1841-Ellipsoid für Gauss-Krüger (Deutschland). 

<br>

### Formate

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Gelände Auswahl (3).png"/>
</p>

Die Formate Northing, Easting, Altitude (NEA) und Easting, Northing, Altitude (ENA) beschreiben die Koordinaten in einem kartesischen oder projektiven Georeferenzsystem:

**Easting** (Ostwert): Abstand eines Punktes nach Osten

**Northing** (Nordwert): Abstand eines Punktes nach Norden

**Altitude** (Höhe): Vertikale Höhe über Referenzniveau

Die Reihenfolge (NEA oder ENA) hängt vom Koordinatensystem ab, verändert jedoch nicht die tatsächliche Lage eines Punktes. Im Folgenden werden alle zu den Koordinatensystemen gehörenden Georeferenzsysteme inklusive der verfügbaren Formatoptionen aufgeführt.

<br>

#### Georeferenzsysteme für UTM (global)

- UTM32-GRS80-Ellipsoid | Formate: NEA / ENA
- UTM33-GRS80-Ellipsoid | Formate: NEA / ENA
- UTM34-GRS80-Ellipsoid | Formate: NEA / ENA
- UTM32-GRS80-GCG16 | Formate: NEA / ENA
- UTM33-GRS80-GCG16 | Formate: NEA / ENA
- UTM34-GRS80-GCG16 | Formate: NEA / ENA
- UTM32-GRS80-EGG15 | Formate: NEA / ENA
- UTM33-GRS80-EGG15 | Formate: NEA / ENA
- UTM34-GRS80-EGG15 | Formate: NEA / ENA

<br>

#### Georeferenzsysteme für Gauss-Krüger (Deutschland)

- GK2(De)-Bessel1841-Ellipsoid | Formate: NEA / ENA
- GK3(De)-Bessel1841-Ellipsoid | Formate: NEA / ENA
- GK4(De)-Bessel1841-Ellipsoid | Formate: NEA / ENA
- GK5(De)-Bessel1841-Ellipsoid | Formate: NEA / ENA

<br>

#### Georeferenzsysteme für Gauss-Krüger (Österreich)

- GKM28(At)-Bessel1841-Ellipsoid | Formate: NEA / ENA
- GKM31(At)-Bessel1841-Ellipsoid | Formate: NEA / ENA
- GKM34(At)-Bessel1841-Ellipsoid | Formate: NEA / ENA

<br>

#### Krovak (North Oriented) – Tschechien

- KrovakN(Cz)-Bessel1841-Ellipsoid | Formate: NEA / ENA
- KrovakN(Cz)-Bessel1841-QGZU13 | Formate: NEA / ENA

<br>

#### Georeferenzsysteme für Geodätisches Koordinatensystem (Geodetic)

Geodetic-GRS80-Ellipsoid | kein Format erforderlich (keine Auswahloption möglich)

-->
<!-- BACKLOG

Unter dem Menüpunkt „Gelände“ erhalten Sie die Möglichkeit eingelesene dreidimensionale Geländemodelle im gewünscht Dateiformat zu laden, einzusehen oder auch ggf. wieder zu löschen.


## Arbeitsplatz als LandXML

Um einen neuen Arbeitsplatz speziell im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf das Tablet hochladen und lokal ablegen. Wenn Sie die Funktion Gelände auswählen, werden Sie gebeten über "+ XML importieren" eine LandXML-Datei vom Tablet auszuwählen. Als Nächstes müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Geo-Referenz- und Höhen-Referenzsystem machen, die Sie im Vorfeld vom Planungs- oder Ingenieuerbüro erhalten.

Über Art und Umfang der erforderlichen Angaben entscheidet maßgeblich die Wahl des Geo-Referenzsystems. Sollten die eingegebenen Daten oder Einstellungen sowie die Beschaffenheit der LandXML-Datei nicht miteinander übereinstimmen, wird automatisch eine Fehlermeldung ausgelöst. 


**Vorgang XML kalibrieren**

Punkte oder Punktewolken in LandXML-Dateien sind zwar absolut als reale Punkte auf der Erde referenziert, doch es können etwaige Fehler und Abweichungen auftreten, wodurch Abweichungen zwischen den vordefinierten LandXML-Punkten und realen Punkten später mittels des Messstabs auf der Baustelle möglich sind. Über die Funktion XML kalibrieren können Sie bestimmen, dass reale Punkte auf der Baustelle genutzt werden, um die Bauplanansicht der LandXML-Datei daran auszurichten. Der Punkt bzw. die Punkte innerhalb der LandXML-Datei werden um die Differenz entsprechend verschoben. Wählen Sie mindestens einen Punkt aus, damit dieser mit einem eingemessenen Punkt der Wahl in Übereinstimmung gebracht wird.   

Beachten Sie den Hinweis, dass ungespeicherte Änderungen verloren können. Vergeben Sie dem neuen Arbeitsplatz unter „Bezeichnung“ einen Namen und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“. Wählen Sie im Anschluss die gewünschte LandXML-Datei aus, die zuvor auf das Tablet hochgeladen worden ist. 

BACKLOG -->