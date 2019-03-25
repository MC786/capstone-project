# Datenzugriff & -verwaltung

### MySQL
•	Relationales DB Verwaltungssystem
•	Open-Source & Plattformunabhängig
•	Häufiger Einsatz von MySQL in Verbindung mit dem Webserver Apache und der Skriptsprache PHP: leichte Bedienung über die Webanwendung phpMyAdmin
•	Grundlagen für dynamische Webseiten: Blogs, Bildergalerien, online Shops
Bsp.: MySQL ist Grundvoraussetzung zur Nutzung von Wordpress → Verwaltung von Artikeln, Userkommentaren oder Medien 
Weitere Anwendungsgebiete: Börsenkurse, Wettervorhersagen, Suchmaschine 
•	Wird u.A. häufig für Flickr, YouTube, Facebook und Twitter verwendet → Visualisierung, Analyse und Vermarktung von Nutzerdaten 
•	Sonstige Anwendungen finden in eingebetteten DB statt: Kleine Systeme, nach außen nicht sichtbar

### PostgreSQL
•	Beliebte Anwendung von vielen Entwicklern in Großunternehmen und Start-ups
•	Häufiger Einsatz im Bereich der mobilen Anwendungen und Geodatenanwendungen (Erweiterungen durch Dritthersteller: PostGIS)   
•	freies objektrelationales DBMS
Basiert auf Objektdatenbankmodell (Objekte im Sinne der Objektorientierung) und auf Relationen zwischen den Tabellen 
•	In den meisten Linux Dis. standardmäßig vorhanden und wird ab Version MAC OS X Lion (10.7) mitgeliefert
•	Großer Spektrum an Fähigkeiten
Hochverfügbarkeit, Erweiterbarkeit, moderne SQL Features
•	Es basiert auf einem Client-Server-Modell
Kommunikation zwischen client und postmaster (Serverprogramm von PostgreSQL), wobei unterschiedliche client-Programme genutzt werden. 
•	Internationaler Support 24/7 durch CyberTec


### SQLite
SQLite ist eine gemeinfreie Programmbibliothek, die ein relationales Datenbanksystem enthält. Sie unterstützt einen Großteil der im SQL-92-Standard festgelegten SQL-Sprachbefehle. Unter anderem implementiert SQLite Transaktionen, Unterabfragen, Sichten, Trigger und benutzerdefinierte Funktionen. SQLite wird häufig für Anwendungen in Android oder auch Browseranwendungen verwendet. Hierbei kommen meistens eingebettete Datenbanksysteme zum Einsatz. SQlite unterstützt eine direkte Integration der Anwendungsbibliothek weswegen keine andere Server Software benötigt wird. Der große Vorteil von SQLite basiert darauf, dass die komplette Datenbank aus nur einer Datei besteht welche eine Größe von ca. 100KB besitzt. Dadurch kann der Austausch der kompletten Daten zwischen Systemen einfacher und schneller erfolgen.

### mongo DB
•	Dokumentenorientierte NoSQL DB, die in der Sprache C++ geschrieben ist
•	Daten werden zunächst im RAM abgelegt und nach einer bestimmten Zeit mit dem Dienst mmap auf die Disk verschoben 
+ Geschwindigkeitsvorteil
– Beim Absturz im RAM gehen vorh. Daten verloren
•	MongoDB kann den Datenbestand und die Arbeitslast auf mehrere Server verteilen
•	Bietet Zahlreiche kostenlose GUIs zur Sichtung und Bearbeitung der Daten 
•	Bekannte Anwender
Die Webpräsenz von MTV Networks
Disney Interactive Media Group
Foursquare
The New York Times
SourceForge


### Firebase Realtime DB
Firebase ist eine Entwicklungs-Plattform für mobile und Webanwendungen. Sie stellt über ein Software Development Kit Tools und Infrastruktur zur Verfügung, die es einem Entwickler ermöglichen sollen, einfacher und effizienter Funktionen mittels Programmierschnittstellen auf verschiedenen Plattformen bereitzustellen. Die Firebase Realtime Datenbank ist Cloud basiert und zentriert. Durch zusätzliche Real-Time-Sync werden die Zugriffzeiten minimal und der Informationsunterschied der einzelnen Benutzer läuft gegen 0. Jeder Benutzer hat jedoch auch die Möglichkeit sich eine Kopie der aktuellen zentrierten Datenbankn zu machen und sich diese Lokal zu speichern.Zum Beispiel bei nicht dauerhafter Connection zum Server.

[Informationsvideo zu Firebase Realtime DB](https://www.youtube.com/watch?v=U5aeM5dvUpA&index=24&list=PLI-K7zZEsYLmOF_07layrTntevxtbUxDL)

### Contentful DB
Contentful ist ein Content Management System (CMS) für Entwickler. Anders als traditionelle CMS Anbieter konzentriert sich Contentful auf API, und macht es mithilfe von strukturierten Daten und der Trennung von Inhalts- und Präsentationsschicht für Unternehmen so möglich, Content in Web- und Mobile-Apps zu integrieren. Contentful DB benutzt die Cloud-Server von Amazon (AWS). Der Service bietet eine benutzerfreundliche Erstellung der Datenbank. Es ermöglicht die Datenstruktur selbst zu deklarieren.  Dadurch wird die Darstellung auf verschiedenen Geräten vereinfacht und die Kosten bei neuen Innovationen der Darstellungen gesenkt. Contentful bietet sich besonders bei einer komplett neuen Datenbank an, da hier besonders die Datenstrukturordnung eingehalten werden kann. In Kombination mit anderen Servicen von Contenful lassen sich alle Abläufe zwischen Frontend- und Backend-Entwicklung leicht verbinden.

[Contentful in a nutshell](https://www.contentful.com/developers/bits-and-bytes/#)

### Redis
• In-Memory-Datenbank mit einer Schlüssel-Werte-Datenstruktur 
• höhere Zugriffsgeschwindigkeiten 
• besser für die Vorhersagbarkeit
• Schneller als Relationale Datenbanken 
• Teuer in Verhältnis zur Datenmenge 
• Daten gehen verloren wenn das System abstürzt 
Schnappschuss-Dateien / Protokolldateien erstellen

### GraphQL
GraphQL ist eine Open-Source-Datenabfrage- und Manipulationssprache und ein Laufzeitsystem zum Ausfüllen von Abfragen mit vorhandenen Daten. GraphQL wurde 2012 von Facebook intern entwickelt und 2015 veröffentlicht. GraphQL bietet eine leistungsfähigere Alternative zu REST. Es lässt nämlich die Datenstruktur anpassen, wodurch die Größe der Daten eingeschränkt werden kann und die komplexität jeder einzelnen Abfrage sinkt. Außerdem wird die Datenbank per Echtzeit-Updates gesynct und alle gängigen Programmiersprachen wie JavaScript, Python, Ruby, C# usw. werden akzeptiert und können in den Prozess integriert werden.

[GraphQL Vorteile](https://www.youtube.com/watch?v=62aGtOmXqp4)
[Vergleich GraphQL vs. REST](https://www.howtographql.com/basics/1-graphql-is-the-better-rest/)

### Apollo
Apollo Client bietet die Möglichkeit mit GraphQL Client-Anwendungen zu erstellen. Der Client wurde entwickelt, um dem Benutzer zu helfen, schnell eine Benutzeroberfläche zu erstellen, die Daten mit GraphQL abruft und mit jedem JavaScript-Frontend verwendet werden kann. Mithilfe von Apollo kann man sehen wer alles Zugang zu der Datenbank hat, wann er die Daten abgerufen hat und welche Daten der User aufgerufen hat. GraphQL bietet somit eine simple Verbindung zwischen Front- und Backend-Entwicklung. 

## Autoren

| Name | E-Mail | Änderungsdatum |
|:-----|:-------|:---------------|
|      |        |                |
| Sebastian Kah | skah@smail.uni-koeln.de | 24.03.2019 |
| Muzamal Cheema| mcheema1@smail.uni-koeln.de|25.03.2019|
