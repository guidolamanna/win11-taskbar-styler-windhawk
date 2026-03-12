# ❄️ Windows 11 Taskbar Styler: Frosty Glass Edition
> A refined, translucent "Dock" experience for Windows 11 via Windhawk.

[![Windhawk](https://img.shields.io/badge/Requires-Windhawk-blue?style=flat-square)](https://windhawk.net/)
[![Theme](https://img.shields.io/badge/Base_Theme-DockLike-9cf?style=flat-square)](#)
[![Style](https://img.shields.io/badge/Style-Frosty_Glass-lightgrey?style=flat-square)](#)

This configuration is built upon the **DockLike** theme and features a modern **Frosty Glass** aesthetic. It utilizes custom translucent `AcrylicBrush` effects to create a soft, blurred interface that feels integrated with the desktop environment.

---

## ✨ Design Philosophy
This theme focuses on a clean, premium look through:
* **DockLike Foundation:** Uses the DockLike theme as a base for the centered, detached taskbar structure.
* **Translucent Effects:** Soft blurring via Acrylic effects for a modern, high-end feel.
* **The "Floating" Layout:** Detached from screen edges with a centered, rounded appearance.
* **Minimalist UI:** Removing unnecessary clutter to focus on pure aesthetics.

## 📐 Display Optimization
Specifically tuned for high-resolution displays to ensure pixel-perfect rounding and font rendering:
* **Resolution:** 2880 x 1800 (14" Laptop)
* **Scaling:** 200%
* **Primary Font:** `vivo Sans EN VF`

---

## 🛠️ The Full Setup
For the complete "Frosty Glass" experience, I use the following Windhawk mod ecosystem:

| Mod Name | Key Configuration Settings |
| :--- | :--- |
| **Taskbar tray system icon tweaks** | `Hide location icon` \| `Hide bell icon` \| `Show desktop width: 12` |
| **Taskbar tray auto-hide (show on hover)** | `Hidden opacity: 0` \| `Hide delay: 0` \| `Fade duration: 100` |
| **Taskbar height and icon size** | `Height: 50` \| `Icon: 30` \| `Width: 42` |
| **Taskbar auto-hide when maximized** | `Mode: Auto-hide when maximized or intersects taskbar` |
| **Taskbar Auto-Hide Instant Show** | *See configuration below* |

<details>
<summary><b>Taskbar Auto-Hide Instant Show Settings (click to expand)</b></summary>

Paste this into the **Advanced** tab of the **Taskbar Auto-Hide Instant Show** mod:

```json
{"animationType":"slideFade","showSpeedup":400,"hideSpeedup":400,"showDuration":100,"hideDuration":100,"frameRate":120,"unhideDelay":1,"hideDelay":1,"oldTaskbarOnWin11":0,"edgeDetection":0}
```

<details>

---

## 📦 Installation
1.  **Mod Selection:** Open **Windows 11 Taskbar Styler** in Windhawk and select the **DockLike** theme.
2.  **Download Config:** Copy the raw code from [`taskbar-config.json`](./taskbar-config.json).
3.  **Advanced Tab:** Paste the code into the configuration box in the **Advanced** tab.
4.  **Save:** Click **Save** to apply the translucent effects instantly.

---
*Created by [Guido Lamanna](https://github.com/guidolamanna)*
