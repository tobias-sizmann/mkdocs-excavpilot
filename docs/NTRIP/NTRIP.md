<style>
    setCenter{
        justify-content: center;
    }
</style>
# NTRIP

## Was ist NTRIP?

NTRIP steht für Networked Transport of RTCM via Internet Protocol und ist ein gängiges Verfahren zur Bereitstellung von RTK-Korrekturdaten über das Internet. Die erreichbare **Lagegenauigkeit** wird je nach Korrekturdatendienstleister mit **ca. 1 - 3 cm** angegeben.

## Was brauche ich für die Nutzung von NTRIP?

Sie benötigen eine SIM-Karte mit ausreichend Datenvolumen für den **Zugang zu mobilem Internet** und einen professionellen **Dienstleister für die Bereitstellung von RTK-Korrekturdaten**. 

excav bietet eine eigene [Roaming SIM-Karte](https://excav.de/produkte/) an, die europaweit nutzbar ist und automatisch das beste Netz auswählt. Die SIM-Karte ist sowohl monatlich aktivierbar als auch deaktivierbar.


## RTK-Korrektur: Empfehlung - SAPOS Heps

Die Arbeitsgemeinschaft der Vermessungsverwaltungen der Länder der Bundesrepublik Deutschland (AdV) bietet mit **SAPOS Heps** einen hochgenauen und kostengünstigen Echtzeit-RTK-Korrekturdaten-Service an.

Für jedes Bundesland stehen eigene SAPOS Heps Dienste zur Verfügung. Sie können mit dem jeweiligen Dienst entsprechend Korrekturdaten nur für das betreffende Bundesland beziehen.

Einen für die bundesweite Nutzung vorgesehenen SAPOS Heps Dienst stellt die Zentrale Stelle SAPOS (ZSS) über das Landesamt für Geoinformation und Landesvermessung mit Standort in Niedersachsen zur Verfügung.

In der folgenden Auflistung gelangen Sie zu den Übersichtsseiten der bundesweit zentralen SAPOS-Stelle sowie zu den zuständigen untergeordneten Stellen der einzelnen Bundesländer:

- Bundesrepublik Deutschland (bundesweite SAPOS-Nutzung): [Zentrale Stelle SAPOS®](https://zentrale-stelle-sapos.de/)

- Baden-Württemberg - [Satellitenpositionierungs-Dienst SAPOS® Baden-Württemberg](https://www.lgl-bw.de/unsere-themen/Geoinformation/Geodaetischer-Raumbezug/Satellitenpositionierungsdienst/)

- Bayern - [Satellitenpositionierungs-Dienst SAPOS® Bayern](https://www.ldbv.bayern.de/produkte/dienste/sapos.html)

- Berlin - [Satellitenpositionierungs-Dienst SAPOS® Berlin](https://www.berlin.de/sen/sbw/stadtdaten/geoinformation/landesvermessung/raumbezug/sapos/)

- Brandenburg - [Satellitenpositionierungs-Dienst SAPOS® Brandenburg](https://geobasis-bb.de/lgb/de/geodaten/raumbezug-sapos/)

- Hamburg - [Satellitenpositionierungs-Dienst SAPOS® Hamburg](https://www.hamburg.de/politik-und-verwaltung/behoerden/behoerde-fuer-stadtentwicklung-und-wohnen/aemter-und-landesbetrieb/landesbetrieb-geoinformation-und-vermessung/produkte-und-dienstleistungen/geodaten-des-lgv/sapos-244122)

- Hessen - [Satellitenpositionierungs-Dienst SAPOS® Hessen](https://hvbg.hessen.de/landesvermessung/geodaetischer-raumbezug/saposr)

- Mecklenburg-Vorpommern - [Satellitenpositionierungs-Dienst SAPOS® MVP](https://www.laiv-mv.de/Geoinformation/Raumbezug/Satellitenpositionierungsdienste/)

- Niedersachsen / Bremen - [Satellitenpositionierungs-Dienst SAPOS® Niedersachsen/Bremen](https://www.lgln.niedersachsen.de/startseite/online_angebote_amp_services/webdienste/sapos/sapos-services-und-bereitstellung-143814.html)

- Nordrhein-Westfalen - [Satellitenpositionierungs-Dienst SAPOS® NRW](https://www.bezreg-koeln.nrw.de/geobasis-nrw/produkte-und-dienste/raumbezug/satellitenpositionierungsdienst-sapos)

- Rheinland-Pfalz - [Satellitenpositionierungs-Dienst SAPOS® Rheinland-Pfalz](https://lvermgeo.rlp.de/ueber-uns/unsere-aufgaben/vermessungstechnischer-raumbezug/saposr)

- Saarland - [Satellitenpositionierungs-Dienst SAPOS® Saarland](https://www.saarland.de/lvgl/DE/themen-aufgaben/themen/grundlagen/sapos/sapos.html)

- Sachsen - [Satellitenpositionierungs-Dienst SAPOS® Sachsen](https://www.landesvermessung.sachsen.de/sapos-sachsen-7213.html)

- Sachsen-Anhalt - [Satellitenpositionierungs-Dienst SAPOS® Sachsen-Anhalt](https://www.lvermgeo.sachsen-anhalt.de/de/sapos-in-sachsen-anhalt/sapos-in-sachsen-anhalt.html)

- Schleswig-Holstein - [Satellitenpositionierungs-Dienst SAPOS® Schleswig-Holstein](https://sapos.geonord.de/index.php)

- Thüringen - [Satellitenpositionierungs-Dienst SAPOS® Thüringen](https://tlbg.thueringen.de/geobasisdaten/raumbezug/sapos)

Es gibt weitere national sowie zum Teil international tätige Anbieter, welche in speziellen Anwendungsfällen, wie in Grenznähe zu anderen Staaten oder bei grenzüberschreitenden Projekten im Bau, kostengünstig und hilfreich sind.

## Wie verbinde ich mich mit NTRIP?

<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht Start 2.png"/>
</p>
<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht NTRIP 1 2.png"/>
</p>
<p align="center" width="100%">
  <img width="100%" src="/images_docs/Screenshot excav PILOT Arbeitsansicht NTRIP 2.jpg"/>
</p>

Über den Button "Hinzufügen" können Sie eine neue NTRIP-Verbindung anlegen. Sie erhalten nachfolgend eine Erklärung zu allen relevanten Eingaben:

**NTRIP-Daten**

- Bezeichnung: Individuell wählbar - unter welchem Namen soll die NTRIP-Verbindung abgespeichert werden?

- DNS: Domain Name System: Die Internet-Adresse des NTRIP-Casters - wird Ihnen von Ihrem Korrekturdatendienstleister bei Registrierung mitgeteilt;
  Wichtig: Hier den Domain-Namen eingeben (z.B. für SAPOS Deutschland: www.sapos-ntrip.de) und nicht die IP-Adresse

- Port: numerische Adresse auf dem NTRIP-Caster - wird Ihnen von Ihrem Korrekturdatendienstleister bei Registrierung mitgeteilt (für SAPOS: 2101)

- Mountpoint: Kennung des Korrekturdatenstroms - wird Ihnen von Ihrem Korrekturdatendienstleister bei Registrierung mitgeteilt (für SAPOS: VRS_3_4G)

- Username: Der Ihnen von Ihrem Korrekturdatendienstleister zugewiesene Nutzername

- Passwort: Das Ihnen von Ihrem Korrekturdatendienstleister zugewiesene Passwort

- Latitude: Breitengrad Ihrer Baustelle; Tipp: Schalten Sie den Sensor an und drücken Sie nach Signalaufbau den Button rechts neben der Eingabe, um Ihre aktuelle Position zu erfassen.

- Longitude: Längengrad Ihrer Baustelle; Tipp: Schalten Sie den Sensor an und drücken Sie nach Signalaufbau den Button rechts neben der Eingabe, um Ihre aktuelle Position zu erfassen.

<br>

<p align="center" width="100%">
  <img width="100%" src="/images_docs/NTRIP4.jpg"/>
</p>

In der Kopfleiste befindet sich ganz rechts das Icon zur Darstellung des NTRIP-Empfangs. Die verschiedene Farbgebung weist auf den aktuellen Status der NTRIP-Verbindung hin.

Grau &nbsp;&nbsp; - &nbsp;&nbsp; <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid grey; display: inline-block; margin-right: 8px;"></span>
      <span>:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Keine Verbindung (z.B. keine Internetverbindung oder kein Caster verbunden)</span>
</span>

Blau &nbsp;&nbsp; - &nbsp;&nbsp;  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid blue; display: inline-block; margin-right: 8px;"></span>
      <span>:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Aufbau der Verbindung ist gescheitert</span>
</span>

Rot &nbsp;&nbsp;&nbsp; - &nbsp;&nbsp;&nbsp;  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid red; display: inline-block; margin-right: 8px;"></span>
      <span>:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Aufbau der Verbindung ist gescheitert</span>
</span>

Grün &nbsp;&nbsp; - &nbsp;&nbsp;  <span style="display: inline-flex; align-items: center;">
      <span style="width: 12px; height: 12px; border-radius: 50%; border: 1px solid lightgreen; display: inline-block; margin-right: 8px;"></span>
      <span>:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Erfolgreich verbunden und aktiv</span>
</span>
