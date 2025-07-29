# NetCompanion App

**NetCompanion** ist eine native iOS-App für Nutzer von Netatmo-Wetterstationen. Sie bietet eine schnelle, werbefreie und datenschutzfreundliche Möglichkeit, alle Module im Überblick zu behalten – inklusive Temperaturverlauf und Statusinformationen aller Module.

---

## 🚀 Funktionen

- Übersichtliche Anzeige aller Module (z. B. Innenraum, Außenmodul, Regenmesser) mit Kacheldesign
- Schnell erkennbare Statusanzeigen (Temperatur, Luftfeuchtigkeit, Batteriestand, Funkverbindung)
- Anzeige (je nach Modultyp) von:
  - Temperatur
  - Luftfeuchtigkeit
  - CO₂-Gehalt
  - Lärm
  - Luftdruck
  - Niederschlag
  - Windgeschwindigkeit
  - Batteriestatus
  - Verbindungsstatus
- Diagramme für Temperaturverläufe:
  - Tages-, Wochen- und Monatsansicht
- Premium-Freischaltung via StoreKit 2
  - Einmalkauf oder Abo
- WidgetKit-Integration: Daten direkt auf dem Homescreen
- Login via OAuth2 und Token (Apple Keychain-basiert, keine Passworteingabe notwendig)
- Datenschutzfreundlich – keine Datenweitergabe

---

## 🎯 Fokus

Der Fokus liegt besonders auf einer **klaren Benutzerführung**, einer **modernen Darstellung mit SwiftUI** und der **ansprechenden Visualisierung von Messwerten** (Temperatur, Luftfeuchtigkeit, Regen, CO₂ etc.) über verschiedene Zeiträume hinweg.

---

## 🛠️ Verwendete Technologien

- **Swift** & **SwiftUI**
- **StoreKit 2** für In-App-Käufe
- **Keychain** für sichere Token-Speicherung
- **WidgetKit** für iOS-Homescreen-Widgets
- **Swift Charts** für Diagramme
- **URLSession** mit `async/await` zur API-Kommunikation
- **OSLog** für strukturierte App-Logs

---

## 📸 Screenshots

### 📋 Hauptansicht
Zeigt alle verfügbaren Netatmo-Module als übersichtliche Kacheln.

![Main List View](Assets/mainListView.png)

---

### 📈 Detailansicht – Temperatur (Tag)
Ein Modul in der Tagesansicht mit Temperaturverlauf als Liniendiagramm.

![Detail View – Tag](Assets/detailView.png)

---

### 🌧️ Regenmodul – Tagesansicht mit Bar-Chart
Regenmengen pro Stunde als Balkendiagramm.

![Rain Detail View](Assets/rainDetailView.png)

---

### 📅 Wochen- und Monatsverlauf

#### Wochenansicht (Temperaturverlauf)
![Week Detail View](Assets/weekDetailView.png)

#### Monatsansicht (mit Höchst- und Tiefsttemperatur pro Tag)
![Month Detail View](Assets/monthDetailView.png)

#### Monatsansicht mit aktivem Popover (Drag-Geste)
![Month Detail View with Drag](Assets/monthDetailViewDragGesture.png)

---

## 🎥 Demo (GIF)

Hier folgt ein animiertes GIF, das einen kurzen Ablauf durch die App zeigt:

![App Demo GIF](Assets/demo.gif)


*Live-Demo ohne Geräte-Rahmen (Bezel)*


---

## 🎯 Motivation

Ich habe NetCompanion als native Alternative zur Web- oder Hersteller-App entwickelt, um meine eigene Netatmo-Wetterstation sinnvoll auszuwerten. Dabei lag der Fokus darauf, moderne SwiftUI-Techniken mit echten APIs, sicherer Tokenverarbeitung und Apple-Frameworks wie StoreKit 2, Charts und WidgetKit sinnvoll zu verknüpfen.

Aktuell arbeite ich an einer Veröffentlichung im App Store.

---

## 📂 Hinweis zum Repository

> Dieses Repository dient aktuell nur der **Präsentation** meiner App und der **Visualisierung** des Projekts für Interessierte, potenzielle Auftraggeber oder Teams.  
> Der Quellcode ist nicht öffentlich.  
> Bei Interesse an einer technischen Zusammenarbeit → gerne Kontakt aufnehmen.

---

## 🧑‍💻 Autor

**Marco Witt**  
iOS-Developer | SwiftUI-Enthusiast  
[LinkedIn](https://www.linkedin.com/in/marco-witt-1265301b6)
