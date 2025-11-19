<style>
    setCenter{
        justify-content: center;
    }
</style>

# Flächen

Diese Seite befindet sich gerade in Bearbeitung.

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (112) - Kopie.jpg"/>
</p>

Das Erstellen von horizontalen und geneigten Flächen über einen oder optional mehrere Punkte, ist eine der wichtigsten Arbeitsfunktionen der 3D-basierten App-Anwendung des excav PILOT.

Das aktuell ausgewählte Werkzeug oder Sensor wird in der primären Arbeitsansicht räumlich im Verhältnis zur aktiven Fläche dargestellt (farblich in einem dunkleren Grauton abgehoben) sowie in der Frontal- und Seitenansicht im oberen Bildschirmabschnitt.

!!! info "Höhenangabe und Positionsbestimmung"
    Die Höhenangabe der Fläche bezieht sich auf die Höhenangabe zum Meeresspiegel (exakt 0 Höhenmeter) und kann sich abhängig vom Standort innerhalb von Deutschland und anderswo erheblich unterscheiden. Die für die Arbeit auf der Baustelle vor Ort erforderlichen Angaben zur Positionsbestimmung werden über die Angaben der x-,y- und z-Koordinate dargestellt. 


## Neue Flächen erstellen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (100) - Kopie.jpg"/>
</p>

Die Funktion zur Flächenerstellung finden Sie in der Sidebar des Designmenüs. Aktive Flächen erscheinen in der primären Arbeitsansicht (mathematisch) als unbegrenzte Ebenen. 

Folgende Arten von Flächen sind in der excav PILOT App standardmäßig als Option verfügbar: 

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> 1-Punkt Fläche** - Eine Fläche, die durch mindestens einen Punkt im Raum definiert ist. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> 2-Punkt Fläche** - Eine Fläche, die durch mindestens zwei Punkte im Raum definiert ist.

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> 3-Punkt Fläche** - Eine Fläche, die durch mindestens drei Punkte im Raum definiert ist.

Alle grundlegenden Arten von Flächen (1-Punkt Fläche, 2-Punkt Fläche und 3-Punkt Fläche) können grundsätzlich durch mindestens einen oder mehrere Punkte anlegt werden. Weiterhin können Sie die gewünschte Fläche durch Angabe der Steigung (Neigungswinkel) sowie durch Angabe des Höhenversatzes präziser als lediglich durch einzelne Punkte im Raum bestimmen.

Die standardmäßig vorhandenen Optionen zur Flächenerstellung lassen sich mit entsprechender Erfahrung in der alltäglichen Nutzung modifizieren. Durch die Definition über mehrere Punkte sowie unter Angabe der Steigung bzw. Neigung und des Höhenversatzes können auch spezifisch genaue Flächen im komplexen Arbeitsumfeld einer modernen Baustelle realisiert werden.  

Mit folgenden Funktionen lässt sich die gewünschte Fläche im Raum präziser bestimmen.

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Steigung** | Der Faktor Steigung beträgt standardmäßig 0.0 und kann sowohl in Prozent (%) sowie in Höhengrad (deg) dargestellt werden. Als Ausrichtungsoptionen kommen sowohl die Werkzeugrichtung des Sensors oder die Himmelsrichtung infrage. Der Wert der Steigung kann sowohl positiv als auch negativ sein. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Höhenversatz** | Der Faktor Höhenversatz beträgt standardmäßig 0.0 und kann sowohl in Zentimeter (cm) sowie in Meter (m) dargestellt werden. Als Ausrichtungsoptionen kommen die vertikale und orthogonale Ausrichtung infrage. Die Unterschiede zwischen beiden Optionen werden in einem kleinen Informationsfenster näher erklärt. Der Wert des Höhenversatzes kann sowohl positiv als auch negativ sein. 

!!! info "Tipps zur Flächenerstellung"
    Für das Erstellen einer neuen Fläche können sowohl bereits vorhandene Punkte der Punkteliste verwendet oder gänzlich neu eingemessene Punkte verwendet werden. Wir empfehlen Punkte zu verwenden, die bereits zuvor genau bestimmt und eingemessen wurden, um eine Fläche im Bedarfsfall leichter erneut anlegen zu können. 
    
    Über das Zahnrad-Symbol oben rechts öffnet sich das Einstellungsfenster. Hier können Sie auswählen, welche Informationen zu den Flächen in Ihrer Flächen-Liste angezeigt werden sollen, darunter den Typ sowie den optional vergebenen Wert des Höhenversatzes einer Fläche. 



## Eine 1-Punkt Fläche erstellen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (101) - Kopie 2.png"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Punkt aus Punkteliste** | Nutzen Sie diese Funktion, um einen bereits vorhandenen Punkt der Punkteliste für die Flächenerstellung zu verwenden. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Punkt neu erfassen** | Nutzen Sie diese Funktion, um einen neu ausgewählten Punkt für die Flächenerstellung zu verwenden. 

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Flächenbezeichnung** | Vergeben Sie einen geeigneten Arbeitsnamen für die neue Fläche, insbesondere bei mehreren aktiven Flächen.

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Angabe Steigung** | Nutzen Sie diese Funktion für die Angabe der Steigung. Wenn kein Wert angegeben ist, wird das Eingabefeld standardmäßig 0.0 ausweisen.

**<span style="color: red; font-weight: bold;">5: &nbsp;</span> Angabe Höhenversatz** | Nutzen Sie die Funktion, um die Höhe (+) bzw. Tiefe (-) der Fläche vertikal oder orthogonal anzugeben.  

Für die 1-Punkt Fläche kann zusätzlich zur Position und Höhenangabe des einzig erforderlichen Punktes ein Steigungswinkel als Neigung angegeben werden. Sollte keine Neigung angegeben werden, beträgt der Wert im unteren Eingabefeld der Steigung standardmäßig 0.0. 

Optional kann über die Funktion Höhenversatz die Höhe (+) bzw. Tiefe (-) der Fläche zu Punkt 1 manuell angegeben werden, um die Fläche auf der gewünschten Höhe bzw. Tiefe darzustellen. Der Höhenversatz kann entweder vertikal (im senkrechten Lot) zur virtuellen Referenzebene des Koordinatensystems oder orthogonal (im senkrechten Lot) zur Referenzfläche mit Neigung abgebildet werden. Durch die Auswahloption ergeben sich Abweichungen im Höhenversatz.    

<br>

### Varianten der 1-Punkt Fläche

**Horizontale 1-Punkt Fläche (keine Neigung)**

Die einfachste Variante stellt eine 1-Punkt Fläche ohne Neigungswinkel dar und somit völlig ebenerdig ist. Sie liegt parallel zur virtuellen Grundfläche des Koordinatensystems in der primären Arbeitsansicht und befindet sich auf Höhe des einzelnen Punktes.   

**Beispiel: Horizontale Fläche im Sportplatzbau**

Normalerweise werden Sportplatzflächen mit einer minimalen Neigung (zumindest zum Feldrand hin) angelegt, damit Regen- und Schmelzwasser gefahrlos abfließen können. Gelegentlich kann es jedoch im Sportplatzbau erforderlich sein eine Fläche zunächst völlig ebenerdig und glatt zu gestalten, beispielsweise um Material wie Schotter sauber abzuziehen. Dies gilt beispielsweise für ausgedehnte Flächen wie die langezogenen Start- und Landebahnen auf Flughäfen.  

**Beispiel: Horizontale Sohlenfläche einer Baugrube**

Auf großen Baustellen für die Grundsteinlegung eines größeren Gebäudes ist es zu Beginn erforderlich, die spätere Baufläche ebenerdig anzulegen und jede unerwünschte Erhebung zu begradigen, um den Bodengrund für das Anlegen des Fundaments zu erschließen.     

<br>

**1-Punkt Fläche mit einem Neigungswinkel**

Über die Funktion Steigung lässt sich die Neigung der Fläche über den Punkt bestimmen. Hierbei kommt es auf drei Faktoren an: Den Umfang der Steigung in Prozent oder Grad, ob die Steigung positiv oder negativ ist sowie die Ausrichtung (in Werkzeug- oder in Himmelsrichtung). 

**Beispiel: Großräumiges Abtragen von Erdreich**

Eine 1-Punkt Fläche mit einem moderaten Neigungswinkel ist ideal, um in einem Arbeitsbereich großflächig Erdreich oder anderes Material schrittweise abzutragen, wo lediglich ein minimaler Höhenunterschied von 0 bis 3° anfällt oder später Regen- und Schmelzwasser von der künftigen Einsatzfläche gefahrlos ablaufen müssen.  

**Beispiel: Großräumiges Aufschütten von Erdreich**

Umgekehrt lässt sich eine 1-Punkt Fläche mit einem moderaten Neigungswinkel nutzen, um eine zuvor völlig ebenerdige Fläche bis zu einer gewissen Höhe schrittweise mit Erdreich oder anderem Material aufzuschütten und somit ein leichtes Gefälle herzustellen.   

<br>

**1-Punkt Fläche mit einem Höhenversatz**

Über die Funktion Höhenversatz lässt sich die Höhe der Fläche über den Punkt bestimmen, sowohl positiv (oberhalb des Punktes) als auch negativ (unterhalb des Punktes). Die Höhenangabe kann sowohl in Zentimeter (cm) oder in Meter (m) erfolgen. 

**Beispiel: Anlegen einer Fläche als Plateau**

Gelegentlich kann es erforderlich sein, eine Fläche zwar ebenerdig und somit parallel zum Koordinatensystem der primären Arbeitsansicht, jedoch gegenüber dem Ausgangspunkt erhöht, zu gestalten. Hierzu lässt sich eine ebenerdige oder geneigte Fläche mit Erdreich oder anderem Material aufzuschütten und sauber mit einem Planierbalken abziehen, bis das Plateau in der gewünschten Sollhöhe gegeben ist. 

<br>

## Eine 2-Punkt Fläche erstellen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (102) - Kopie 2.png"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Punkt aus Punkteliste** | Nutzen Sie diese Funktion, um einen bereits vorhandenen Punkt der Punkteliste für die Flächenerstellung zu verwenden. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Punkt neu erfassen** | Nutzen Sie diese Funktion, um einen neu ausgewählten Punkt für die Flächenerstellung zu verwenden. 

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Flächenbezeichnung** | Vergeben Sie einen geeigneten Arbeitsnamen für die neue Fläche, insbesondere bei mehreren aktiven Flächen.

**<span style="color: red; font-weight: bold;">4: &nbsp;</span> Angabe Steigung** | Nutzen Sie diese Funktion für die Angabe der Steigung. Wenn kein Wert angegeben ist, wird das Eingabefeld standardmäßig 0.0 ausweisen.

**<span style="color: red; font-weight: bold;">5: &nbsp;</span> Angabe Höhenversatz** | Nutzen Sie die Funktion, um die Höhe (+) bzw. Tiefe (-) der Fläche vertikal oder orthogonal anzugeben. 

**<span style="color: red; font-weight: bold;">6: &nbsp;</span> Angleichung Höhe** | Die Höhe von Punkt 2 kann optional auf die Höhe von Punkt 1 angeglichen werden.

Für die 2-Punkt Fläche kann zusätzlich zur Position und Höhenangabe der zwei erforderlichen Punkte ein Steigungswinkel als seitliche Neigung angegeben werden. Sollte keine Neigung angegeben werden, beträgt der Wert im unteren Eingabefeld der Steigung standardmäßig 0.0. 

Optional kann über die Funktion Höhenversatz die Höhe (+) bzw. Tiefe (-) der Fläche zu Punkt 1 manuell angegeben werden, um die Fläche auf der gewünschten Höhe bzw. Tiefe darzustellen. Der Höhenversatz kann entweder vertikal (im senkrechten Lot) zur virtuellen Referenzebene des Koordinatensystems oder orthogonal (im senkrechten Lot) zur Referenzfläche mit Neigung abgebildet werden.

Die Neigung einer 2-Punkt Fläche als Steigungsfaktor ergibt sich aus dem Höhenunterschied zwischen Punkt 1 und Punkt 2, da die Fläche beide Punkte durchläuft und sich somit nicht parallel zum Koordinatensystem der primären Arbeitsansicht bewegt. Je größer der Höhenunterschied und je näher die Punkte P1 und P2 räumlich beieinander liegen, desto größer und somit steiler fällt die Steigung der Fläche aus. Darüber hinaus lässt sich ein seitlicher Neigungswinkel der Fläche (zusätzlich zur eigentlichen Höhenneigung über die Steigung) nach rechts in Blickrichtung von P1 auf P2 angeben. 

Alternativ kann Punkt 2 räumlich auf die Höhe von Punkt 1 angeglichen werden, um gezielt über einen manuellen Eingabewert die Höhenneigung über die Steigung anzugeben. Hierzu steht unten im Menü die Funktion "Punkt 2 auf Punkt 1 angleichen" zur Verfügung. Hierdurch liegt Punkt 2 sozusagen ebenfalls auf der Ebene von Punkt 1. Die Höhenneigung kann als seitliche Steigung rechts in Blickrichtung von P1 auf P2 definiert werden.

<br>

### Varianten der 2-Punkt Fläche

**2-Punkt-Fläche ohne eine weitere Neigung**

Im einfachsten Fall kann eine 2-Punkt Fläche einzig über zwei Punkte ohne weitere Angabe einer Steigung oder eines Höhenversatzes angegeben werden. Die Steigung bzw. das Gefälle der Fläche ergibt sich somit aus dem Höhenunterschied und der Nähe von Punkt 2 zu Punkt 1. Hierdurch ergeben sich dennoch präzisere Möglichkeiten eine Fläche in der Neigung zu bestimmen.     

**Beispiel: Geringfügig geneigte Fläche für Auffahrt**

Ein typisches Beispiel für eine einfache 2-Punkt-Fläche ist das Anlegen einer Straßenausfahrt für ein Gebäude, wobei Punkt 1 beispielsweise den Beginn der Auffahrt am Straßenrand und Punkt 2 den endgradigen Punkt an der Garage oder Stellplatzfläche bildet. In diesem Beispiel liegt verständlicherweise nur ein geringer Neigungswinkel vor. Auch für ähnliche Zwecke, wie das Gestalten einer Fläche für eine Rampe auf einer großen Tiefbau-Baustelle oder dergleichen, lässt sich diese Methode gut anwenden.  

**Beispiel: Geringfügig geneigte Fläche im Straßenbau**

Auf einer sehr langgestreckten ebenen Fläche wie im Straßenbau ist es im Regelfall erforderlich, dass eine minimale Neigung zum Fahrbahnrand vorliegen muss, damit Regen- und Schmelzwasser gefahrlos ablaufen können und sich nicht auf der Fahrbahn ansammeln sowie den späteren Verkehr gefährden. Eine minimale Seitenneigung in Richtung rechter Fahrbahnseite von unter einem Grad wird im Straßenbau praktiziert, um dieses Problem zu lösen.   

<br>

**2-Punkt-Fläche mit einer Neigung**

In komplexeren Anwendungsfällen kann eine 2-Punkt Fläche über zwei Punkte sowie unter Angabe einer weiteren Steigung als Seitenneigung angegeben werden. Die Steigung bzw. das Gefälle der Fläche ergibt sich somit aus dem Höhenunterschied und der Nähe von Punkt 2 zu Punkt 1. Hinzukommt ein seitlicher Neigungswinkel nach rechts in Blickrichtung von P1 auf P2. 

**Beispiel: Große Baugrube als Polyeder oder anderes Vieleck**

Diese Auswahloption bietet sich jederzeit an, wenn eine Fläche nicht nur einen Steigungswinkel zwischen Punkt 1 und Punkt 2 aufweist, sondern zudem in eine spezifische Richtung geneigt sein muss.   

**Beispiel: Geringfügig geneigte Fläche für Auffahrt**

Über die Auswahloption "Punkt 2 auf Punkt 1" angleichen lässt sich ebenfalls gut eine größere Straßenausfahrt anlegen. Hierbei liegen Punkt 1 sowie versetzt Punkt 2 (in der Höhe angeglichen) entlang des Straßenrandes und die seitliche Neigung entspricht der moderaten Steigung in Richtung des Gebäudes, zu dessen Stellplatz die Ausfahrt hinführen soll.  

<br>

## Eine 3-Punkt Fläche erstellen

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot (103) - Kopie 2.png"/>
</p>

**<span style="color: red; font-weight: bold;">1: &nbsp;</span> Punkt aus Punkteliste** | Nutzen Sie diese Funktion, um einen bereits vorhandenen Punkt der Punkteliste für die Flächenerstellung zu verwenden. 

**<span style="color: red; font-weight: bold;">2: &nbsp;</span> Punkt neu erfassen** | Nutzen Sie diese Funktion, um einen neu ausgewählten Punkt für die Flächenerstellung zu verwenden. 

**<span style="color: red; font-weight: bold;">3: &nbsp;</span> Flächenbezeichnung** | Vergeben Sie einen geeigneten Arbeitsnamen für die neue Fläche, insbesondere bei mehreren aktiven Flächen.

**<span style="color: red; font-weight: bold;">5: &nbsp;</span> Angabe Höhenversatz** | Nutzen Sie die Funktion, um die Höhe (+) bzw. Tiefe (-) der Fläche vertikal oder orthogonal anzugeben. 

**<span style="color: red; font-weight: bold;">5: &nbsp;</span> Angabe Steigung** | Über die optional verfügbare Steigungsfunktion kann eine Neigung als Steigung angegeben werden.   

Für die 3-Punkt Fläche kann zusätzlich zur Position und Höhenangabe der drei erforderlichen Punkte ein Steigungswinkel als seitliche Neigung jeweils in Blickrichtung von P1 auf P2 sowie in Blickrichtung von P1 auf P3 angegeben werden. Sollte die Funktion "Mit Steigung" nicht ausgewählt und keine Art der Neigung angegeben werden, wird einzig der Neigungswinkel als Steigung zwischen P3 und der Gerade zwischen P1 und P2 dargestellt.  

Optional kann über die Funktion Höhenversatz die Höhe (+) bzw. Tiefe (-) der Fläche zu Punkt 1 manuell angegeben werden, um die Fläche auf der gewünschten Höhe bzw. Tiefe darzustellen. Der Höhenversatz kann entweder vertikal (im senkrechten Lot) zur virtuellen Referenzebene des Koordinatensystems oder orthogonal (im senkrechten Lot) zur Referenzfläche mit Neigung abgebildet werden.

<br>

### Varianten der 3-Punkt Fläche

**Variante 1: Einfache 3-Punkt-Fläche ohne eine weitere Neigung**

Eine einfache 3-Punkt Fläche ohne weiteren Neigungswinkel ist ideal, wenn die Lage einer Fläche im Raum exakt bestimmt werden muss, um präzise Erdarbeiten aufgrund räumlicher Begrenzung der Baugrube oder den Abschluss von Tiefbauarbeiten ermöglichen zu können. Alle zuvor genannten Anwendungsbeispiele lassen sich mit der Option einer 3-Punkt Fläche abbilden, allerdings genauer und mit mehr Möglichkeiten die Beschaffenheit der Fläche zu präzisieren.     

**Beispiel: Abgeschrägte Fläche in der Baugrube**

Aufgrund der präzisen Referenzierung der Fläche über drei Punkte im Raum kann man mit einer einfachen 3-Punkt Fläche ohne weiteren Neigungswinkel überall innerhalb einer größeren Baugrube flexibel eine kleine schräge Fläche anlegen, um beispielsweise Erdreich oder anderes Material gezielt abzutragen und durch anschließende Planierarbeiten eine Rampe für einen weiteren Zugang der Baumaschine in die Baugrube anzulegen.   

<br>

**Variante 2: 3-Punkt-Fläche inklusive weiterer Neigung**

Wenn im Rahmen der Option der 3-Punkt Fläche die Funktion "Mit Steigung" ausgewählt wird, fungiert Punkt 1 als zentraler Referenzpunkt der Fläche mit der Möglichkeit die Steigung in Blickrichtung von P1 auf P2 oder in Blickrichtung von P1 auf P3 manuell als Höhenneigung anzugeben. 

**Beispiel: Komplexe geometrische Modelle im Garten- und Landschaftsbau**

Eine solche Option bietet sich an, wenn beispielsweise im Garten- und Landschaftsbau eine Vielzahl individueller und verschiedenartiger Flächen wird, um die natürlich Unebenheit und Abwesenheit menschlicher Begradigung im Landschaftsbild zu suggerieren, wie kleine Hügel, Senken, Täler und Teichmulden im Rahmen eines größeren Garten- und Landschaftsbauprojektes.  


<!-- BACKLOG

Ebene oder im dreidimensionalen Raum vertikale oder geneigte Flächen lassen sich am einfachsten über das definieren und Setzen von Punkten sowie das Erstellen von Linien durch Strecken und Geraden anlegen. Zudem haben Nutzer die Möglichkeit Flächen durch ein bis drei einzelne Punkte sowie Angabe eines Neigungswinkels im Raum anzulegen und darzustellen.

Unter dem Menüpunkt „Flächen“ erhalten Sie die Möglichkeit Flächen anhand mehrerer Optionen zu hinterlegen und zu speichern. Unter Einstellungen (Zahnradsymbol rechts oben) haben Sie die Möglichkeit den Typ und den Höhenversatz darstellen zu lassen oder bei Bedarf auszublenden. Wenn sie eine neuen Fläche erstellen möchten, betätigen Sie den Button „+ Neue Fläche“. Sie gelangen zu einer Ansicht, über die Sie mehrere Möglichkeiten haben, eine Fläche zu erstellen, sowohl über einen als auch über mehrere Punkte.

Hinweis: Eine horizontale Fläche ist als Ebene mathematisch unendlich in der Ausdehnung. Durch die Begrenzung durch Linien entsteht aus einer Ebene eine klar definierte Fläche.  


## Fläche über einen Punkt erstellen

Um eine Ein-Punkt-Fläche zu erstellen, müssen Sie mind. einen Punkt erfassen und speichern sowie die Werte zur Steigung in % nach Werkzeugrichtung / Himmelsrichtung und Höhenversatz in cm / m nach vertikal / orthogonal angeben.
Mit dieser Funktion können Sie eine Fläche (zum Beispiel die gewünschte Planierfläche) aus einem von Ihnen ausgewählten Punkt, einem Neigungswinkel und einem Richtungswinkel erschaffen. Sie können als Richtung eine gezielte Himmelsrichtung auswählen (z.B. Ausrichtung nach Norden 0°, Osten 90°, Süden 180° oder Westen 270°) oder Sie nutzen die Schaufelrichtung (Fläche steigt dann hinter die Baggerschaufel an). Legen Sie hierfür den Regler “Schaufelrichtung nutzen” um und schwenken Sie die Baumaschine, sodass die Baggerschaufel oder das Werkzeug in die gewünschte Richtung zeigt, bevor Sie die Flächenberechnung starten.
Hinweis: Eine Fläche kann im Raum erst durch drei Punkte eindeutig definiert werden, daher sind weitere Angaben zur Lagebestimmung erforderlich.

Sollte der Steigungswinkel 0° betragen, spielt der Steigungswinkel als Faktor für eine Ein-Punkt-Fläche keine Rolle. Die Fläche erscheint dann horizontal ohne jede Neigung im dreidimensionalen Raum.   

**Beispiel: Fläche über einen Punkt erstellen**

Im Alltag auf Baustellen kann es erforderlich sein horizontale Flächen für päzise Planierarbeiten und das gezielte Abziehen von Erdmaterial und Schutt auf Oberflächen zu erstellen. Gelegentlich ist eine größere ebene Fläche mit einem geringen Neigungswinkel (ca. 2° bis 5°) erforderlich, wie einer sehr gering bis moderat geneigten Fläche einer längeren Tiefgaragenausfahrt, einer Rampe oder eine anderweitige Auffahrt für Fahrzeuge. Für solche Arbeiten genügt es einen Punkt sowie einen Neigungswinkel zu definieren und das Erdreich mit einem Planierschild abzuziehen.

Eine rein horizontale Ebene ohne Neigung (Neigungswinkel 0°) kann im betrieblichen Alltag der Baustelle zum Beispiel eine größere Bodenplatte sein, die sich als Fläche leicht durch Linien als Begrenzung abstecken lässt. 


## Fläche aus zwei Punkten und einem Winkel erstellen

Um eine Zwei-Punkt-Fläche zu erstellen, müssen Sie zwei Punkt erfassen und speichern sowie die Werte zur Steigung in % nach Werkzeugrichtung / Himmelsrichtung und Höhenversatz in cm / m nach vertikal / orthogonal angeben.
Mit dieser Funktion können Sie eine Fläche (zum Beispiel die gewünschte Planierfläche) aus zwei von Ihnen ausgewählten Punkten und einem Neigungswinkel erschaffen. Sie können zudem die Höhe des zweiten Punktes im Raum an die Höhe des ersten Punktes angleichen, um lediglich eine Flächenneigung in eine Richtung zu garantieren. Legen Sie hierfür den Regler “Höhe angleichen” um. Der Neigungswinkel steht orthogonal (d.h. 90° nach rechts) zu dem Richtungsvektor von Punkt 1 zu Punkt 2.

Dies soll folgendes Beispiel erläutern: Sie haben zwei Punkte A und B eingemessen, wobei A als Punkt 1 und B als Punkt 2 in der Flächenerstellung ausgewählt wurde. Wenn Sie nun von Punkt A zu Punkt B schauen, steigt die Fläche nach rechts im eingegebenen Neigungswinkel an.
Hinweis: Eine Fläche kann im Raum erst durch mind. drei Punkte eindeutig definiert werden, daher sind weitere Angaben zur Lagebestimmung erforderlich.

**Beispiel: Fläche aus zwei Punkten und einem Winkel erstellen**

Für den Sachverhalt einer Fläche aus zwei Punkten und einem Winkel gilt prinzipiell das gleiche wie für die Erstellung einer fläche über einen Punkt und einen Neigungswinkel. Da die Neigung bereits über zwei Punkte definiert wurde, können Nutzer darüberhinaus einen weiteren Neigungswinkel als Steigung definieren. Hierdurch lässt sich eine Fläche im dreidimensionalen Raum exakt beschreiben und ähnlich wie im vorherigen Beispiel eine ebene Fläche für spezielle Bauarbeiten, wie das Erstellen von Rampen und Gefällen, anlegen.

Selbstverständlich sind auch Zwei-Punkt-Flächen mit einem Neigungswinkel von 0° (folglich horizontal) möglich, beispielsweise für das Anlegen eines Kanal- oder Rohrleitungsgrabens. Der erste Punkt markiert den Beginn der Rohrunterkante, der zweite Punkt markiert das Ende der Rohrunterkante. Der Neigungswinkel beträgt im Beispiel 0°, die Linie visualisiert dabei die geplante Rohrleitung und ist folglich auf einer horizontalen Ebene.  


## Fläche aus drei Punkten erstellen

Um eine Drei-Punkt-Fläche zu erstellen, müssen Sie drei Punkte erfassen und speichern. Nachdem Sie drei Punkte erfasst haben, können Sie eine Fläche (zum Beispiel die gewünschte Planierfläche) aus den von Ihnen ausgewählten Punkten erschaffen. Eine Fläche im Raum ist durch drei Punkte eindeutig definiert. Als Punkte bieten sich zum Beispiel drei Eckpunkte an.

Ebenfalls lässt sich eine größere geneigte Fläche, wie eine moderat ansteigende Auffahrt zu einem Wohnhaus mithilfe einer Drei-Punkt-Fläche erstellen. Ein Punkt befindet sich beispielsweise an der Schwelle zur Garage, zwei weitere Punkte an der Schelle ur Straße, um die Ausmaße (Länge und Breite der Fläche) und den Neigungswinkel für das Gefälle zu bestimmen. 

BACKLOG -->