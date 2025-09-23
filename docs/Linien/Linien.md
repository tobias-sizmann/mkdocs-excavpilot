<style>
    setCenter{
        justify-content: center;
    }
</style>

# Linien

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (87) - Kopie.jpg"/>
</p>

Mit Linien können Sie verschiedene Gegebenheiten Ihrer Baustelle direkt in der App selbst gestalten und darstellen – zum Beispiel, wenn sie keinen Bauplan oder kein Modell vorliegen haben. So lassen sich beispielsweise Baustellenbegrenzungen, Rohrleitungen oder Kanalwände einfach abbilden.

Um Linien zu erstellen, gehen Sie ins [Designmenü]() und wählen Sie "Linien" aus.

## Linien-Liste


<p align="center" width="100%">
  <img width="100%" src="/images_docs/Weitere Screenshots (1) - Kopie.png"/>
</p>


**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Auge-Button** | Zum Einblenden und Ausblenden der jeweiligen Linie in der [Arbeitsansicht]().

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Löschen-Button** | Linie aus der Linien-Liste löschen. Achtung: Nicht wiederherstellbar! Wenn Sie die Linie möglicherweise später noch mal benötigen, dann besser nur ausblenden.

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Linie bearbeiten** | Durch Tippen auf eine Linie können Sie diese bearbeiten, z.B. die Farbgebung oder Bezeichnung. Unter der Linienbezeichnung werden Ihnen alle Informationen zur Linie (z.B. Länge der Linie) ausgegeben, welche Sie in den Linien-Einstellungen (siehe **<span style="color: red; font-weight: bold;">4</span>**) aktiv gesetzt haben. 

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Linien-Einstellungen** | Öffnet das Einstellungs-Fenster. Hier können Sie auswählen, welche Informationen zu den Linien in Ihrer Linien-Liste angezeigt werden sollen. Je nach Linienart (Strecke, Unendliche Strecke, Polylinie, Polyeder) gibt es verschiedene Informationen zu Auswahl. 

## Neue Linie erstellen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (74) - Kopie 2.png"/>
</p>

Tippen Sie auf den Button "Neue Linie" unter der Linien-Liste.

Geben Sie der Linie Start- und Endpunkt indem Sie 

**<span style="color: red; font-weight: bold;">1: &nbsp;</span>** Den Punkt aus der Punkteliste auswählen

oder

**<span style="color: red; font-weight: bold;">2: &nbsp;</span>** Den Punkt direkt antasten, indem Sie die aktive Werkzeugecke (oder entsprechend die Spitze des Messstabes) auf die gewünschte Position setzen und den "Punkt erfassen" - Button drücken.

</br></br>

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Zusätzlicher Punkt** | Mit dem Plus-Button können Sie der Linie einen weiteren Punkt hinzufügen. 

!!! info "Wichtig"
    Die Reinfolge in der Sie die Punkte auswählen, bestimmt den Verlauf der Linie. Also P1 -> P2 -> P3 usw. 

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Unendliche Strecke /Polylinie schließen** | Bei einer Linie aus zwei Punkten kann die Strecke über beide Punkte hinaus unendlich verlängert werden, z.B. zum Darstellen einer Flucht. Bei einer Polylinie mit mehr als zwei Punkten haben Sie die Option die Polylinie zu schließen. Dabei wird der zuletzt gesetzte Punkt automatisch mit dem zuerst gewählten Punkt verbunden und Sie erhalten ein Polyeder. 

Jetzt noch mit "OK" bestätigen, dann wird die Linie in der Linien-Liste abgespeichert und in der [Arbeitsansicht]() angezeigt. 

## Linien-Einstellungen


<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (77) - Kopie.png"/>
</p>

Welche Informationen zu den jeweiligen Linen sollen in der Linien-Liste angezeigt werden? Je nach Linienart (Strecke, Polylinie, Polyeder) gibt es verschiedene Informationen zur Auswahl. 

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Strecke** 

- **Länge horizontal**: horizontaler Abstand der beiden Punkte; nur x-Wert und y-Wert werden berücksichtigt 
- **Länge 3D**: räumlicher Abstand der beiden Punkte; x-Wert, y-Wert und z-Wert werden berücksichtigt 
- **Höhenunterschied**: Höhendifferenz der beiden Punkte; nur der z-Wert wird berücksichtigt
- **Ausrichtung**: die Himmelsrichtung des Richtungsvektors P1->P2; Nord bei 0°, Ost bei 90°
- **Steigung**: die Steigung der Linie von Punkt 1 nach Punkt 2

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Polylinie** 

- **Länge horizontal**: Länge der horizontalen Projektion; alle **horizontalen Längen** der Einzelstrecken P1->P2, P2->P3 usw. aufsummiert
- **Länge 3D**: Länge der Polylinie im Raum; alle **3D-Längen** der Einzelstrecken P1->P2, P2->P3 usw. aufsummiert

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Polyeder**

- **Umfang horizontal**: siehe **Länge horizontal** bei Polylinie
- **Umfang 3D**: siehe **Länge 3D** bei Polylinie
- **Fläche horizontal**: die eingeschlossene Fläche des Polyeders, hilfreich für die Mengenermittlung z.B. bei Pflasterarbeiten


<!-- <p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz Menü 2-6.jpg"/>
</p>

Das Erstellen von Linien in Form von Strecken und Geraden gehört - neben dem Definieren und Setzen von Punkten - zu den wichtigsten praktischen Anwendungen. Die Bestimmung einer Linie erfordert mindestens zwei Punkte im zweidimensionalen Raum und unterteilt sich in zwei arten: Strecken und Geraden. Eine Strecke ist eine begrenzt lange Linie innerhalb von zwei Punkten, eine Gerade hingegen ist eine unbegrenzt lange Linie zwischen zwei Punkten. In der Länge begrenzte Linien wie Strecken eignen sich daher ideal für das Erstellen von geometrischen Körpern, wie Baugruben, welche exakte Angaben zur Kantenlänge erfordern.

Unter dem Menüpunkt „Linien“ erhalten Sie die Möglichkeit Punkte zu Linien zusammenzuführen sowie neue Linien zu hinterlegen und zu speichern. Unter Einstellungen (Zahnradsymbol rechts oben) haben Sie die Möglichkeit, sich die Informationen zu zahlreichen Angaben im Hinblick auf Strecken, Polylinien und Polyeder darstellen zu lassen oder bei Bedarf auszublenden.

## Linien als Strecken und Geraden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz Menü 2-7.jpg"/>
</p>

Einzelne Messpunkte können zu Linien (im Folgenden auch Strecken und Geraden genannt) verbunden werden, um mehrere Punkte zusammenzuführen, Geraden zu ziehen und auch komplexere geometrische Anwendungsfälle, wie Baugruben, im Arbeitsplatz zu erstellen.

## Strecken und Geraden ziehen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz Menü 2-8.jpg"/>
</p>

Sie können in der Kartenansicht der Arbeitsansicht Strecken bzw. Geraden abbilden. Erfassen Sie hierfür den Startpunkt und Endpunkt der Strecke als Punkte in der App (Punkte erfassen). Wählen Sie die erfassten Punkte im Anschluss aus. Bestimmen Sie mithilfe des darunterliegenden Reglers, ob Sie die Punkte mit einer Strecke verbinden möchten oder eine durchgehende Gerade legen wollen und bestätigen Sie Ihre Auswahl mit “Ok”. Die Strecke wird automatisch generiert und ist in der primären Arbeitsansicht dauerhaft einsehbar.

## Polyeder erstellen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz Menü 2-9.jpg"/>
</p>

Möchten Sie mehrere Punkte geschlossen mit Strecken verbinden, so können Sie einen Polyeder erstellen. Wählen Sie hierzu 3 oder mehr Punkte in der Reihenfolge aus, in der diese Punkte verbunden werden sollen. Dabei wird Punkt 1 mit Punkt 2, Punkt 2 mit Punkt 3, Punkt 3 mit Punkt 4, usw. verbunden. Der letzte Punkt wird dann wieder mit Punkt 1 verbunden. Mit dieser Funktion lassen sich z.B. Baugruben in der Arbeitsansicht spezifisch einzeichnen.

## Strecken und Geraden löschen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz Menü 2-10.jpg"/>
</p>

Wird die erstellte Strecke bzw. Gerade für anschließende Bauarbeiten nicht mehr benötigt oder ist sie fehlerhaft, können Sie diese mithilfe von “Strecke löschen” auch wieder entfernen. Wählen Sie dazu die zu löschende Strecke aus und bestätigen Sie mit "Ok". -->