<style>
    setCenter{
        justify-content: center;
    }
</style>

# Werkzeuge

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Werkzeug 2.jpg"/>
</p>

Der Menüpunkt „Werkzeug“ stellt eine Übersicht über alle kalibrierten und eingemessenen Werkzeuge dar. Der Sensor sowie der mitgelieferte Messstab sind standardmäßig vorkalibriert.

Das aktuelle Werkzeug wird unter dem Reiter „Aktuell ausgewählt“ dargestellt, die gespeicherten Werkzeuge unter dem Reiter „Gespeicherte Werkzeuge“. Das aktuell ausgewählte Werkzeug wird mit dem Hinweis „(aktiv)“ in Grün versehen.
Über den Button „+ Hinzufügen“ können neue Werkzeuge hinzugefügt werden. Wichtiger Hinweis: Hierfür ist es erforderlich exakte Werte durch das Eingabe- oder Antastverfahren einzugeben. Nur mit einer möglichst präzisen Kalibrierung des Werkzeugs sind genaue Ergebnisse und fehlerfreies Arbeiten möglich.

## Werkzeug hinzufügen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Werkzeug 3.jpg"/>
</p>

[//]: # (todo: Text überarbeiten: Nur kurz erwähnen, dass aktuell Messstab, Löffel, Schaufel und Schild unterstützt werden. Danach einfach möglichst genau auf Antast- und Eingabeverfahren eingehen und ein Beispiel anhand einer Baggerschaufel geben. Vielleicht mögliche Fehlerquellen in der Kalibrierung beachten. Alle anderen Werkzeuge sind dann analog und müssen deshalb nicht gesondert erklärt werden. Messstab allerdings kurz gesondert erklären.)

Aktuell stehen folgende Werkzeuge zur Verfügung: Messstab, Löffel, Schaufel und Schild. Die Kalibrierung erfolgt über das Eingabe- oder Antastverfahren. Für den Messstab ist eine Höhenangabe erforderlich. Der Schild kann nur durch das Antastverfahren hinterlegt werden.

• Die Hinterlegung des Messstabs erfordert die Höhe ab der Platte in cm und eine Bezeichnung des Werkzeugs (per Eingabeverfahren).

• Die Hinterlegung des Löffels erfordert die Höhe, Breite, Einrückung des Sensors vom Werkzeugrand in cm und eine Bezeichnung des Werkzeugs (per Eingabeverfahren).

• Die Hinterlegung der Schaufel erfordert die Höhe, Breite, Einrückung in cm und eine Bezeichnung des Werkzeugs (per Eingabeverfahren).

• Die Hinterlegung des Schilds erfordert im Antastverfahren den Basispunkt, die Werkzeugecke links, die Werkzeugecke rechts und eine Bezeichnung des Werkzeugs (nur per Antastverfahren).

Auf diese Weise können alle wichtigen Arten von Werkzeugen an gängigen Baumaschinen für Tief- und Straßenbauarbeiten (Klein- und Großbagger, Radlader, Planierraupen, Kompaktlader, Straßen-Grader, ähnliche Baumaschinen und Messstäbe) erfasst und dauerhaft abgelegt werden.

## Werkzeug laden

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Werkzeug 1.jpg"/>
</p>

[//]: # (todo: Ist der Text für die alte App und muss komplett überarbeitet werden.)

Mit der Funktion "Werkzeug laden" können Sie die bereits einmal angelegte Baggerschaufel oder das Werkzeug erneut laden (ohne eine Kalibrierung erneut manuell durchführen zu müssen) oder jederzeit auf den Messstab wechseln. Dieser ist standardmäßig bereits als Werkzeug hinterlegt und muss daher nicht kalibriert werden.
Hinweis: Beachten Sie bitte, dass Ihre Werkzeuge nur lokal in Ihrem Arbeitsplatz gespeichert sind. Sie müssen daher zuerst den entsprechenden Arbeitsplatz laden, bevor Ihnen in diesem Projekt abgelegte Werkzeuge angezeigt werden.

## Werkzeugecke wechseln

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Werkzeug 5.jpg"/>
</p>

[//]: # (todo: Ist auch von der alten App und muss überarbeitet werden, auch wenn es sinngemäß stimmt. Der zweite Teil (Ebene/Höhenversatz) hat mit Werkzeugecke nichts zu tun und muss entfernt werden.)

Diese Funktion bietet Ihnen die Möglichkeit, Ihre während der Kalibrierung festgelegte Schaufel- oder Werkzeugecke (primär notwendig zum Antasten von Punkten) zu wechseln. Je weiter die Schaufel- oder Werkzeugecke vom Sensor entfernt ist, desto größer wird der Messfehler.
Wir empfehlen daher, im Normalfall die Mitte oder die rechte Schaufel- oder Werkzeugecke (bei Montage des Sensors auf der rechten Seite) zu nutzen. Sollte der Sensor ausnahmsweise links montiert sein, empfehlen wir folglich die Mitte oder die linke Schaufel- oder Werkzeugecke.

Nachdem Sie Ihre Ebene (Ist-Fläche) erstellt haben, müssen Sie einen Höhenversatz wählen, um so die Soll-Fläche in Ihrer Arbeitsansicht zu definieren. Sie können dabei einstellen, ob Sie einen Versatz nach oben (z.B. hilfreich, wenn Erde aufgeschüttet werden soll) oder einen Versatz nach unten (z.B. hilfreich, wenn Erde abgetragen werden soll) haben möchten.
Der Versatz kann vertikal oder orthogonal bemessen werden. Vertikaler Versatz bemisst sich senkrecht zur Horizontalen, wohingegen orthogonaler Versatz orthogonal zur Ursprungsebene gemessen wird.


[//]: # (todo: Referenzpunkt hat mit Werkzeug nichts zu tun)

## Referenzpunkt neu setzen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Referenzpunkt.jpg"/>
</p>

Diese Funktion erlaubt eine Neuermittlung des Referenzpunkts, falls erforderlich. Das Setzen des Referenzpunktes wird automatisch zu Beginn der Erstellung eines Arbeitsplatzes abgefragt.

!!! warning "Setzen des Referenzpunktes"

Wenn Sie den Referenzpunkt neu setzen, werden alle erfassten und eingestellten Punkte oder Flächen um die Differenz zwischen dem aktuellen Referenzpunkt und dem neuen Referenzpunkt verschoben und sind somit nicht mehr gültig.
Wenn die Basisstation neu gestartet wurde oder eine neue Positionserfassung durchgeführt wurde, kann durch erneutes Setzen des Referenz-punktes an der Stelle des alten die Arbeitsfläche wieder zur Baustelle synchronisiert werden.
