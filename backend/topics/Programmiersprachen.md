[&#8592; Zurück zur Übersicht](..)

# Programmiersprachen

## Auflistung

- [PHP](#php)
- [C#](#c)

## PHP 

### Allgemein

- Open Source-Skriptsprache
- Speziell für die Webprogrammierung
- Einfach für Neueinsteiger
- Großer Funktionsumfang
- Code auf Server ausgeführt. Dort wird HTML-Ausgabe generiert und an Client gesendet
- Client erhält lediglich das Ergebnis der Skriptausführung
- Benötigt [Apache](capstone-project/backend/topics/Webserver.md#Apache) als Webserver

### Fähigkeiten

- HTML in PHP einbettbar
- Generieren von Bildern, PDF-Dateien und Flashanimationen
- Möglichkeit prozedural oder objektorientiert zu programmieren
- Jede Art von Text ausgebbar
- Dateien automatisch generieren und im Dateisystem speichern
- Unterstützung für eine breite Masse von Datenbanken
-  unterstützt auch die Instantiierung von Java-Objekten

### Hauptanwendungen

#### Serverseitige Programmierung

- Hauptfeld von PHP
- Benötigt: PHP-Parser (CGI oder Server-Modul); Webserver; Webbrowser
- Zugriff auf Ausgabe des PHP-Programms per Webbrowser
- Seite mithilfe des Servers dargestellt

#### Kommandozeilenprogrammierung

- Skripte schreiben, die ohne Server oder Browser arbeiten
- Benötigt nur PHP-Parser

#### Desktop-Applikationen

- Eher für Experten
- Benötigt PHP-GTK Erweiterung
- Es gibt bessere Sprachen für Anwendungen mit grafischer Oberfläche
- Falls von Interesse hier ein Link zur [PHP-GTK Seite](http://gtk.php.net/)

### Vorteile

- Kompatibilität: Kann beinahe überall gehosted werden
- Plattformunabhängig
- Anfragen in Apache sind isoliert --> "bad requests" bringen nicht den kompletten Server down
- Gute, moderne Frameworks


### Bibliotheken

- Standard SPL: Sammlung von Interfaces und Klassen für Standardprobleme. Bedarf ab PHP 5.0.0 keine Erweiterung
- Folgend einige Blogs mit weiteren interessanten libraries:
  - [tutorialzine](https://tutorialzine.com/2013/02/24-cool-php-libraries-you-should-know-about)
  - [programmableweb](https://www.programmableweb.com/news/15-best-php-libraries-every-developer-should-know/analysis/2015/11/18)

### Interessante Links

- [Youtube Tutorial](https://www.youtube.com/playlist?list=PLNmsVeXQZj7rZMP1lj32Qyp4bkarvzCGm)
- [PHP Handbuch](http://php.net/manual/de/index.php)
- [Datenbankerweiterungen](http://php.net/manual/de/refs.database.php)
- [Funktionsreferenzen](http://php.net/manual/de/funcref.php)

## C#

### Allgemein

- typsichere, objektorientierte Allzweck-Programmiersprache 
- als Visual C# im Zusammenhang mit dem .NET Framework genutzt
- Anwendungen für Linux, macOS und Android erstellbar
- Entwicklungsumgebung: [Visual Studio 2017](https://visualstudio.microsoft.com/de/vs/)
- Wichtigstes Framework: .NET

### Fähigkeiten

- Vielzahl sicherer und robuster Anwendungen erstellbar
- Erweiterter Code-Editor mit integrierte Debugger (Bei Visual C#)
- unterstützt generische Methoden
- Konzepte der Kapselung, Vererbung und Polymorphie

### Hauptanwendungen

- Klassische Windows-Forms-Anwendungen (einfach zu erstellende, grafische Benutzeroberflächen und ereignisorientierte Programmierung)
- Moderne WPF-Anwendungen mit XAML (Desktopclientanwendungen)
- Datenbankanwendungen mit lesendem und schreibendem Zugriff auf unterschiedliche Datenbanken. (per ADO.NET Framework)
- Dynamische Internetanwendungen, bei denen die Webseiten als interaktive Benutzeroberflächen dienen (per ASP.NET Framework)

### Vorteile

- Plattformunabhängig
- Guter Support
- Viele Online-Dokumente durch Microsoft zur Verfügung gestellt
- Ähnlich zu Java und anderen C-Typ-Sprachen (schnell zu adaptieren, wenn man eine der Sprachen kann)
- Beinhaltet Features, die nicht in Java enthalten sind


### Bibliotheken

Viele verschiedene [Bibliotheken](https://en.wikipedia.org/wiki/List_of_.NET_libraries_and_frameworks#Libraries_and_frameworks) gibt es in dem Wikipedia-Artikel zu C#

### Interessante Links

- [C#-Leitfaden](https://docs.microsoft.com/de-de/dotnet/csharp/)
- [C# Fundamentals for Beginner](https://mva.microsoft.com/en-US/training-courses/c-fundamentals-for-absolute-beginners-16169?l=Lvld4EQIC_2706218949)
- [Einstieg in C# für Programmierer](https://mva.microsoft.com/de-de/training-courses/einstieg-in-c-fr-programmierer-8826)

## Quellen

- https://www.upwork.com
- http://www.php.net/
- https://www.it-treff.de
- https://www.gulp.de
- https://mva.microsoft.com
