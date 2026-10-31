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

* **📱 Tablet-tauglich:** Große Schaltflächen, Zwei-Finger-Zoom, Bauteil antippen und setzen, Leitungen direkt vom Anschluss ziehen, Aktionsleiste für Bearbeiten, Drehen, Duplizieren und Löschen – ganz ohne Tastatur und Rechtsklick.
* **🔌 Leitungen & Knoten:** Leitungen rasten an Anschlüssen ein, alle Anschlüsse liegen im 8er-Raster, Knotenpunkte entstehen automatisch.
* **🔲 Mehrfachauswahl:** Werkzeug *Rahmen* (oder `Umschalt` + Ziehen) wählt ganze Schaltungsteile aus – gemeinsam verschieben, drehen, duplizieren, kopieren und einfügen (auch zwischen Projekten).
* **📚 Vorlagen:** Reihen-, Parallel- und Wechselschaltung, Spannungsteiler, RC-Glied, Einweggleichrichter, Transistor als Schalter.
* **➡️ Zählpfeile:** Spannungs- und Strompfeil mit Beschriftung wie `U_1` → U₁.
* **📝 Arbeitsblatt-Modus:** Bauteile oder Leitungen als *Lücke* markieren. Export *Aufgabe* zeigt leere Kästen, *Lösung* die vollständige Schaltung.
* **⚡ Simulation (Gleichstrom):** Lampen leuchten, LEDs glühen, Spannungs- und Strommesser zeigen Werte. Schalter, Taster, Fotowiderstand (hell/dunkel) und Heißleiter (kalt/warm) lassen sich antippen. Warnungen bei Kurzschluss, überlasteter LED und ausgelöster Sicherung.
* **🖼️ Export:** PNG mit Druckauflösung (150/300/600 dpi, von Word korrekt erkannt), *Als Bild kopieren* zum direkten Einfügen, SVG und LaTeX (circuitikz). Signatur abschaltbar.
* **🔗 Teilen per Link & QR-Code:** Die ganze Schaltung steckt im Link – nichts wird hochgeladen. Den QR-Code per Beamer zeigen, die Klasse öffnet die Schaltung auf ihren Tablets.
* **📲 Als App installierbar:** Auf dem iPad *Zum Home-Bildschirm*, in Chrome/Edge über *Installieren*. Danach läuft Vectronix auch ohne Internet.
* **🕰️ Undo & Redo, Autosave, Speichern & Laden** als `.vectronix`-Datei.

---

## 🧩 Umfangreiche Bauteil-Bibliothek

* 🔋 **Quellen:** Batterie, Gleichspannungsquelle, Netzgerät, Wechselspannungsquelle, Solarzelle, Erde, Masse
* 🕹️ **Schalter:** Schalter, Taster, Wechselschalter, Relais
* 💡 **Verbraucher:** Lampe, Motor, Klingel, Lautsprecher
* 🪫 **Passiv:** Widerstand, Potentiometer, Fotowiderstand (LDR), Heißleiter (NTC), Kondensator, Elko, Spule, Spule mit Eisenkern, Sicherung
* 🔬 **Halbleiter:** Diode, LED, Z-Diode, Transistor npn/pnp
* 📏 **Messen & Pfeile:** Spannungsmesser, Strommesser, Spannungspfeil, Strompfeil
* 🧠 **Sonstige:** Transformator (mit/ohne Eisenkern), Operationsverstärker, UND/ODER/NICHT-Gatter

---

## 🍎 Für Lehrkräfte

* **Arbeitsblatt in zwei Minuten:** Vorlage öffnen → Werte eintragen (Doppeltippen) → einzelne Bauteile als *Lücke* markieren → *Export* → PNG, Fassung *Aufgabe* und danach *Lösung*. Oder *Als Bild kopieren* und direkt in Word einfügen.
* **Im Unterricht:** *Simulieren* starten und Schalter live umlegen. Mit *Export → Teilen* einen QR-Code an die Wand werfen; die Klasse arbeitet mit einer eigenen Kopie weiter.
* **In mebis oder einer anderen Lernplattform:** Den Teilen-Link als *Link/URL* im Kurs anlegen. Wer ihn öffnet, bekommt genau diese Schaltung. Ohne Link genügt die Adresse `https://tjrschmidbauer.github.io/Vectronix/`.
* **Datenschutz:** Keine Anmeldung, keine Cookies, kein Server. Schaltungen bleiben im Browser oder im Link.

---

## 🛠️ Loslegen (Installation & Nutzung)

Es könnte nicht einfacher sein:

1. **Herunterladen:** Lade dieses Repository herunter (als `.zip`) oder klone es via Git. 📦
2. **Entpacken:** Öffne den Ordner auf deinem PC. 📂
3. **Starten:** Doppelklick auf die `index.html` – sie öffnet sich in deinem Standardbrowser (Chrome, Firefox, Edge, Safari). 🌐
4. **Zeichnen:** Wähle links ein Bauteil, platziere es auf der Arbeitsfläche und verbinde die Pins mit dem Leitungs-Werkzeug (Taste `W`)! 🎉

### 🌐 Online nutzen mit GitHub Pages

Vectronix besteht aus statischen Dateien (`index.html`, dazu `manifest.webmanifest`, `sw.js` und Icons für die App-Installation) und braucht weder Build noch Server. `index.html` funktioniert auch allein. So bringst du es online:

1. Öffne das Repository auf GitHub und gehe zu **Settings → Pages**.
2. Wähle unter **Build and deployment → Source** den Eintrag **Deploy from a branch**.
3. Wähle als Branch **`master`** (der Standard-Branch dieses Repositories) und als Ordner **`/ (root)`**. Klicke auf **Save**.
4. Warte ein bis zwei Minuten. Oben auf der Pages-Seite erscheint dann der Link – bei diesem Repository:
   **`https://tjrschmidbauer.github.io/Vectronix/`**
5. Jede weitere Änderung im Branch `master` wird automatisch neu veröffentlicht.

> 💡 Die Datei `.nojekyll` sorgt dafür, dass GitHub die Seite unverändert ausliefert. Deine Schaltpläne bleiben auch online **lokal in deinem Browser** – nichts wird hochgeladen.

### 🧭 Kurzanleitung: Dein erster Schaltplan

1. **Bauteil platzieren:** In der Palette antippen und auf die Fläche tippen (mehrfach möglich, *Fertig* beendet) – oder direkt auf die Fläche ziehen. Schneller Start: *Datei → Vorlagen*.
2. **Leitungen ziehen:** Vom Anschluss eines Bauteils aus ziehen, oder Werkzeug *Leitung* (`W`): Start und Ziel antippen.
3. **Bearbeiten:** Antippen wählt aus; die Leiste unten bietet *Bearbeiten*, *Drehen*, *Duplizieren*, *Löschen*. Doppeltippen öffnet den Dialog für Bezeichnung und Wert, z. B. `4,5 V`, `1 kΩ` oder `3,5 V; 0,2 A` (diese Werte nutzt auch die Simulation).
4. **Knotenpunkte:** Entstehen automatisch. Antippen, um einen Punkt als „nicht verbunden“ zu markieren oder zu entfernen.
5. **Simulieren:** *Simulieren* (Leertaste) startet die Gleichstrom-Simulation, *Beenden* stoppt sie.
6. **Exportieren:** *Export → Exportieren …* (PNG, SVG, LaTeX), *Als Bild kopieren* oder *Teilen*. Mit *Export-Bereich wählen* (`Umschalt+R`) nur einen Ausschnitt.

### 🛟 Häufige Fragen

* **Mein Plan ist nach dem Neuladen weg?** Der Autosave nutzt den Browserspeicher. Im privaten Modus oder nach dem Löschen von Websitedaten geht er verloren – sichere wichtige Pläne zusätzlich als Datei.
* **Die Seite zeigt auf GitHub Pages einen 404-Fehler?** Prüfe, ob in *Settings → Pages* der Branch `master` und `/ (root)` gewählt sind und ob `index.html` im Hauptordner liegt.
* **Der LaTeX-Export kompiliert nicht?** Du brauchst das Paket `circuitikz`. Kontrolliere Polarität und Symbolgrößen im Ergebnis.

### ⌨️ Tastenkürzel

| Taste | Funktion |
|---|---|
| `V` / `W` / `T` / `M` | Auswahl / Leitung / Text / Rahmen |
| `Leertaste` | Simulation starten/beenden |
| `Umschalt+R` | Export-Bereich aufziehen |
| `R` | Auswahl drehen |
| `Entf` | Auswahl löschen |
| `Strg+C` / `Strg+X` / `Strg+V` | Kopieren / Ausschneiden / Einfügen |
| `Strg+A` / `Strg+D` | Alles auswählen / Duplizieren |
| `Strg+Z` / `Strg+Y` | Rückgängig / Wiederholen |
| `Strg+E` / `Strg+Umschalt+C` | Exportieren / Als Bild kopieren |
| `Strg+S` / `Strg+O` | Speichern / Laden |
| `F`, `+`, `-`, `0` | Alles anzeigen, Zoom |
| `?` | Hilfe |

---

## 📤 Export-Möglichkeiten

* 🖼️ **PNG:** Für Word, Pages, OneNote und Arbeitsblätter – mit eingebetteter Druckauflösung, optional transparent.
* 📋 **Als Bild kopieren:** Direkt in die Zwischenablage (Chrome, Edge, Safari über https).
* ✒️ **SVG:** Verlustfrei skalierbar für Präsentationen und Web.
* 📜 **LaTeX (circuitikz):** Code zum Kopieren oder als `.tex`. Bauteile ohne circuitikz-Gegenstück werden originalgetreu aus Linien gezeichnet.
* 📝 Jeweils als *Lösung* oder *Aufgabe* (Lücken leer), Signatur abschaltbar.

---

**Viel Spaß beim Planen, Entwickeln und Konstruieren mit Vectronix!** 💡👨‍💻👩‍💻
