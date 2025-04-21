```markdown
# 🏛️ Templerwissen ex Machina

**Templerwissen ex Machina** ist eine manuell gesteuerte, interaktive Wissensanwendung zur Erkundung der Welt der Tempelritter.
Das Programm ermöglicht den Zugriff auf eine kuratierte Sammlung von Inhalten, die sich mit Geschichte, Symbolik, Architektur
und Philosophie des Templerordens beschäftigen – vollständig offline, ohne KI oder Cloudanbindung.

> „ex Machina“ steht hier für das bewusste Handeln *aus der Maschine heraus* – der Mensch bedient die Software, nicht umgekehrt.

---

## 🎯 Ziel des Projekts

Ziel ist es, ein Werkzeug zur Verfügung zu stellen, das Nutzer:innen befähigt, sich eigenständig mit den geistigen, kulturellen
und historischen Aspekten der Templer auseinanderzusetzen. Im Fokus stehen Übersichtlichkeit, Tiefe und eigenständige Navigation
– kein automatisiertes Generieren oder Interpretieren von Inhalten.

---

## 🔐 Geschützter Bereich

Das Programm enthält einen passwortgeschützten Abschnitt, der ausschließlich Mitgliedern des Templerordens vorbehalten ist.
Dieser Bereich ist für Inhalte gedacht, die spezielles Hintergrundwissen oder eine besondere Zugangsberechtigung voraussetzen.

---

## 🧭 Funktionen

- 📚 **Kuratierte Wissensmodule**  
  Themenbereiche wie Symbolik, Rituale, Geschichte, Architektur, Personen und Orte

- 🔎 **Durchsuchbare Inhalte**  
  Strukturiertes Browsen durch thematische Kategorien

- 🧱 **Klarer Aufbau, kein „Black Box“-System**  
  Die Software ist bewusst ohne künstliche Intelligenz oder Cloud-Abhängigkeit entwickelt

- 🖥️ **Plattformunabhängig**  
  Erstellt mit C++ und Qt6, lauffähig unter Windows (Linux/macOS in Planung)

---

## 📦 Abhängigkeiten

Installiert wird das Projekt über [vcpkg](https://github.com/microsoft/vcpkg). Aktuell genutzte Bibliotheken:

- `qt6-base`
- `qt6-widgets`
- `qt6-tools`

---

## 🛠️ Installation

1. **vcpkg einrichten (falls nicht vorhanden):**
   ```bash
   git clone https://github.com/microsoft/vcpkg.git
   .\vcpkg\bootstrap-vcpkg.bat
   ```

2. **Abhängigkeiten installieren:**
   ```bash
   vcpkg install qt6-base qt6-widgets qt6-tools --triplet x64-windows
   ```

3. **Projekt kompilieren (z. B. mit CMake oder Qt Creator)**

---

## 🗂️ Projektstruktur (Ausblick)

```
TemplerwissenExMachina/
├── src/                # Hauptprogramm (C++/Qt)
├── modules/            # Wissensmodule (Text + Metadaten)
├── secure/             # Geschützter Bereich (passwortgeschützt)
├── assets/             # Bilder, Symbole etc.
├── vcpkg.json          # Abhängigkeitsdefinition
└── README.md
```

---

## 📅 Status

Die Software befindet sich in aktiver Entwicklung. GUI, Strukturierung der Module und Passwortbereich sind in Bearbeitung.
Technische Herausforderungen wie das vcpkg-Setup und Qt6-Integration sind weitgehend gelöst.

---

## 🤝 Beteiligung

Dieses Projekt richtet sich in erster Linie an historisch, kulturell und spirituell Interessierte mit Bezug zum Templerorden.
Rückmeldungen, Vorschläge oder technische Unterstützung sind willkommen.

---

## 📜 Lizenz

Das Projekt ist proprietär oder wird unter einer noch zu definierenden Lizenz veröffentlicht.
Bitte kontaktiere den Autor vor Weiterverwendung oder Verbreitung.

---

*„Wissen zu teilen, ist ein Akt des Vertrauens – Wissen zu hüten, ein Zeichen der Verantwortung.“*
```

---

Wenn du möchtest, kann ich daraus auch eine **deutsche Version** machen – oder eine zweisprachige. Sag einfach Bescheid.
