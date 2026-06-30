VoxBox is a cross-platform, open-source application that reads text files (.txt, .pdf, .docx, etc.) and web pages aloud in a natural voice. It features a right-click context menu, drag-and-drop functionality, offline and cloud-based TTS, and automatic speech recognition. Includes a browser add-on and a mobile app concept. (https://github.com/yourusername/voxbox/actions/workflows/release.yml/badge.svg)] (https://github.com/yourusername/voxbox/actions/workflows/release.yml) [License: MIT] (https://opensource.org/licenses/MIT) VoxBox is a cross-platform, open-source application that reads any text format aloud in a natural voice in almost any language. Perfect for audiobooks, accessibility, or e-learning.
 (Insert demo GIF here)## ✨

Features- 
  **Right-click context menu:** Read files aloud directly from File Explorer (Windows/macOS/Linux).- 
  **Drag & Drop:** Drag `.txt`, `.pdf`, `.docx`, `.html`, `.md`, or `.epub` files into the app.- 
  **Automatic Language Detection:** Automatically detects the text language and selects the appropriate voice.- 
  **Offline & Online TTS:** Use system voices (offline) or cloud APIs (Google Cloud TTS) for natural-sounding voices.- 
  **System Tray:** Minimize VoxBox to the system tray and control playback (Play/Pause/Stop).- 
  **Clipboard Monitoring:** Press `Ctrl+Shift+V` (or `Cmd+Shift+V`) to have the clipboard contents read aloud.- 
  **Browser Add-on:** Read web page text aloud directly from Chrome.- 
  **No Telemetry:** No tracking. Full privacy.## 🚀 Installation### End UsersDownload the latest version for your operating system from the [Releases page](https://github.com/yourusername/voxbox/releases).#### Enable the context menu:- 
  **Windows:** After the installation, run `scripts/install-contextmenu.bat` as an administrator.- 
  **macOS:** Run `scripts/install-contextmenu.sh` in Terminal.- 
  **Linux:** Copy the `.desktop` file (created by the script) to `~/.local/share/nautilus/scripts/`.###


For Developers
  1. Clone the repository: `git clone https://github.com/yourusername/voxbox.git`
  2. Install dependencies: `cd voxbox/desktop && npm install`
  3. Start the app: `npm start`## 🛠️ Configuration (Cloud TTS)To use natural-sounding cloud voices, enter your API key in the app’s settings or create a `.env` file in the `desktop` folder:```envGOOGLE_TTS_API_KEY=your_api_key_here
