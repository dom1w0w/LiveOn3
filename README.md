
# LiveOn3 - Competitive Optimizer for Windows 11

LiveOn3 is a Windows optimization tool designed for **competitive PC gamers**, especially for titles like **Counter-Strike 2 (CS2)**. It reduces background latency, disables non-essential services, enables Game Mode, and switches your power plan to **Bitsum's Highest Performance** mode — all through a simple graphical interface.

---

## 🛠 Features

- ✅ Enables **Windows Game Mode**
- ⚡ Switches to **Bitsum Highest Performance** power plan (fallback to High Performance if not found)
- 🚫 Disables unnecessary background services (e.g., SysMain, Windows Search, DiagTrack)
- 🔄 Restarts `explorer.exe` to ensure registry tweaks take effect
- 🔁 One-click **Restore Defaults** button to reset all changes
- 💡 Includes helpful tooltips and a clean GUI for easy use

---

## 📦 Requirements

- Windows 11 (recommended)
- Python 3.x
- Tkinter (comes pre-installed with Python)
- Administrator privileges

---

## 🚀 How to Run

1. Download the script:
   ```bash
   python liveon3_gui_tool.py
   ```

2. Or, compile to `.exe` using PyInstaller:
   ```bash
   pyinstaller liveon3_gui_tool.spec
   ```

3. Run as **Administrator** to apply all changes properly.

---

## 📂 File Structure

| File | Description |
|------|-------------|
| `liveon3_gui_tool.py` | Main Python script with GUI |
| `liveon3_gui_tool.spec` | PyInstaller configuration to build .exe |
| `cs2_optimizer_log.txt` | Log file for tracking tweaks applied |

---

## 🧩 Future Roadmap

- GUI redesign with icons and animations
- Auto-detect background apps and warn user
- Safe Mode vs Extreme Mode toggles
- Steam/game launcher integration

---

## 🙌 Created By

Dominic Nuguid ([@dom1w0w](https://github.com/dom1w0w))  
Optimized for competitive CS2 and low-latency workflows.

---

**LiveOn3** helps you squeeze every frame, reduce input lag, and keep your Windows setup lean for game day.
