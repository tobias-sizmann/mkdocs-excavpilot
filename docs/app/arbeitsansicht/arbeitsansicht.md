# Arbeitsansicht
<!-- ![Arbeitsansicht](Workscreen.png) -->
<p align="center" width="100%">
  <img width="50%" src="/app/arbeitsansicht/images_arbeitsansicht/tablet_Workscreen.png"/>
</p>


Nach erfolgreicher Kalibrierung des Systems gelangen Sie automatisch in die Arbeitsansicht, die Ihnen Informationen über die Position des Löffels im Raum und in Bezug zur Planierfläche bietet und Sie bei Ihren Arbeiten visuell unterstützt.

## Batterieanzeige von Anzeige, Basis und Sensor
<!-- ![Batterie](battery.png) -->
<p align="center" width="100%">
  <img width="100%" src="/app/arbeitsansicht/images_arbeitsansicht/battery.png"/>
</p>

Die Kopfleiste der Arbeitsansicht zeigt den aktuellen Akkustand der Anzeige, der Basisstation und des Sensors an. Achten Sie idealerweise darauf, dass die Akkustände nicht unter 10% fallen, da sich dies insbesondere bei Sensor und Basisstation negativ auf die Performanz auswirken kann. Eine volle Akkuladung reicht ca. 16 Stunden. Die Ladezeit beläuft sich in etwa auf 2,5 Stunden. 

## Frontalansicht - Löffel in Bezug zur Planierfläche
<!-- ![Frontalansicht](top_left.png) -->
<p align="center" width="100%">
  <img width="50%" src="/app/arbeitsansicht/images_arbeitsansicht/top_left.png"/>
</p>

Die linke obere Box in der Arbeitsansicht visualisiert den Baggerlöffel in einer 2D-Frontalansicht:

* Das graue Rechteck stellt den Löffel dar, wobei die Seitenverhältnisse der Eingaben von Höhe und Breite bei der Vermessung entsprechen. 
* Der rote Punkt an der unteren rechten Ecke des Löffels zeigt die ausgewählte Löffelecke. Von diesem Punkt aus wird der Abstand zur Fläche berechnet.  
* Der grüne Strich zeigt die Höhe der erstellten Fläche ohne Versatz an (Ist-Fläche). Er ist nur sichtbar, wenn ein [Versatz](https://docs.excav.de/app/funktionen/arbeitseinstellungen/hoehenversatz_waehlen/) angesetzt wurde.
* Braun eingefärbt ist die von Ihnen erstellte Planierfläche (Soll-Fläche). Sollten Sie noch keine eigene Fläche erstellt haben ([Fläche mit 3 Punkten](https://docs.excav.de/app/funktionen/punkte_und_flächen/flaeche_3_pt/), [Fläche mit 2 Punkten und Neigung](https://docs.excav.de/app/funktionen/punkte_und_flächen/flaeche_2_pt/), [Fläche mit 1 Punkt, Neigung und Richtung](https://docs.excav.de/app/funktionen/punkte_und_flächen/flaeche_1_pt/), [Horizontale auf Höhe eines Punktes](https://docs.excav.de/app/funktionen/punkte_und_flächen/flaeche_0_pt/)), dann wird standardmäßig eine Parallele zur Horizontalen auf Höhe des Referenzpunktes gezogen.

## Seitenansicht - Baggerlöffel in Bezug zur Planierfläche
<!-- ![Seitenansicht](top_right.png) -->
<p align="center" width="100%">
  <img width="50%" src="/app/arbeitsansicht/images_arbeitsansicht/top_right.png"/> 
</p>

Die rechte obere Box in der Arbeitsansicht visualisiert den Baggerlöffel in einer 2D-Seitenansicht:

* Die Baggerschaufel wird grau dargestellt.
* Die grüne Linie zeigt die von Ihnen einmessene Fläche. Sie ist nur sichtbar, wenn ein [Versatz](https://docs.excav.de/app/funktionen/arbeitseinstellungen/hoehenversatz_waehlen/) angesetzt wurde.
* Die Zielfläche, also mit dem von Ihnen eingestellten Versatz zur eingemessenen Fläche, wird braun dargestellt. Sollten Sie noch keine eigene Fläche erstellt haben ([Fläche mit 3 Punkten](https://docs.excav.de/app/funktionen/punkte_und_flächen/flaeche_3_pt/), [Fläche mit 2 Punkten und Neigung](https://docs.excav.de/app/funktionen/punkte_und_flächen/flaeche_2_pt/), [Fläche mit 1 Punkt, Neigung und Richtung](https://docs.excav.de/app/funktionen/punkte_und_flächen/flaeche_1_pt/), [Horizontale auf Höhe eines Punktes](https://docs.excav.de/app/funktionen/punkte_und_flächen/flaeche_0_pt/)), dann wird standardmäßig eine Parallele zur Horizontalen auf Höhe des Referenzpunktes gezogen.

## Draufsicht Baustelle / Bauplan
<!-- ![Draufsicht Baustelle](construction_site_view.png) -->
<p align="center" width="100%">
  <img width="75%" src="/app/arbeitsansicht/images_arbeitsansicht/MapScreen.png"/> 
</p>

Die Draufsicht auf die Baustelle informiert Sie über die Position des Baggerlöffels in Bezug zum Referenzpunkt (REF) und den von Ihnen erfassten Punkten auf der Baustelle. Der graue horizontale Strich stellt den Löffel dar, wobei die Länge des Strichs der eingegebenen Löffelbreite entspricht. Zudem zeigt der rot gekennzeichnete Vektor N stets Richtung Norden.

Sie können auch Ihren eigenen Bauplan in der Draufsicht hochladen. Mehr Informationen hierzu finden Sie in der App unter "[Bauplan laden](https://docs.excav.de/app/funktionen/arbeitseinstellungen/bauplan_laden/)".

## Anzeige der horizontalen und vertikalen Abweichung

Der vertikale Balken auf der linken Seite der Arbeitsansicht zusammen mit dem horizontalen Balken, welcher die Löffelansichten von der Draufsicht auf den Bauplan trennt, stellen das Analogon zur Anzeige am Baggerarm (vgl. [Anzeigekreuz](https://docs.excav.de/geräteübersicht/geraeteuebersicht/#led-anzeigekreuz)) dar. Je nach Präferenz oder falls die Anzeige am Baggerarm aus dem Fahrerhaus nicht gut einsehbar ist, können hierüber aktuelle Höhen- und Neigungsabweichungen von den Soll-Werten abgelesen werden. Der mittige, dunkelgrüne Strich in beiden Balken bezeichnet den jeweiligen Soll-Wert. 