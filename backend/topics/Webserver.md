[&#8592; Zurück zur Übersicht](..)

# Webserver

<img src="https://blog.botfrei.de/wp-content/uploads/2013/01/6_Abbildung-2-3-1.jpg" alt="Kommunikation zwischen Client und Webserver" width="450" align="right">

## Definition / Allgemeines
Ein Webserver ist ein Server, der **Anfragen** über das Internet von Webclients/Browsern annimmt und Daten und Inhalte zum Abrufen bereitstellt.

## Arbeitsweise
Der Client stellt eine HTTP-Anfrage an den Server: `GET https://www.example.com`. <br>
Statische Webseiten (HTML-Dateien) werden direkt vom Webserver an den Client ausgeliefert. <br>
Wenn es sich um eine **dynamische Seite** handelt (bsp. PHP-Dateien), wird ein zusätzliches Modul benötigt, dass das entsprechende Skript ausführt und die Inhalte erst beim Aufruf aus **unterschiedlichen Quellen** zusammengestellt.

## Gängige Webserver
<p align="center">
<img src="../images/Marktanteil_Webserver.png" alt="Marktanteil von Webservern" width="350">
</p>

Es gibt einige verschiedene Webserver-Software. Jedoch werden im Folgenden nur die beiden dominierenden Server betrachtet.<br>
Es ist erkennbar, dass der **Apache**-Server weltweit am häufigsten verwendet wird, dicht gefolgt vom **NGINX**-Server. Allerdings findet NGINX bei Websiten, die viel Traffic vorzuweisen haben, signifikant mehr Anwendung als alle anderen.

### Apache
<img align="right" src="https://www.apache.org/foundation/press/kit/asf_logo.svg" alt="Apache-Logo" width="190">

- einer der ältesten und meistbenutzten Webserver
- erste Version: 1995
- Entwickler: [Apache Software Foundation](http://www.apache.org/)
- Open-Source, kostenfrei
- läuft auf allen gängigen Betriebssystemen
- kann durch viele 

### NGINX
<p> <img align="right" src="https://upload.wikimedia.org/wikipedia/commons/c/c5/Nginx_logo.svg" alt="NGINX-Logo" width="190">
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Si sapiens, ne tum quidem miser, cum ab Oroete, praetore Darei, in crucem actus est. Sunt enim prima elementa naturae, quibus auctis vírtutis quasi germen efficitur. Eam si varietatem diceres, intellegerem, ut etiam non dicente te intellego; <i>Id enim natura desiderat.</i> Beatus autem esse in maximarum rerum timore nemo potest. 
</p>

## Quellen
- [botfrei Blog: "Know-How: Was ist ein Webserver?"](https://blog.botfrei.de/2013/01/webserver-die-qual-der-wahl/) (abgerufen am 20.03.2019)
- [Netcraft: "February 2019 Web Server Survey"](https://news.netcraft.com/archives/2019/02/28/february-2019-web-server-survey.html) (abgerufen am 20.03.2019)

## Autoren
| Name       | E-Mail                    | Änderungsdatum |
|------------|---------------------------|----------------|
| Felix Graf | fgraf4@smail.uni-koeln.de | 20.03.2019     |
