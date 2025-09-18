<style>
    setCenter{
        justify-content: center;
    }
</style>

# Koordinatensystem

Die aktuelle Position der aktiven Werkzeugsecke wird über die drei Koordinaten x,y,z mehrmals die Sekunde in Echtzeit übermittelt und in der Arbeitsansicht angezeigt (siehe Abb. 4). 

Standardmäßig ist das gängige GNSS-Koordinatensystem END (East-North-Down) aktiv. D.h. die x-Achse spannt sich nach Osten auf, die y-Achse nach Norden und die z-Achse nach unten dem Zenit entgegen. Für viele praktische Anwendungen im Bau und der Vermessung sind diese Richtungen aber nicht immer hilfreich, da man oft lieber in einem projektspezifischen Achsensystem arbeiten möchte – beispielsweise entlang einer Bauachse, eines Zauns oder einer Straße.

Wir bieten zwei Möglichkeiten an, dieses Koordinatensystem umzudefinieren, indem man:

- den Ursprung und die Richtung der x-Achse vorgibt

- die Position und Richtung von sowohl x-Achse als auch y-Achse vorgibt

Dadurch entsteht ein kartesisches Koordinatensystem, welches direkt auf die Absteckung angewendet werden kann.

Beispiel: Sie möchten ein Rechteck für einen 3mx6m Pool abstecken, welcher genau 2 Meter vom Zaun an der Grundstücksgrenze entfernt parallel dazu erbaut werden soll. Definieren Sie hierfür z.B. die Flucht des Zaunes als x-Achse. Dann können Sie Ihren Pool ganz einfach und schnell abstecken: 

- Rechteck Punkt 1 (RP 1): (0, 2) 
- RP2: (6,2) 
- RP3: (6,5) 
- RP4: (0,5)

Beide Optionen zum Setzen eines individuellen, lokalen Koordinatensystems werden in den folgenden Unterkapiteln genauer erklärt. 

## Koordinatensystem mit Ursprung und x-Achse

<p align="center" width="100%">
  <img width="100%" src="/images_docs/1 (3) - Kopie 2.png"/>
</p>

Um Ihr Koordinatensystem mit Ursprung und x-Achse zu definieren, benötigen Sie die Position des Ursprungs und einen Punkt auf der x-Achse, um die Richtung vorzugeben. Die x-Achse verläuft immer vom Ursprung zu Punkt 1. Die y-Achse verläuft dann automatisch im 90° Winkel zur x-Achse nach links durch den Ursprung. Das Koordinatensystem wird auf Höhe des Ursprungs aufgespannt, d.h. die Höhe des Punktes, welcher als Ursprung gewählt wird, ist im neuen Koordinatensystem die Nullhöhe. 

**<span style="color: red; font-weight: bold;">1: &nbsp;</span>** Mit dem Punktliste-Button können Sie einen bereits [erfassten Punkt]() auswählen, welcher als Ursprung bzw. als Punkt auf der x-Achse dienen soll

oder

**<span style="color: red; font-weight: bold;">2: &nbsp;</span>** Sie tasten mit dem Position-Erfassen-Button schnell den Punkt an. Bewegen Sie hierfür die aktuell aktive Werkzeugecke (wir empfehlen für eine genaue Position den Messstab, also in diesem Fall die Messstabspitze) auf die entsprechende Position und klicken Sie dann auf den Button, um die aktuelle Position zu erfassen. 


<p align="center" width="100%">
  <img width="100%" src="/images_docs/1 (5) - Kopie.jpg"/>
</p>

Beide Punkte sind erfasst. Jetzt noch mit "OK" bestätigen und das Koordinatensystem ist aktiv. 
<br><br>
<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (22) - Kopie.png"/>
</p>


In der Arbeitsansicht wird Ihnen dann die aktuelle Position im Koordinatensystem angezeigt. Die drei Achsen sind farbig markiert.

<span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 100%; border: 6px solid red; display: inline-block; margin-right: 8px;"></span>
      <span>x-Achse</span>
</span> 

<span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 100%; border: 6px solid #00FF00; display: inline-block; margin-right: 8px;"></span>
      <span>y-Achse</span>
</span> 

<span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 100%; border: 6px solid blue; display: inline-block; margin-right: 8px;"></span>
      <span>z-Achse</span>
</span> 

## Koordinatensystem mit x-Achse und y-Achse

<p align="center" width="100%">
  <img width="100%" src="/images_docs/1 (4) - Kopie 2.png"/>
</p>

Alternativ können Sie auch beide Achsen definieren. Der Ursprung ergibt sich dann als Schnitt der beiden Achsen. Diese Option ist zum Beispiel dann sinnvoll, wenn der Ursprung schlecht oder gar nicht anzutasten ist. 

Die x-Achse verläuft immer von Punkt 1 nach Punkt 2. Die y-Achse verläuft dann automatisch im 90° Winkel zur x-Achse nach links durch Punkt 3. Das Koordinatensystem wird auf Höhe von Punkt 1 aufgespannt, d.h. die Höhe des Punktes, welcher als Punkt 1 gewählt wird, ist im neuen Koordinatensystem die Nullhöhe. 

## Manuellen Punkt im lokalen Koordinatensystem setzen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (34) - Kopie 2.png"/>
</p>

Sie können auch manuelle Punkte im neuen Koordinatensystem erstellen ohne diese antasten zu müssen. Wählen Sie bei **<span style="color: red; font-weight: bold;">1:</span> Koordinatensystem** das richtige Koordinatensystem aus (standardmäßig ist immer das aktuell aktive Koordinatensystem ausgewählt, Sie können aber auch zwischen mehreren Koordinatensystemen wechseln) und geben Sie für **<span style="color: red; font-weight: bold;">2</span>, <span style="color: red; font-weight: bold;">3</span>, <span style="color: red; font-weight: bold;">4</span>** die entsprechenden Koordinaten ein. 


<!-- <p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Arbeitsplatz Menü 2-2.jpg"/>
</p>

Unter dem Menüpunkt „Koordinatensystem“ erhalten Sie die Möglichkeit ein dreidimensionales Koordinatensystem (x-, y- und z-Achse) mit dem Referenzpunkt als Mittelpunkt oder mit einem ersten Messpunkt der Wahl als Mittelpunkt hinterlegen und speichern. Entweder bildet der Referenzpunkt den Mittelpunkt oder er befindet sich außerhalb mit einem oder mehreren Messpunkten auf der x- und y-Achse. Erstellen Sie das Koordinatensystem und bestätigen Sie den Vorgang mit „Ok“ oder brechen Sie ihn ab mit „Abbrechen“.

<br>

# Anwendungsbeispiel: Koordinatensystem in 2D

Das Anlegen eines Koordinatensystems ermöglicht Ihnen einen zweidimensionalen Raum präzise zu definieren und Punkte darin zu bestimmen, auch wenn kein externer Bauplan als Datei für die Positionsbestimmung vorliegt. Als Mittelpunkt eines neu angelegten Koordinatensystems kann ein wichtiger Referenzpunkt in der Beauplanung - beispielsweise die Ecke eines Zauns oder Gatters - definiert werden. Von diesem ausgehend kann eine Zaunseite als Linie für die x-Achse definiert werden, eine weitere im 90° Winkel als die Linie für die y-Achse. Dadurch kann der Nutzer ausgehend vom Mittelpunkt des Koordinatensystems und ohne einen externen Bauplan einzelne Punkte einmessen, Linien und Geraden ziehen sowie erste Flächen erstellen.

**Beispiel für Koordinatensystem in 2D**

Ausgehend vom Mittelpunkt (Eckpfosten eines Zauns oder Gatters) werden zwei zueinander im 90° Winkel stehende Zäune jeweils als Linien für die x- und y-Achse verwendet. Dadurch kann im zweidimensionalen Koordinatensystem ein jeweils 100 cm von beiden Achsen entfernter Punkte als erster Referenzpunkt für eine Baugrube definiert und angelegt werden, um beispielsweise einen Sicherheitsabstand von exakt 100 cm zum Zaun während der Bauarbeiten einzuhalten.

<br>

# Anwendungsbeispiel: Koordinatensystem in 3D

Es kann ebenfalls ein Koordinatensystem für einen dreidimensionalen Raum angelegt werden, um diesen präzise zu definieren und Punkte darin zu bestimmen, auch wenn kein externer Bauplan als Datei für die Positionsbestimmung vorliegt.

Als Mittelpunkt eines neu angelegten Koordinatensystems kann ein wichtiger Referenzpunkt in der Beauplanung - beispielsweise die Ecke eines Zauns oder Gatters - definiert werden. Von diesem ausgehend kann eine Zaunseite als Linie für die x-Achse definiert werden, eine weitere im 90° Winkel als die Linie für die y-Achse. Zudem kann, falls erforderlich, für die z-Achse der Eckpfosten des Zauns herangezogen werden, um den Raum auf der Baustelle dreidimensional zu definieren. Dadurch können neben einzelnen Linien, Geraden und horizontalen Flächen auch erste geometrische Körper, wie Baugruben aus mehreren Punkten, erstellt werden.

**Beispiel für Koordinatensystem in 3D**

Ausgehend vom Mittelpunkt (Eckpfosten eines Zauns oder Gatters) werden zwei zueinander im 90° Winkel stehende Zäune jeweils als Linien für die x- und y-Achse verwendet. Zusätzlich wird eine vertikale Linie oder Lot (beispielsweise der Eckpfosten) als z-Achse durch den Mittelpunkt gezogen, um eine dreidimensionale Positionsbestimmung zu ermöglichen.

Dadurch kann im dreidimensionalen Koordinatensystem ein jeweils 100 cm von beiden Achsen entfernter Punkte als erster Referenzpunkt für die Ecke einer horizontalen Fläche definiert und angelegt werden. Zusätzlich kann im dreidimensionalen Raum eine Höhe für die Fläche, beispielsweise als maximale oder Solltiefe, für Erdaushubarbeiten definiert werden. -->