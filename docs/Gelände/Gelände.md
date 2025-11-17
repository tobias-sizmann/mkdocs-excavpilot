<style>
    setCenter{
        justify-content: center;
    }
</style>

# Gelände

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände (19).jpg"/>
</p>

Das Einlesen und die Nutzung von Digitalen Geländemodellen (DGM) im LandXML-Format für eine vollständig in 3D visualisierte Arbeitsweise auf der Baustelle ist eine der Hauptfunktionen der excav App-Anwendung. Nutzer können sich jederzeit entscheiden, ob sie Baupläne als PDF in der zweidimensionalen Ansicht oder mithilfe von DGM im LandXML-Format im dreidimensionalen Raum für ein intuitives und immersives Arbeitserlebnis verwenden möchten. 


!!! Warning "Richtige Einstellungen für LandXML"
    LandXML ist ein Dateiformat zum Austausch georeferenzierter Objekte zwischen Softwareprogrammen. Es ermöglicht die Übermittlung von Objekten mit Attributen, Distanzrelationen und Geometrien zwischen Endgeräten, insbesondere für Anwendungen im Tiefbau, Straßenbau oder im Garten- und Landschaftsbau.
    
    Um die LandXML-Datei in der excav PILOT App richtig darzustellen, muss bekannt sein, mit welchen Einstellungen im Hinblick auf das Koordinatensystem, das Georeferenzsystem und das Format der LandXML-Datei im CAD-Programm gearbeitet wurde. Nur so lassen sich Fehler in der Darstellung oder Fehlermeldungen vermeiden. 

    
!!! info "Inhalte be Georeferenzierung"
    Da die Vermessungsdaten georeferenziert sind, erscheinen die Inhalte der Datei nur dann auf dem Bildschirm des Tablets, wenn sich der Nutzer mit dem GNSS-Sensor innerhalb des entsprechenden referenzierten Areals befindet.


!!! info "Bezug von geodätischen Plänen"
    Sie erhalten georeferenzierte Baupläne als LandXML oder in vergleichbaren Dateiformaten typischerweise von einem Ingenieurs- oder Planungsbüro sowie ggf. intern von einem fachkundigen Spezialisten. Von diesen erhalten Sie die notwendigen Informationen zum Koordinatensystem, Georeferenzsystem und Format, um die Datei korrekt darzustellen. 


## Import eines digitalen Geländemodells

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot Gelände (1) - Kopie.jpg"/>
</p>

Um einen neuen Arbeitsplatz speziell im Dateiformat LandXML in der App anzulegen, haben Sie zwei Möglichkeiten: Entweder laden Sie in einem bestehenden Arbeitsplatz eine LandXML-Datei hoch oder Sie erstellen einen neuen Arbeitsplatz mithilfe einer LandXML-Datei. 

Im ersten Schritt müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei auf das Tablet hochladen und dort lokal ablegen. Wenn Sie in einem bestehenden Arbeitsplatz eine LandXML-Datei einladen und die Funktion Gelände im Designmenü auswählen, werden Sie gebeten, über „+ XML importieren“ eine Datei aus dem lokalen Speicher des Tablets auszuwählen. 


## Koordinaten- und Georeferenzsysteme

### Koordinatensysteme

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Gelände Auswahl (1).png"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Koordinatensystem** | Wählen Sie hier das zugrunde liegende Koordinatensystem aus. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Georeferenzsystem** | Wählen Sie hier ein geeignetes Georeferenzsystem aus.  

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Format** | Wählen Sie hier das erforderliche Format für die LandXML-Datei aus. 


Ein Koordinatensystem ist ein länderspezifisches oder weltweit einheitliches Bezugssystem zur Bestimmung von Positionen auf der Erdoberfläche. Es basiert auf dem Modell eines Erdellipsoids, das die Form der Erde mathematisch beschreibt, und definiert Breiten- und Längengrade als Koordinaten. Hierdurch lassen sich Orte und einzelne Punkte auf der Erdoberfläche eindeutig durch geografische Breite (engl. latitude) und geografische Länge (engl. longitude) angeben.


!!! info "Koordinatensystem Universal Transverse Mercator (UTM)"
    Das UTM-Koordinatensystem ist ein weltweit einheitliches, rechtwinkliges Koordinatensystem zur genauen Positionsbestimmung. Es basiert auf einer Einteilung des Erdellipsoids in 60 Meridianzonen, die jeweils 6° breit sind und durch eine transversale Mercatorprojektion dargestellt werden. Jede Zone besitzt ein eigenes Koordinatennetz mit Ost- (Rechtswert) und Nordwert (Hochwert) in Metern, wodurch Entfernungen direkt messbar sind. Das UTM-System wird häufig in topografischen Karten, GPS-Geräten und geografischen Informationssystemen (GIS) verwendet, da es präzise, metrisch und weltweit standardisiert ist. In Deutschland wird überwiegend das auf dem ETRS89-Referenzellipsoid basierende UTM-System genutzt. 


!!! info "Koordinatensystem Gauss-Krüger (DE)"
    Das Gauss-Krüger-Koordinatensystem ist ein in Deutschland traditionell verwendetes rechtwinkliges Abbildungssystem, das auf der transversalen Mercatorprojektion basiert. Die Erdoberfläche wird in 3° breite Meridianstreifen unterteilt, in denen Positionen durch Rechtswerte (Ostwerte) und Hochwerte (Nordwerte) in Metern angegeben werden. Grundlage ist mehrheitlich das Bessel-Ellipsoid und das Datum Potsdam (DHDN). Es wird heute weiterhin neben dem zunehmend häufiger genutzten UTM-Koordinatensystem eingesetzt.

    Alle UTM-Zonen in Deutschland (WGS84 / ETRS89): 

    - UTM-Zone 31
    - UTM-Zone 32
    - UTM-Zone 33


!!! info "Koordinatensystem Gauss-Krüger (AT)"
    Das Gauss-Krüger-Koordinatensystem (AT) ist dasamtliche Koordinatensystem Österreichs, das auf der transversalen Mercatorprojektion basiert. Als Bezugsellipsoid dient das Bessel-Ellipsoid, und als geodätisches Datum wurde das MGI (Militärgeografisches Institut) verwendet.

    Alle UTM-Zonen in Österreich (WGS84 / ETRS89): 

    - UTM-Zone 32
    - UTM-Zone 33


!!! info "Krovak (North Oriented) (für Tschechien)"
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

Ein geodätisches Referenzsystem dient der eindeutigen Lagebestimmung von Punkten auf der Erdoberfläche. Es definiert, wie geografische Koordinaten (Breite, Länge, Höhe) auf ein mathematisches Erdmodell – meist ein Referenzellipsoid – bezogen werden. So entsteht ein festes Bezugssystem. Das Europäische Terrestrische Referenzsystem 1989 (ETRS89) ist beispielsweise das offizielle geodätische Referenzsystem für Europa. Es ist an die eurasische Kontinentalplatte gebunden und daher im europäischen Raum stabil, wodurch präzise und zeitlich konsistente Lageangaben gewährleistet sind.

Beispiele:

– UTM32-GRS80-Ellipsoid für UTM (global) 
<br>
– GK2(De)-Bessel1841-Ellipsoid für Gauss-Krüger (Deutschland)


<br>

### Formate

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Gelände Auswahl (3).png"/>
</p>

Die Formate Northing, Easting, Altitude (NEA) und Easting, Northing, Altitude (ENA) beschreiben die Koordinaten in einem kartesischen oder projektiven Georeferenzsystem:

**Easting** (Ostwert): Abstand eines Punktes nach Osten

**Northing** (Nordwert): Abstand eines Punktes nach Norden

**Altitude** (Höhe): Vertikale Höhe über Referenzniveau

Die Reihenfolge (NEA oder ENA) hängt vom Koordinatensystem ab, verändert jedoch nicht die tatsächliche Lage eines Punktes.

Im Folgenden werden alle zu den Koordinatensystemen gehörenden Georeferenzsysteme inklusive der verfügbaren Formatoptionen aufgeführt.


<br>

#### Georeferenzsysteme für UTM (global)

Georeferenzsysteme für UTM (global)

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

Geodetic-GRS80-Ellipsoid | kein weiteres Format erforderlich (keine Auswahloption möglich)


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