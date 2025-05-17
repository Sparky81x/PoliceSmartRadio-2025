# PoliceSmartRadio 2025

**The 2025 revival of Albo1125’s legendary Police SmartRadio**  
Fully restored, modernized, and integrated for GTA V 1.0.3521.1 and LSPDFR 0.4.9.  
Maintained by Sparky81x.

---

### ✅ Features

- 🎮 Radio UI with keyboard/controller support
- 🧠 Smart button system with XML-based configuration
- 🔈 Dispatch voiceovers and text-based notifications
- 🐾 Fully functional **Panic Button**, **Plate Check**, **Ped Check**, **Request PIT**, and **End Call**
- 🐕 K9 logic (search & indicate) — ready for activation
- 🎙️ Vocal Dispatch integration (voice command support)
- 🚔 Plugin compatibility:
  - **Traffic Policer 2025**
  - **Arrest Manager 2025**
  - **LSPDFR+ 2025**
  - **British Policing Script (optional)**
  - **BetterEMS (indirect)**
- 💻 Editable INI + XML configs
- 🧩 API available for third-party plugins (e.g., LSPDFR+, Computer+)

---

### 🔧 Requirements

- GTA V: `1.0.3521.1`
- LSPDFR: `0.4.9`
- RagePluginHook: `0.51+`
- Albo1125.Common.dll: `v6.6.4.0` (included)
- RAGENativeUI.dll: `1.9.3` or higher (typically bundled)

---

### 📂 Installation

1. Place `PoliceSmartRadio.dll` in `Plugins/LSPDFR/`
2. Place `Albo1125.Common.dll` in your **GTA V root directory**
3. Place the contents of the `Config` and `Audio` folders in:
   - `Plugins/LSPDFR/PoliceSmartRadio/Config/`
   - `Plugins/LSPDFR/PoliceSmartRadio/Audio/`
4. Start GTA V via **RagePluginHook**, go on duty, and press the radio hotkey (default: `C`)

---

### 🎨 Customization

PoliceSmartRadio uses **OnFoot.xml** and **InVehicle.xml** to define buttons.  
Add or remove button definitions, set visibility, and assign icons (`.png` files).  
Use `DisplayConfig.ini` and `DisplayPositioning.ini` to reposition or scale the UI.

---

### 📦 Included Buttons

| Button        | Description                     |
|---------------|---------------------------------|
| Panic         | Sends multiple backup units     |
| Plate Check   | Runs license plate with audio   |
| Ped Check     | Shows record of nearest ped     |
| Request PIT   | Clears you to PIT if safe       |
| End Call      | Cancels active LSPDFR callout   |
| K9 (Optional) | K9 sniff vehicle for drugs      |

> Use `C + Controller D-Pad` to scroll and select actions in-game.

---

### 📝 Credits

- Original author: **Albo1125**  https://github.com/Albo1125/PoliceSmartRadio
- 2025 update: **Sparky81x**  
- UI concept inspired by FinKone and OfficerSquare  
- Voiceovers sourced from original mod and RPH scanner

---

### 💬 Support & Feedback

Please report bugs or feature requests via GitHub Issues.  
Feel free to fork and contribute.

👉 [Download the mod from LSPDFR.com](https://www.lcpdfr.com/downloads/gta5mods/scripts/51096-policesmartradio-2025-realistic-dispatch-plate-checks-panic-buttonmore/)
