<style>
    setCenter{
        justify-content: center;
    }
</style>

# Punkte

Punkte sind das grundlegende Designobjekt in der App. Mit Punkten können Sie alle weiteren Designobjekte wie z.B Linien, Polylinien, Kreise, Flächen oder eine Baugraube modellieren. 

Alle bereits aufgenommenen Punkte finden Sie abgespeichert in der Punkteliste unter "Punkte" im Designmenü. 

## Punkteliste

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (71) - Kopie.png"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Auge-Button** | Zum Einblenden und Ausblenden des jeweiligen Punktes in der [Arbeitsansicht]().

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Löschen-Button** | Punkt aus der Punkteliste löschen. Achtung: Nicht wiederherstellbar! Wenn Sie den Punkt möglicherweise später noch mal benötigen, dann besser nur ausblenden.  

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Punkt bearbeiten** | Durch Tippen auf den Punkt können Sie diesen bearbeiten, z.B. die Farbgebung, Bezeichnung oder ihn in der Höhe verschieben. Unter der Punktbezeichnung werden Ihnen alle Informationen zum Punkt in Echtzeit ausgegeben, welche Sie in den Punkt-Einstellungen (siehe **<span style="color: red; font-weight: bold;">4</span>**) aktiv gesetzt haben. 

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Punkt-Einstellungen** | Öffnet das Einstellungs-Fenster. Hier können Sie auswählen, welche Informationen zu den Punkten in Ihrer Punkteliste angezeigt werden sollen. 


## Punkt-Einstellungen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (72) - Kopie.png"/>
</p>

Welche Informationen zu den jeweiligen Punkten sollen in der Punkteliste angezeigt werden?

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Horizontale Position** | x-Koordinate und y-Koordinate des Punktes im aktiven Koordinatensystem

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Distanz in (X,Y)** | x-Abstand und y-Abstand separat ausgegeben zwischen dem Punkt und der aktuellen Position

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Entfernung horizontal** | horizontaler Abstand zwischen dem Punkt und der aktuellen Position; nur x-Wert und y-Wert werden berücksichtigt 

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Entfernung vertikal** | Höhendifferenz zwischen dem Punkt und der aktuellen Position; nur der z-Wert wird berücksichtigt


## GNSS-Punkt

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (30) - Kopie.png"/>
</p>

Bei Bestätigung mit "OK" wird die aktuelle Position der aktiven Werkzeugecke (beim Messstab die Position der Spitze) als Punkt erfasst und in der Punkteliste abgespeichert.


## Manueller Punkt

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (31) - Kopie.png"/>
</p>

Sie können Punkte auch manuell erfassen, indem Sie das entsprechende Referenzsystem auswählen und die Koordinaten für Ihren Punkt eingeben. Vermessungen werden in Deutschland üblicherweise in UTM32/ETRS89 durchgeführt. 

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> UTM** | Universal Transverse Mercator - 2D-projeziertes, zonenspezifisches Koordinatensystem mit Rechtswert (Easting) und Hochwert (Northing) in Metern, aufgeteilt in 60 Zonen mit je 6° Breite. Deutschland liegt in Zone 32, ggf. Zone 33 im Osten. Achtung: nur genau, wenn innerhalb der angegebenen Zone! Bezugssystem in Europa: ETRS89

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> ECEF** | Earth-Centered, Earth-Fixed - 3D-kartesisches erdfestes Koordinatensystem mit (x,y,z)-Koordinaten in Metern, Ursprung im Erdmittelpunkt; x-Achse Schnittpunkt Äquator/Greenwich Meridian, y-Achse 90° östlich davon, z-Achse Nordpol. Bezugssystem in Europa: ETRS89  

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Lat/Long** | geografisches Kugel-/Ellipsoid-basiertes Koordinatensystem mit Breite (Latitude, φ) als Nord-/Südwinkel vom Äquator und Länge (Longitude, λ) als Ost-/Westwinkel vom Nullmeridian (Greenwich), Achtung: Winkel in der App bitte als Dezimalzahlen eingeben. Bezugssystem in Europa: ETRS89

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Local** | Hier können Sie eines Ihrer lokal angelegten [Koordinatensysteme]() auswählen.

!!! info "Schnelltaste zum Punkte erfassen"
    Seitlich rechts in der Arbeitsansicht befindet sich eine Schnelltaste zum Aufnehmen von Punkten (dritter oranger Button von unten). 

<!-- BACKLOG

Das Definieren und Setzen von Messpunkten zuzüglich zum Referenzpunkt auf der Baustelle ist eine der wichtigsten Funktionen und als Grundlage essenziell für höhere Funktionen, wie das Erstellen von Linien, Geraden, Flächen, Ebenen und geometrischen Formen, wie für Baugruben. Durch den mitgelieferten GNSS-Sensor, den zerlegbaren Messstab und eine Tablethalterung können Nutzer einfach und schnell beliebig viele Punkte erstellen und auflisten.

Unter dem Menüpunkt „Punkt“ erhalten Sie die Möglichkeit, den aktuellen Referenzpunkt unter Angabe präziser Entfernungswerte einzusehen sowie neue Punkte per GNSS oder manuell per Eingabe zu hinterlegen und in der Punkteliste zu speichern. Unter Einstellungen (Zahnradsymbol rechts oben) haben Sie die Möglichkeit, die Informationen zu Entfernungswerten darstellen zu lassen oder bei Bedarf auszublenden. Die Funktionen werden im Folgenden näher beschrieben.
Normale Punkte können, anders als der Referenzpunkt, nachträglich bearbeitet und geändert werden. Zudem lässt sich die Farbe der Punkte für bessere Übersichtlichkeit ebenfalls ändern.


## Punkte erfassen

Mit dieser Funktion können Sie neue Punkte auf der Baustelle erfassen und in einer Punkteliste gezielt abspeichern. Montieren Sie hierfür den Sensor auf dem Messstab oder bewegen Sie alternativ die ausgewählte Ecke der Baggerschaufel oder des Werkzeugs auf den vorgesehenen Punkt im Raum und speichern Sie diesen in einem der Punkte-Slots (A, B, C, …) ab. Aus der Punkteliste können Sie im Folgenden Punkte auswählen, mit Hilfe derer Sie Strecken, Flächen und sogar Polyeder erschaffen können (z.B. Fläche durch drei Punkte ziehen). Die Punkte können neben dem Referenzpunkt als visuelle Orientierung auf der Baustelle dienen.

!!! information "Information"

Benötigen Sie eine reine Höhenreferenz, bietet es sich an die Mitte der Baggerschaufel oder des Werkzeugs zum Erfassen der Punkte zu benutzen. Möchten Sie die Punkte möglichst genau bestimmen, empfehlen wir den Messstab zu benutzen, da dieser präzisere Arbeiten ermöglicht.


## Punkte löschen

Sollten Sie einen oder mehrere der bereits abgespeicherten Punkte für künftige Bauarbeiten nicht mehr benötigen, können Sie diese(n) wieder aus Ihrer Punkteliste löschen. Wählen Sie hierzu den zugehörigen Punkt-Slot aus und bestätigen Sie den Löschvorgang mit "Ja". 

BACKLOG -->