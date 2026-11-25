# PSKOS 1.0 (Early Access)
**PowerShell Kernel Operating System** — a lightweight, retro-styled Power-text graphics (PTG) desktop environment and shell for Windows, developed by **Rutitgtutipam Software**.

![Release](https://shields.io)
![Platform](https://shields.io)

## ✨ Key Features
- **Dual Desktop Modes:** Switch seamlessly between **EZ Mode** (graphical desktop with icons, Start menu & taskbar) and **Default Mode** (classic dual-pane TUI file & app manager).
- **Multi-Window Compositor:** Run, drag, resize, minimize, and toggle fullscreen (`Windowed |YES|NO|`) for up to **5 simultaneous applications**.
- **Strict Read-Only Security Guard:** Disk writes are blocked by default until explicitly unlocked via `FS Write ON`.
- **Built-in `.pskosapp` Suite:** Includes `Calculator`, `WordPad` (saves to `Doc Saves`), `Analog/Digital Clock`, `HD Pixel Paint` (exports PNG to `Paint Saves`), `Snake Arcade`, and the interactive `Help Manual`.
- **Persistent Session Lock:** Local account protection with password-verified logout.

## 🚀 Download & Quick Start
1. Go to the **[Releases](../../releases)** page and download **`PSKOS-v1.0-EarlyAccess.zip`**.
2. Extract the archive to any folder (e.g., `C:\PSKOS\`).
3. Run **`PSKOS.exe`**.
4. Create your local username and password on first boot.

## ⌨️ Essential Terminal Commands

| Command | Description |
| :--- | :--- |
| `FS Write ON` / `OFF` | Enable or disable physical disk writes |
| `Theme <color>` | Switch color scheme (`blue`, `matrix`, `amber`, `red`, `dark`) |
| `mode ez` / `mode default` | Switch between EZ Mode and Default Mode |
| `config` | Open System Configuration window |
| `open <app.pskosapp>` | Launch a PSKOS application |
| `logout` / `exit` | Sign out of your account or shut down PSKOS |

---
*© Rutitgtutipam Software. All rights reserved. Originally evolved from the PSOPSYS console shell.*
