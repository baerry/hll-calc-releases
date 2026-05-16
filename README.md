# HLL Artillery Calculator

A lightweight desktop overlay for **Hell Let Loose** that calculates artillery mils in real time — no alt-tabbing, no spreadsheets.

> Source code is private. Only release binaries are published here.

---

## Download

Go to the [**Releases**](../../releases/latest) page:

| File | Description |
|------|-------------|
| `HLL-Artillery-Calculator-Setup-x.x.x.exe` | Installer — adds Start Menu & Desktop shortcuts, includes uninstaller |
| `HLL-Artillery-Calculator-vx.x.x-portable.zip` | Portable — extract anywhere and run, no install needed |

---

## Get Started

1. **Download** the installer (`.exe`) or the portable `.zip` from the [Releases](../../releases/latest) page.
2. **Run** `HLL-Artillery-Calculator.exe` — a small overlay appears on screen.
3. **Launch Hell Let Loose.**
4. In-game, press **Ctrl+Shift+F** to bring the overlay to the front at any time.
5. **Select your faction** from the dropdown (American, German, British, Soviet).
6. **Type the distance** in meters, or press **Ctrl+Shift+V** to speak it.
7. The **mils result** updates instantly — dial it in and fire.

> **Tip:** The window is draggable by its title bar. Position it wherever it doesn't interfere with your game.

---

## How to Use

### Basic calculation
Select faction → type distance (200–1600 m) → read the mils shown in large text.

### SPA mode *(work in progress)*
Click **SPA: OFF** or press **Ctrl+Shift+G** to toggle SPA mode. An optional elevation offset field appears. Note that SPA calculations are still being refined.

### Voice input
Press **Ctrl+Shift+V** (or the 🎤 Voice button) and say the distance — e.g. *"eight hundred"* or *"800"*. Requires a microphone and internet connection (uses Google Speech).

### Text-to-speech
Open **⚙ Options** and set **Text to Speech** to:
- **Auto** — speaks the result automatically after you stop typing (~700 ms pause)
- **Manual** — only speaks when you press **Ctrl+Shift+D** or **Enter**
- **Off** — silent

### Options
| Setting | Description |
|---------|-------------|
| Window opacity | How transparent the overlay is |
| Text color | Color of the mils and distance text |
| Text opacity | Separate opacity just for the text |
| Font size | Scale the mils display up or down |
| Always on top | Keep overlay above all windows |
| Mute sounds | Disable UI sound effects |
| Text to speech | Off / Auto / Manual (see above) |
| Minimal mode | Hide buttons and history — just faction, distance, and mils |

### Hotkeys
| Hotkey | Action |
|--------|--------|
| `Ctrl+Shift+F` | Focus the overlay and select the distance field |
| `Ctrl+Shift+V` | Start voice input |
| `Ctrl+Shift+G` | Toggle SPA mode |
| `Ctrl+Shift+D` | Speak the current mils result aloud (TTS) |

---

## Requirements

- Windows 10 or Windows 11
- Microphone *(optional — voice input only)*
- Internet connection *(optional — voice recognition only)*
