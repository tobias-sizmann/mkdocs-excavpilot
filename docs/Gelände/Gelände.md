<style>
    setCenter{
        justify-content: center;
    }
</style>

# Gelände

[//]: # (Peter: Gelände überarbeitet / neuer Erklärung hier angelegt)

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz Gelände.jpg"/>
</p>

Unter dem Menüpunkt „Gelände“ erhalten Sie die Möglichkeit eingelesene dreidiemsionale Geländemodelle im gewünscht Dateienformat zu laden, einzusehen oder auch ggf. wieder zu löschen.

## Arbeitsplatz als LandXML

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 3.jpg"/>
</p>

m einen neuen Arbeitsplatz speziell im Format LandXML in der App anzulegen, müssen Sie einen vorhandenen Baustellenplan als LandXML-Datei zunächst auf das Tablet hochladen und lokal ablegen. Wenn Sie die Funktion Gelände auswählen, werden Sie gebeten über "+ XML importieren" eine LandXML-Datei vom Tablet auszuwählen. Als Nächstes müssen Sie exakte Angaben zu den XML-Metadaten der Datei für das Geo-Referenz- und Höhen-Referenzsystem machen, die Sie im Vorfeld vom Planungs- oder Ingenieuersbüro erhalten.

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
