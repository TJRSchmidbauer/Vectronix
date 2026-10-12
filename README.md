# ⚡ Vectronix – Schaltplandesigner ⚡

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

Willkommen bei **Vectronix**, dem innovativen, leichten und vollständig webbasierten Editor für elektronische Schaltpläne. Entworfen nach der offiziellen Norm **DIN EN 60617**, ist Vectronix das perfekte Werkzeug für Schule, Studium, Lehre und private Elektronik-Projekte! 🛠️🔌

Egal ob Einsteiger oder Profi – mit Vectronix erstellst du im Handumdrehen professionelle Schaltpläne, speicherst deinen Fortschritt und exportierst die Ergebnisse in höchster Qualität. Und das Beste: **Alles läuft lokal in deinem Browser!** 🌍🔒

---

## 🚀 Warum Vectronix? (Vorteile)

* **Keine Installation, keine Cloud-Zwänge:** Lade einfach die `index.html` und leg los! Deine Daten verlassen niemals deinen Rechner. 🛡️
* **Federleicht & Blitzschnell:** Das gesamte Programm besteht aus einer einzigen, hochoptimierten HTML-Datei. Kein Warten, keine Ladebalken. ⚡
* **Normgerechtes Design:** Alle Bauteile sind strikt nach der **DIN EN 60617** gestaltet, perfekt für offizielle Dokumente und Abschlussarbeiten. 📐
* **Wissenschaftlicher Export:** Nahtloser Export nach **LaTeX (TikZ)** und hochauflösendes **SVG**. Deine Dokumente sahen noch nie so gut aus! 🎓

---

## ✨ Features im Überblick

* **🖱️ Intuitive Drag & Drop Oberfläche:** Bauteile einfach aus der Seitenleiste auf die Arbeitsfläche ziehen.
* **🔌 Intelligentes Leitungs-Routing:** Zeichne blitzschnell Verbindungen. Knotenpunkte werden automatisch und intelligent gesetzt!
* **⚙️ Präzise Werkzeuge:** 
  * Einrastendes Raster (Snap-to-Grid) für perfekte Ausrichtung 📏
  * Bereichsauswahl für passgenauen Export ✂️
  * Rotation, Duplizieren und individuelle Beschriftung von Bauteilen 🔄
* **🕰️ Undo & Redo (Strg+Z / Strg+Y):** Fehler gemacht? Kein Problem! Springe einfach in der Zeit zurück.
* **🔍 Zoom & Verschieben:** Mausrad zoomt am Mauszeiger, leere Fläche ziehen verschiebt die Ansicht, `F` zeigt alles an.
* **🧲 Pin-Magnet:** Leitungen rasten automatisch an Bauteil-Anschlüssen ein; beim Verschieben/Drehen folgen die Leitungen.
* **📱 Touch-Unterstützung:** Bedienbar mit Maus, Stift und Touchscreen.
* **💾 Autosave:** Der Arbeitsstand wird automatisch im Browser gesichert und beim nächsten Öffnen wiederhergestellt.
* **💾 Lokales Speichern & Laden:** Speichere dein Projekt als `.vectronix` oder `.json` Datei und arbeite später genau dort weiter, wo du aufgehört hast. 📁

---

## 🧩 Umfangreiche Bauteil-Bibliothek

Vectronix kommt out-of-the-box mit allen wichtigen Bauteilen:

* 🪫 **Passiv:** Widerstand, Potentiometer, Kondensator, Elko, Spule, Sicherung
* 💡 **Halbleiter:** Diode, LED
* 🕹️ **Schalter / Ausgänge:** Schalter, Lampe, Motor
* 🔋 **Quellen:** Batterie, Gleichspannungsquelle, Wechselspannungsquelle, Masse
* 🧠 **Logik / Sonstige:** Transformator (mit/ohne Eisenkern), Operationsverstärker, AND/OR/NOT-Gatter, Spannungsmesser (V), Strommesser (A)

---

## 🛠️ Loslegen (Installation & Nutzung)

Es könnte nicht einfacher sein:

1. **Herunterladen:** Lade dieses Repository herunter (als `.zip`) oder klone es via Git. 📦
2. **Entpacken:** Öffne den Ordner auf deinem PC. 📂
3. **Starten:** Doppelklick auf die `index.html` – sie öffnet sich in deinem Standardbrowser (Chrome, Firefox, Edge, Safari). 🌐
4. **Zeichnen:** Wähle links ein Bauteil, platziere es auf der Arbeitsfläche und verbinde die Pins mit dem Leitungs-Werkzeug (Taste `W`)! 🎉

### 🌐 Online nutzen mit GitHub Pages

Vectronix ist eine einzelne statische Datei und läuft direkt auf GitHub Pages:

1. Änderungen in den `main`-Branch mergen.
2. Im Repository **Settings → Pages → Build and deployment** als Quelle **Deploy from a branch** wählen, Branch `main`, Ordner `/ (root)`.
3. Nach kurzer Zeit ist die App unter `https://<benutzer>.github.io/<repository>/` erreichbar.

### ⌨️ Tastenkürzel

| Taste | Funktion |
|---|---|
| `V` / `W` / `T` | Auswahl / Leitung / Text |
| `Umschalt+R` | Export-Bereich aufziehen |
| `R` | Ausgewähltes Bauteil drehen |
| `Entf` | Auswahl löschen |
| `Strg+D` | Duplizieren |
| `Strg+Z` / `Strg+Y` | Rückgängig / Wiederholen |
| `Strg+S` / `Strg+O` | Speichern / Laden |
| `F`, `+`, `-`, `0` | Alles anzeigen, Zoom |
| `?` | Hilfe |

---

## 📤 Export-Möglichkeiten

Perfekte Grafiken für jede Gelegenheit:

* 🖼️ **SVG (Scalable Vector Graphics):** Verlustfreie Skalierung für Präsentationen (PowerPoint, Keynote) und Web.
* 📜 **LaTeX (circuitikz):** Direkter Code-Export für deine LaTeX-Dokumente, benötigt das Paket `circuitikz`. Bitte Polarität und Größe der Symbole im Ergebnis kurz prüfen.

---

**Viel Spaß beim Planen, Entwickeln und Konstruieren mit Vectronix!** 💡👨‍💻👩‍💻
