# voxbox
VoxBox ist eine plattformübergreifende Open-Source-Anwendung, die Textdateien (.txt, .pdf, .docx etc.) und Webseiten in natürlicher Stimme vorliest. Mit Rechtsklick-Kontextmenü, Drag &amp; Drop, Offline- &amp; Cloud-TTS sowie automatischer Spracherkennung. inkl. Browser-Add-on &amp; Mobile-App-Konzept.
(https://github.com/yourusername/voxbox/actions/workflows/release.yml/badge.svg)]
(https://github.com/yourusername/voxbox/actions/workflows/release.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)]
(https://opensource.org/licenses/MIT)
VoxBox ist eine plattformübergreifende Open-Source-Anwendung, die beliebige Textformate in einer natürlichen Stimme in fast jeder Sprache vorliest. Perfekt für Hörbücher, Accessibility oder E-Learning.![VoxBox Demo GIF](assets/demo.gif) 
*(Hier Demo-GIF einfügen)*## ✨ 

Features- 
  **Rechtsklick-Kontextmenü:** Lese Dateien direkt aus dem Datei-Explorer (Windows/macOS/Linux) vor.- 
  **Drag & Drop:** Ziehe `.txt`, `.pdf`, `.docx`, `.html`, `.md` oder `.epub` in die App.- 
  **Automatische Spracherkennung:** Erkennt die Textsprache automatisch und wählt die passende Stimme.- 
  **Offline & Online TTS:** Nutze Systemsprachen (Offline) oder Cloud-APIs (Google Cloud TTS) für natürliche Stimmen.- 
  **System-Tray:** Minimiere VoxBox in den Tray und steuere Wiedergabe (Play/Pause/Stopp).- 
  **Zwischenablage-Überwachung:** Drücke `Strg+Shift+V` (oder `Cmd+Shift+V`), um den Inhalt der Zwischenablage vorzulesen.- 
  **Browser-Add-on:** Lese Webseiten-Text direkt aus Chrome heraus vor.- 
  **Telemetriefrei:** Kein Tracking. Volle Privatsphäre.## 🚀 Installation### EndnutzerLade die neueste Version für dein Betriebssystem von der [Releases-Seite](https://github.com/yourusername/voxbox/releases) herunter.#### Kontextmenü aktivieren:- 
  **Windows:** Führe nach der Installation `scripts/install-contextmenu.bat` als Administrator aus.- 
  **macOS:** Führe `scripts/install-contextmenu.sh` im Terminal aus.- 
  **Linux:** Kopiere die `.desktop`-Datei (wird durch das Skript erstellt) nach `~/.local/share/nautilus/scripts/`.###
  
Für Entwickler
  1. Repository klonen: `git clone https://github.com/yourusername/voxbox.git`
  2. Abhängigkeiten installieren: `cd voxbox/desktop && npm install`
  3. App starten: `npm start`## 🛠️ Konfiguration (Cloud TTS)Um natürliche Cloud-Stimmen zu nutzen, trage deinen API-Key in die Einstellungen der App ein oder erstelle eine `.env` Datei im `desktop` Ordner:```envGOOGLE_TTS_API_KEY=dein_api_key_hier
