# Blazor WebAssembly App

Dieses Projekt ist eine Blazor WebAssembly-Anwendung, die aus einem Client, einem Server und einem gemeinsamen Projekt besteht. 

## Projektstruktur

- **BlazorWebAssemblyApp.Client**: Enthält die Client-Anwendung, die in Blazor WebAssembly geschrieben ist.
  - **wwwroot/appsettings.json**: Konfigurationseinstellungen für die Client-Anwendung.
  - **Pages**: Enthält die Razor-Komponenten der Anwendung.
    - **Counter.razor**: Eine Komponente, die einen Zähler anzeigt und die Möglichkeit bietet, den Zähler zu erhöhen oder zu verringern.
    - **FetchData.razor**: Eine Komponente, die Wetterdaten von einem Server abruft und anzeigt.
    - **Index.razor**: Die Hauptseite der Anwendung und Einstiegspunkt für die Benutzeroberfläche.
  - **Program.cs**: Einstiegspunkt der Client-Anwendung, konfiguriert und startet die Blazor WebAssembly-Anwendung.
  - **App.razor**: Definiert die Hauptkomponente der Anwendung und enthält die Router-Konfiguration.
  - **BlazorWebAssemblyApp.Client.csproj**: Projektdatei für die Client-Anwendung.

- **BlazorWebAssemblyApp.Server**: Enthält die Server-Anwendung, die die API bereitstellt.
  - **Controllers/WeatherForecastController.cs**: Definiert einen Controller, der Wettervorhersagedaten bereitstellt.
  - **Program.cs**: Einstiegspunkt der Server-Anwendung, konfiguriert und startet den Webserver.
  - **Startup.cs**: Konfiguration für die Middleware und die Dienste der Server-Anwendung.
  - **appsettings.json**: Konfigurationseinstellungen für die Server-Anwendung.
  - **BlazorWebAssemblyApp.Server.csproj**: Projektdatei für die Server-Anwendung.

- **BlazorWebAssemblyApp.Shared**: Enthält gemeinsam genutzte Klassen und Modelle.
  - **WeatherForecast.cs**: Definiert die Struktur der Wettervorhersagedaten.
  - **BlazorWebAssemblyApp.Shared.csproj**: Projektdatei für das gemeinsame Projekt.

- **BlazorWebAssemblyApp.sln**: Lösung für das gesamte Projekt, enthält Verweise auf die einzelnen Projekte.

## Verwendung

Um die Anwendung auszuführen, stellen Sie sicher, dass alle Abhängigkeiten installiert sind und verwenden Sie die entsprechenden Befehle, um den Client und den Server zu starten. 

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz.