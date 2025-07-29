<style>
    setCenter{
        justify-content: center;
    }
</style>

# System einrichten

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Start V2.png"/>
</p>

Lesen Sie sich bitte die folgenden Unterpunkte sorgfältig durch und starten Sie anschließend die excav PILOT App auf dem mitgelieferten Tablet. Vergewissern Sie sich bitte davor, dass die einzelnen Geräte gemäß dem vorherigen Abschnitt „System aufbauen und anbringen“ richtig aufgestellt bzw. am Stiel und der Baggerschaufel oder dem Werkzeug befestigt wurden.
Es gibt eine ausführliche [Videoanleitung auf YouTube](https://www.youtube.com/watch?v=dZmhDPmHHl0&t=224s), in der ein komplettes erstmaliges Setup im Detail durchgeführt und erklärt wird. Wir raten Erstnutzern, bei der Systemeinrichtung des excav PILOT auf die Videoanleitung zurückzugreifen und den Leitfaden nur unterstützend zu verstehen. 

## Allgemeines

<p align="center" width="100%">
  <img width="100%" src="/images_docs/System einrichten excav PILOT erste Ansicht Start.jpg"/>
</p>

Sobald Sie den excav PILOT erstmals nach der Anbringung der Hardwarekomponenten einrichten möchten, müssen Sie die ersten wichtigen Schritte in der App genau befolgen. Bevor Sie einen neuen Arbeitsplatz anlegen oder laden können, müssen als Erstes die Grundfunktionen (siehe Geräte, NTRIP und Werkzeuge) im Start-Menü oben links eingerichtet werden. 

Sobald Sie das Tablet aktivieren und die excav PILOT App starten, gelangen sie zur primären Arbeitsansicht und erhalten zwei Fehlermeldungen zu Beginn gleichzeitig: sowohl "Sensor nicht verbunden" sowie "Kein Arbeitsplatz aktiv". Begeben Sie sich zum Start-Menü und wählen Sie die Kategorie Geräte aus. Dort können der Sensor und das LED-Anzeigekreuz verbunden werden.   

## Geräte verbinden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Geräte V2.jpg"/>
</p>

Es können standardmäßig zwei Geräte, der GNSS-Sensor und das als Hilfestellung dienende LED-Anzeigekreuz verbunden werden. Optional kann eine Basisstation hinzugefügt werden, die gehört jedoch nicht zu den systemrelevanten Hardwarekomponenten. Bevor Sie mit der Konfiguration des Systems starten können, müssen der Sensor, die LED-Anzeige und die optional erhältliche Basisstation verbunden sein. Aktivieren Sie als Erstes den Sensor. 

Im Normalfall wird künftig die Sensoreinheit zuerst angezeigt, die dem System bereits bekannt war. Betätigen Sie "Scannen" und wählen Sie den angezeigten Sensor aus. Die Verbindung kann jederzeit manuell wieder aufgehoben werden. Sollte die Verbindung eines oder mehrerer Geräte fehlschlagen, prüfen Sie bitte zuerst den Akkustand der entsprechenden Geräte und ob sie eingeschaltet sind. Versuchen Sie bei anhaltenden Verbindungsproblemen die Geräte räumlich näher zusammenzubringen bis der Aufbau gelingt und alle Geräte sind.

Hinweis: Durch den GPS-Empfang über ein globales Satellitennetzwerk und RTK-Korrekturdaten über NTRIP kann die exakte Position des Sensors im Raum bestimmt werden. Um zudem die genaue Ausrichtung zu bestimmen, muss der Sensor zu Beginn oder bei entsprechendem Hinweis (kein GNSS oder GNSS zu ungenau) geschwenkt oder bewegt werden - auch, um den verloren gegangenen GPS-Empfang wiederherzustellen.

## NTRIP

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Start V3.png"/>
</p>

Die NTRIP-Funktion wird benötigt, um externe RTK-Korrekturdaten von einem Anbieter für GNSS-Dienste zu beziehen. Klicken Sie auf den Button "+ Hinzufügen", um erstmals eine NTRIP-Verbindung anlegen zu können. Füllen Sie die Eingabefelder mit den verfügbaren Daten des GNSS-Anbieters aus und vergeben Sie einen geeigneten Namen, insbesondere wenn später mehrere NTRIP-Verbindungen eingerichtet werden. Da die Arbeit im Freien auf Baustellen erfolgt, werden für eine Internetverbindung mobile Daten über eine eingesetzte SIM-Karte benötigt. 

Sobald die Internet- und NTRIP-Verbindung aktiv sind und aufgrund Blick auf den freien Himmel der Aufbau einer GPS-Verbindung möglich ist, können Sie mit der Kalibrierung eines Werkzeuges, wie einer Baggerschaufel, beginnen. Dies erkennt man daran, dass alle drei Symbole oben rechts in der Ansicht (Ausrichtung, GPS-Empfang und NTRIP-Verbindung) in Grün hinterlegt sind. Der Messstab ist nicht erforderlich, da dieser standardmäßig hinterlegt und damit direkt einsatzbereit ist. Daher muss zunächst das gewünschte Werkzeug kalibriert und hinterlegt werden.  


## Baggerschaufel/Werkzeug vermessen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Werkzeug 3.jpg"/>
</p>

Die nachstehenden Schritte müssen sorgfältig ausgeführt werden, da ansonsten Messfehler entstehen, die sich in der späteren Arbeit immer wieder fortsetzen und Ergebnisse verfälschen. 

Es gibt zwei Möglichkeiten ein Werkzeug erstmals zu kalibrieren: Das Eingabeverfahren mit ermittelten Messwerten sowie das Antastverfahren über das Werkzeug mit dem Sensor. Das Antastverfahren ist einfacher realisierbar und daher bei der ersten Einrichtung empfehlen.   

**1. Antastverfahren**

Über die Schaufel- oder Werkzeugecke wird die Höhendifferenz zur Arbeitsfläche berechnet und des Weiteren wird sie zur Erfassung von Punkten auf der Baustelle herangezogen. Daher kann die Schaufel- oder Werkzeugecke zur Bestimmung von Punkten genutzt werden. Den genauesten Messwert erhalten Sie jeweils an der am nächsten zum Sensor befindlichen Ecke. Bei bereits abgenutzten Ecken der Schaufel- oder Werkzeugschneide empfiehlt sich die mittlere Position zum Antasten von Punkten, vor allem bei denen die Höhe relevant ist. 

Für das Antastverfahren benötigen Sie einen statischen Basispunkt auf dem Boden, der sich gut merken und wieder ansteuern lässt. Definieren Sie den Basispunkt, indem Sie den Sensor exakt mittig darauf platzieren und drücken Sie auf "Punkt erfassen". 

Als nächstes platzieren Sie den Sensor mit Blickrichtung zur Fahrerkabine der Baumaschine auf die linke Außenseite des Werkzeugs, um die linke Werkzeugecke zu erfassen. Bewegen Sie das Werkzeug derart, dass die linke Werkzeugecke (aus Sicht der Fahrerkabine heraus) an dem Basispunkt aufliegt und erfassen Sie den Punkt. Praktizieren Sie den gleichen Vorgang analog mit der rechten Werkzeugecke und erfassen Sie ebenfalls den Punkt. Nach Abschluss der Punkterfassung müssen Sie dem Werkzeug noch einen geeigneten Namen vergeben.

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Werkzeug 5.jpg"/>
</p>

**2. Eingabeverfahren**

Für das Eingabeverfahren werden exakte Angaben zum Werkzeug benötigt, damit der Sensor die Maße in der App korrekt abbilden kann. Bestimmen Sie zuerst die Breite der Schaufel- oder Werkzeugschneide und tragen Sie den Wert in das Abfragefeld der App ein. Bitte messen Sie bis auf eine Nachkommastelle im Zentimeterbereich genau. Danach bestimmen Sie den seitlichen Versatz (Einrückung) des Sensors. Dies ist die Distanz von der Sensormitte bis zur von der Fahrerkabine gesehen rechten Außenseite der Baggerschaufel oder des Werkzeugs. Tragen Sie den ermittelten Wert in das Abfragefeld in der App ein und bestätigen Sie diese. 

Für das manuelle Eingabeverfahren wird das mitgelieferte Kalibriertool benötigt. Die Anleitung zur genauen Herangehensweise mit dem Kalibriertool erfahren Sie im nachfolgenden Abschnitt.

!!! information "Abgenutzte Schaufel- oder Werkzeugschneide"

Bei manchen Baggerschaufeln oder Werkzeugen sind die Seitenwände leicht angeschrägt oder die Schneide steht etwas über. Messen Sie in diesem Fall die Distanz bis zum äußersten Punkt der Schaufel- oder Werkzeugschneide. Wie Sie die Höhe der Baggerschaufel oder des Werkzeugs mithilfe des Kalibriertools ablesen, wird Ihnen im nächsten Abschnitt erklärt.

## Kalibriertool anbringen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Anleitung & FAQ Anbringung 5.png"/>
</p>

Hinweis: Der excav PILOT wurde ursprünglich mit einem kleinen und handlichen Kalibriertool ausgestattet, um das Eingabeverfahren zu erleichtern. Dieses ist bei älteren excav Systemen bereits erhältlich gewesen und kann daher weiterhin zur Kalibrierung Anwendung finden.

**Nutzung des Kalibriertools**

Gehen Sie beim Anbringen des Kalibriertools an der Baggerschaufel oder am Werkzeug so vor:

• Positionieren Sie die an der Baumaschine montierte Baggerschaufel oder Werkzeug mit der Schneide auf einem ebenen und stabilen Untergrund. Die Schneide darf während des Kalibrierungsvorgangs nicht im Bodengrund einsinken oder anderweitig bewegt werden.

• Bringen Sie anschließend das Kalibriertool an der Schaufel- oder Werkzeugseite an, sodass der blaue Punkt auf dem Sensor in der Mitte des kleinen Sichtrohres erscheint.

• Befestigen Sie den Meterstab (Zollstock) so in der Halterung am Ende des Kalibriertools, dass dieser am Ort der Schaufel- oder Werkzeugschneide den Boden berührt. Der Meterstab kann durch leichtes Drücken in das Kalibriertool eingesetzt und fixiert werden.

• Lesen Sie anschließend die Höhe in cm ab. Sie ist der Abstand zwischen der Schaufel- oder Werkzeugschneide und Markierung (Kerbe) am Kalibriertool.

• Lassen Sie das Kalibriertool mit Meterstab für den nachfolgenden Schritt an der Baggerschaufel oder am Werkzeug befestigt.

**Baggerschaufel/Werkzeug justieren** 

Heben Sie die Baggerschaufel durch Bedienung der Baumaschine als nächstes leicht an und neigen Sie diesen, bis die Spitze des Meterstabs exakt mit der Schneide übereinstimmt. 

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Anleitung & FAQ Anbringung 6.png"/>
</p>

Das Kalibriertool mit fixiertem Meterstab dient Ihnen dabei als Hilfe, das Lot von 180° zu finden. Holen Sie sich hierzu ggf. eine zweite Person zu Hilfe, die die Position von der Seite überprüft. Ist die angegebene Position eingenommen, dann bestätigen Sie dies in der App mit “Weiter”.


## Arbeitsplatz anlegen/laden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz 1.jpg"/>
</p>

Sobald ein Werkzeug (zzgl. zum hinterlegten Messstab) kalibriert und angelegt wurde, können Sie beginnen, einen Arbeitsplatz zu laden oder neu anzulegen. Um einen neuen Arbeitsplatz anzulegen, wählen Sie "Neuer Arbeitsplatz". Sie können hier auch einen bereits angelegten Arbeitsplatz aus der Auflistung wählen und laden.

## Baumaschine wählen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Werkzeug 2.jpg"/>
</p>

Wählen Sie hier die Art der Baumaschine aus, an dessen Werkzeug Sie den Sensor des excav PILOT anbringen wollen. Der Einrichtungsprozess läuft für jede Baumaschine egal welcher Art und Größe gleich ab. Einzig der bereits vorkonfigurierte Messstab kann direkt geladen werden.


## Referenzpunkt setzen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Referenzpunkt.jpg"/>
</p>

Der Referenzpunkt dient als Nullpunkt, von dem aus alle weiteren Maße errechnet werden. Zu Beginn eines neuen Arbeitsplatzes bildet der Referenzpunkt den Mittelpunkt eines statischen Koordinatensystems. Hierfür bietet sich idealerweise eine Stelle auf der Baustelle an, die über den gesamten Bauverlauf verfügbar bleibt, sich nicht ändert, jederzeit gut zu erreichen ist und freie Sicht auf den Himmel bietet. Zur Erfassung des Referenzpunkts müssen Sie die ausgewählte Schaufel- oder Werkzeugecke an die entsprechende Stelle bewegen, auf “Referenzpunkt setzen” klicken und dann drei Sekunden warten, bis der Referenzpunkt vermessen und aufgenommen worden ist.

## Einstellung LED-Anzeigekreuz

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht LED Anzeige.jpg"/>
</p>

Die Einstellungen des LED-Anzeigekreuzes erlauben es Ihnen die Helligkeit der Leuchtdioden festzulegen und Anpassungen der horizontalen sowie vertikalen Ausschlagssensibilität vorzunehmen. Die Standardeinstellungen ab Werk sind:

• LED-Helligkeit: 50 % der maximalen Helligkeit

• LED-Abstand horizontal: 1 Grad pro LED

• LED-Abstand vertikal: 20 mm pro LED

Beachten Sie, dass eine erhöhte LED-Helligkeit sich negativ auf die Akkulaufzeit der LED-Anzeige auswirkt und diese dann öfters aufgeladen werden muss.

## Status-Übersicht

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht rechtsoben V2.jpg"/>
</p>

Die Status-Übersicht dient als Hilfe bei der Inbetriebnahme Ihres Systems. Dort aufgelistet finden Sie alle relevanten Kennzeichen (Verbindung zu den einzelnen Systemeinheiten Sensor, LED-Anzeige und Basisstation; Positionserfassung; Referenzpunkt setzen; Orientierung; Schaufelkalibrierung; GNSS-RTK; WLAN-Verbindung). Sollten ein oder mehrere dieser Schritte nicht erfolgt sein, kann das System nicht in Betrieb genommen werden.

Stellt die App das Fehlen mehrerer der oben aufgelisteten Kennzeichen fest, empfiehlt sich entsprechend eine wiederholte Durchführung der Einrichtung. Das System findet die Orientierung im Normalfall nach wenigen Minuten von selbst (hierfür muss der Messstab, die Baggerschaufel oder das Werkzeug bewegt und geschwenkt werden). Existiert keine GNSS-RTK-Lösung, befinden Sie sich wahrscheinlich mit dem Sensor zu nahe an größeren Strukturen, welche den Satellitenempfang beeinträchtigen.

## System ausschalten

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht System ausschalten.jpg"/>
</p>

Die Hardware kann durch das Betätigen der Drucktasten an Sensor, LED-Anzeige und ebenfalls bei der optional erhältlichen Basisstation manuell abgeschaltet werden. Schalten Sie die Geräte im Normalfall nach Beendigung und Speicherung der Arbeit am Tablet aus. 
