[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?[https://github.com/smn-hrtzsch/MMK/edit/main/tools_for_ui_design.md](https://github.com/smn-hrtzsch/MMK/blob/main/tools_for_ui_design.md))

# Exposé-Vortrag: UI Design Frameworks & Tools

| Parameter             | Kursinformationen                                                         |
| ----------------------| --------------------------------------------------------------------------|
| **Veranstaltung:**    | `Mensch-Maschine-Kommunikation`                                           |
| **Semester**          | `Sommersemester 2025`                                                     |
| **Hochschule:**       | `Technische Universität Berkakademie Freiberg`                            |
| **Inhalte:**          | `Frameworks & Tools für UI-Design`                                        |
| **Link auf GitHub:**  | https://github.com/smn-hrtzsch/MMK/blob/main/tools_for_ui_design.md       |
| **Autoren**           | Björn Muchow, Simon Hörtzsch @author                                      |

+ Gruppenmitglieder: Björn Muchow, Simon Hörtzsch
+ Studiengang: Robotik | Angewandte Informatik
+ Betreuer: Prof. Dr.-Ing. Bernhard Jung, Florian Richter
+ Datum: 25.04.2025

---

## 1. Einleitung: Was ist UI-Design?

**User Interface (UI) Design** ist der Prozess der Gestaltung von Benutzeroberflächen für Maschinen und Software, wie Computer, Haushaltsgeräte, mobile Geräte und andere elektronische Geräte, mit dem Fokus auf **Maximierung der Benutzerfreundlichkeit und des Benutzererlebnisses.**

**Ziel:** Die Interaktion des Benutzers so **einfach, effizient und intuitiv** wie möglich zu gestalten.

**Warum ist gutes UI-Design wichtig?**

* Verbessert die Benutzerzufriedenheit
* Erhöht die Effizienz und Produktivität
* Reduziert Fehlerquoten
* Stärkt die Markenidentität
* Fördert die Akzeptanz des Produkts

![Bild von UI Design Konzept](https://images.unsplash.com/photo-1581291518857-4e27b48ff24e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80)

---

## 2. Design & Prototyping Tools

Diese Werkzeuge helfen Designern, die visuellen Elemente einer Benutzeroberfläche zu erstellen, zu iterieren und zu testen, bevor die eigentliche Programmierung beginnt.

---

### 2.1 Figma

![Logo von Figma](https://upload.wikimedia.org/wikipedia/commons/thumb/3/33/Figma-logo.svg/1667px-Figma-logo.svg.png)

* **Art:** Kollaboratives Interface-Design-Tool
* **Kosten:** Kostenloser Plan verfügbar, kostenpflichtige Pläne für Teams und Organisationen ([Figma Pricing](https://www.figma.com/pricing/))
* **Plattform:** Webbasiert (läuft im Browser), Desktop-Apps für Windows & macOS
* **Erlernbarkeit:** Mittel bis hoch, umfangreiche Community-Ressourcen und Tutorials
* **Vorteile:**
    * Echtzeit-Kollaboration
    * Plattformunabhängig (Web)
    * Starke Vektor-Bearbeitungsfunktionen
    * Umfangreiche Plugin-Ökosystem
    * Gute Prototyping-Funktionen
    * Versionierung integriert
* **Nachteile:**
    * Benötigt Internetverbindung (Offline-Modus begrenzt)
    * Kann bei sehr großen Dateien langsamer werden

---

### 2.2 Sketch

![Logo von Sketch](https://upload.wikimedia.org/wikipedia/commons/thumb/5/59/Sketch_Logo.svg/1024px-Sketch_Logo.svg.png)

* **Art:** Vektorbasiertes UI/UX-Design-Tool
* **Kosten:** Kostenpflichtig (Abonnement-Modell) ([Sketch Pricing](https://www.sketch.com/pricing/))
* **Plattform:** Nur macOS
* **Erlernbarkeit:** Mittel, gilt als relativ intuitiv für Designer
* **Vorteile:**
    * Sehr auf UI/UX-Design fokussiert
    * Starke Symbol- und Design-System-Funktionen
    * Große Auswahl an Plugins
    * Gute Performance bei komplexen Dateien
* **Nachteile:**
    * Nur für macOS verfügbar (starke Einschränkung)
    * Kollaboration weniger nahtlos als bei Figma (obwohl verbessert)
    * Kein kostenloser Plan

---

### 2.3 Adobe XD

![Logo von Adobe XD](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c2/Adobe_XD_CC_icon.svg/1024px-Adobe_XD_CC_icon.svg.png)

* **Art:** UI/UX-Design und Prototyping-Tool
* **Kosten:** Kostenloser Starter-Plan, Teil der Adobe Creative Cloud (kostenpflichtig) ([Adobe XD Plans](https://www.adobe.com/products/xd/plans.html)) - *Hinweis: Adobe hat die Weiterentwicklung von XD weitgehend eingestellt.*
* **Plattform:** Windows & macOS
* **Erlernbarkeit:** Mittel, gute Integration in Adobe-Ökosystem
* **Vorteile:**
    * Nahtlose Integration mit anderen Adobe-Produkten (Photoshop, Illustrator)
    * Gute Prototyping- und Animationsfunktionen (Auto-Animate)
    * Unterstützung für Co-Editing (Kollaboration)
    * Sprachsteuerung für Prototypen
* **Nachteile:**
    * Zukunft unsicher, da Adobe Figma akquiriert hat und XD nicht mehr aktiv weiterentwickelt wird.
    * Plugin-Ökosystem kleiner als bei Figma/Sketch
    * Kostenpflichtig für vollen Funktionsumfang

---

## 3. Programmier-Frameworks: Web UI

Diese Frameworks bieten wiederverwendbare Komponenten und Strukturen zur effizienten Entwicklung von Web-Benutzeroberflächen.

---

### 3.1 React

![Logo von React](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1024px-React-icon.svg.png)

* **Art:** JavaScript-Bibliothek zur Erstellung von Benutzeroberflächen
* **Entwickler:** Meta (Facebook)
* **Kosten:** Frei verfügbar (Open Source, MIT-Lizenz)
* **Plattform:** Web
* **Nutzung:** JavaScript (JSX), TypeScript. Integration in viele IDEs (VS Code, WebStorm etc.)
* **Erlernbarkeit:** Mittel bis hoch, erfordert gutes JavaScript-Verständnis, steile Lernkurve möglich
* **Vorteile:**
    * Komponentenbasiert -> Wiederverwendbarkeit
    * Große Community und Ökosystem (viele Bibliotheken, Tools)
    * Virtuelles DOM für gute Performance
    * Flexibel, kann mit vielen anderen Bibliotheken kombiniert werden
    * React Native ermöglicht Cross-Platform Mobile Entwicklung
* **Nachteile:**
    * Ist "nur" eine Bibliothek, benötigt oft zusätzliche Tools (Routing, State Management)
    * JSX kann anfangs ungewohnt sein
    * Schnelle Entwicklungszyklen können Einarbeitung erfordern

* **Quelle:** [React Website](https://react.dev/)

---

### 3.2 Angular

![Logo von Angular](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Angular_full_color_logo.svg/1024px-Angular_full_color_logo.svg.png)

* **Art:** Umfassendes Web-Anwendungsframework
* **Entwickler:** Google
* **Kosten:** Frei verfügbar (Open Source, MIT-Lizenz)
* **Plattform:** Web
* **Nutzung:** TypeScript. Starke Integration in IDEs.
* **Erlernbarkeit:** Hoch, da sehr umfangreich und "opinionated" (vorgegebene Strukturen)
* **Vorteile:**
    * Vollständiges Framework (Routing, State Management, HTTP-Client etc. integriert)
    * TypeScript als Basis fördert Typsicherheit und Skalierbarkeit
    * Klare Struktur und Architekturvorgaben
    * Gute Performance durch Ahead-of-Time (AOT) Kompilierung
    * Command Line Interface (CLI) für einfache Projekterstellung und -verwaltung
* **Nachteile:**
    * Steilere Lernkurve als React/Vue
    * Weniger flexibel als React
    * Kann für kleine Projekte "Overkill" sein

* **Quelle:** [Angular Website](https://angular.io/)

---

### 3.3 Vue.js

![Logo von Vue.js](https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1024px-Vue.js_Logo_2.svg.png)

* **Art:** Progressives JavaScript-Framework
* **Entwickler:** Evan You & Community
* **Kosten:** Frei verfügbar (Open Source, MIT-Lizenz)
* **Plattform:** Web
* **Nutzung:** JavaScript, TypeScript. Gute IDE-Integration.
* **Erlernbarkeit:** Gering bis mittel, gilt als einsteigerfreundlich
* **Vorteile:**
    * Sehr gute Dokumentation
    * Einfach zu lernen und zu integrieren
    * Flexibel (kann als Bibliothek oder volles Framework genutzt werden)
    * Gute Performance
    * Wachsende Community und Ökosystem
* **Nachteile:**
    * Kleineres Ökosystem und weniger Jobangebote als React/Angular (aber wachsend)
    * Manchmal als weniger "strukturiert" empfunden als Angular

* **Quelle:** [Vue.js Website](https://vuejs.org/)

---

## 4. Programmier-Frameworks: Mobile UI

Werkzeuge zur Erstellung von Benutzeroberflächen für iOS und Android.

---

### 4.1 Native Entwicklung (SwiftUI / Jetpack Compose)

* **SwiftUI (iOS):** Modernes deklaratives UI-Framework von Apple für iOS, macOS, watchOS, tvOS.
    * **Sprache:** Swift
    * **Vorteile:** Neueste Apple-Technologie, gute Performance, nahtlose Integration ins Apple-Ökosystem.
    * **Nachteile:** Nur für Apple-Plattformen.
    * **Quelle:** [Apple Developer - SwiftUI](https://developer.apple.com/xcode/swiftui/)
* **Jetpack Compose (Android):** Modernes deklaratives UI-Toolkit von Google für native Android-Entwicklung.
    * **Sprache:** Kotlin
    * **Vorteile:** Moderner Ansatz, weniger Code, gute Integration ins Android-Ökosystem.
    * **Nachteile:** Nur für Android.
    * **Quelle:** [Android Developers - Jetpack Compose](https://developer.android.com/jetpack/compose)

![Logos von Swift und Kotlin](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9d/Swift_logo.svg/1024px-Swift_logo.svg.png | width=100) ![Logo von Kotlin](https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Kotlin_Icon.png/600px-Kotlin_Icon.png | width=100)

* **Kosten:** Entwicklungstools (Xcode, Android Studio) sind kostenlos.
* **Plattform:** Jeweils spezifisch (iOS oder Android)
* **Erlernbarkeit:** Mittel bis hoch (erfordert Erlernen der jeweiligen Sprache und Plattform-Besonderheiten)
* **Vorteile (Allgemein Native):** Beste Performance, direkter Zugriff auf alle Gerätefunktionen, optimales Plattform-Look-and-Feel.
* **Nachteile (Allgemein Native):** Code muss für jede Plattform separat geschrieben und gepflegt werden (höherer Aufwand/Kosten).

---

### 4.2 Cross-Platform: React Native

![Logo von React Native](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1024px-React-icon.svg.png) * **Art:** Framework zur Erstellung nativer Apps mit React

* **Entwickler:** Meta (Facebook)
* **Kosten:** Frei verfügbar (Open Source, MIT-Lizenz)
* **Plattform:** iOS & Android (aus einer Codebasis)
* **Nutzung:** JavaScript (JSX), TypeScript.
* **Erlernbarkeit:** Mittel (wenn React bekannt ist), erfordert Verständnis für native Konzepte.
* **Vorteile:**
    * Code-Wiederverwendung zwischen iOS und Android (oft 70-90%)
    * Nutzt native UI-Komponenten -> natives Look-and-Feel
    * Große Community (aus der React-Welt)
    * "Hot Reloading" für schnelle Entwicklungszyklen
* **Nachteile:**
    * Performance kann hinter nativer Entwicklung zurückbleiben
    * Zugriff auf sehr spezifische native APIs erfordert manchmal native Module
    * Debugging kann komplexer sein ("Bridge")

* **Quelle:** [React Native Website](https://reactnative.dev/)

---

### 4.3 Cross-Platform: Flutter

![Logo von Flutter](https://storage.googleapis.com/cms-storage-bucket/0dbf93e93ead32995039.png)

* **Art:** UI-Toolkit von Google zur Erstellung nativer Apps aus einer Codebasis
* **Entwickler:** Google
* **Kosten:** Frei verfügbar (Open Source, BSD-Lizenz)
* **Plattform:** iOS, Android, Web, Desktop (Windows, macOS, Linux)
* **Nutzung:** Dart. Sehr gute IDE-Integration (VS Code, Android Studio).
* **Erlernbarkeit:** Mittel (Dart ist relativ einfach zu lernen), eigenes UI-Rendering-Konzept.
* **Vorteile:**
    * Sehr gute Performance (kompiliert zu nativem Code)
    * Schnelle Entwicklung mit "Hot Reload/Restart"
    * Kontrolle über jeden Pixel (eigenes Rendering, keine nativen Widgets) -> Konsistentes UI auf allen Plattformen
    * Umfangreiche Widget-Bibliothek (Material Design, Cupertino)
    * Wachsende Community
* **Nachteile:**
    * App-Größe tendenziell größer
    * Dart ist weniger verbreitet als JavaScript
    * Look-and-Feel ist nicht 100% nativ (obwohl sehr nah dran)

* **Quelle:** [Flutter Website](https://flutter.dev/)

---

## 5. Programmier-Frameworks: Desktop UI

Werkzeuge zur Erstellung von Benutzeroberflächen für Desktop-Betriebssysteme.

---

### 5.1 Electron

![Logo von Electron](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Electron_Software_Framework_Logo.svg/1024px-Electron_Software_Framework_Logo.svg.png)

* **Art:** Framework zur Erstellung von Desktop-Anwendungen mit Web-Technologien (HTML, CSS, JavaScript)
* **Entwickler:** GitHub (Teil von Microsoft)
* **Kosten:** Frei verfügbar (Open Source, MIT-Lizenz)
* **Plattform:** Windows, macOS, Linux
* **Nutzung:** JavaScript, TypeScript, HTML, CSS (oft in Kombination mit Web-Frameworks wie React, Vue, Angular).
* **Erlernbarkeit:** Gering bis mittel (wenn Web-Technologien bekannt sind).
* **Vorteile:**
    * Nutzung bekannter Web-Technologien
    * Cross-Platform aus einer Codebasis
    * Große Community und viele bekannte Apps (VS Code, Slack, Discord)
* **Nachteile:**
    * Hoher Ressourcenverbrauch (RAM, CPU), da jede App eine eigene Chromium-Instanz mitbringt
    * Größere Installationsdateien
    * Performance kann hinter nativen Desktop-Apps zurückbleiben

* **Quelle:** [Electron Website](https://www.electronjs.org/)

---

### 5.2 Qt (mit QML)

![Logo von Qt](https://upload.wikimedia.org/wikipedia/commons/thumb/0/0b/Qt_logo_2016.svg/640px-Qt_logo_2016.svg.png)

* **Art:** Umfassendes Cross-Platform Anwendungsframework (nicht nur UI)
* **Entwickler:** The Qt Company & Qt Project
* **Kosten:** Dual-Lizenzierung: Kostenlose Open-Source-Lizenzen (LGPL, GPL), kostenpflichtige kommerzielle Lizenzen für proprietäre Entwicklung. ([Qt Licensing](https://www.qt.io/licensing/))
* **Plattform:** Windows, macOS, Linux, Android, iOS, Embedded Systems
* **Nutzung:** C++, QML (deklarative UI-Sprache), Python (PyQt/PySide). Eigene IDE (Qt Creator).
* **Erlernbarkeit:** Mittel bis hoch (C++ erforderlich für Kernlogik, QML relativ einfach).
* **Vorteile:**
    * Sehr gute Performance (nativ kompiliert)
    * Wirklich Cross-Platform (bis hin zu Embedded)
    * Umfangreiche Module (Netzwerk, Multimedia, Datenbanken etc.)
    * QML ermöglicht einfache Trennung von UI und Logik
    * Lange etabliert und stabil
* **Nachteile:**
    * Komplexe Lizenzierung für kommerzielle Nutzung
    * C++ als Basis kann Einarbeitungshürde sein
    * Look-and-Feel muss ggf. plattformspezifisch angepasst werden

* **Quelle:** [Qt Website](https://www.qt.io/)

---

## 6. Ausblick & Fazit

**Die Wahl des richtigen Werkzeugs/Frameworks hängt stark vom Projekt ab:**

* **Projektgröße & Komplexität:** Kleine Website vs. große Unternehmensanwendung.
* **Zielplattform(en):** Nur Web? Mobile? Desktop? Alles?
* **Team-Know-how:** Welche Sprachen/Technologien kennt das Team bereits?
* **Performance-Anforderungen:** Kritisch oder sekundär?
* **Budget:** Kostenlose vs. kostenpflichtige Tools/Lizenzen.
* **Design-Anforderungen:** Benötigt es Pixel-perfekte Kontrolle oder reicht ein Standard-Look?

**Trends:**

* **Deklarative UI:** Setzt sich immer mehr durch (SwiftUI, Jetpack Compose, React, Vue, Flutter).
* **Cross-Platform:** Bleibt wichtig, um Entwicklungskosten zu senken (React Native, Flutter, Qt, Electron).
* **Design-Systeme:** Werden zentral für konsistente UIs über Produkte und Plattformen hinweg (oft mit Figma oder Sketch erstellt).
* **Kollaboration:** Echtzeit-Zusammenarbeit wird zum Standard (Figma als Vorreiter).

**Empfehlung:**

* **Design:** **Figma** ist oft die beste Wahl wegen Kollaboration, Plattformunabhängigkeit und großem Funktionsumfang (trotz Kosten für Teams).
* **Web:** **React** oder **Vue.js** für Flexibilität und große Communities. **Angular** für große, strukturierte Projekte.
* **Mobile:** **Native** für beste Performance/Integration. **Flutter** oder **React Native** für Cross-Platform mit gutem Kompromiss.
* **Desktop:** **Electron** für schnelle Entwicklung mit Web-Kenntnissen. **Qt** für höchste Performance und echte Cross-Platform-Fähigkeit (inkl. Embedded).

---

**Vielen Dank für Ihre Aufmerksamkeit!**

**Fragen?**
