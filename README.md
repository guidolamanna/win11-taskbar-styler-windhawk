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
* **Comprehensive Styling:** By handling all `explorer.exe` threads, this config extends the seamless "Frosty Glass" look far beyond the taskbar. It styles the volume and brightness popups, Alt+Tab and Win+Tab menus, the language popup, snap layout flyouts, and all app/system tray tooltips.
* **Minimalist UI:** Removing unnecessary clutter to focus on pure aesthetics.

## 📐 Screen Compatibility & Reference Setup
This configuration will work on **any device or resolution**. However, depending on your physical screen size and scaling, you may want to tweak certain values (like taskbar height or icon sizes) in the mods to perfectly align with your display.

For reference, the default values in this config and the screenshots below are based on my personal setup:
* **Device:** 14" Laptop (ROG Zephyrus G14 - 2024)
* **Resolution & Scaling:** 2880 x 1800 at 200%

---

## 🛠️ The Full Setup
For the complete minimal and smooth "Frosty Glass" experience, I use the following Windhawk mod ecosystem:

| Mod Name | Key Configuration Settings |
| :--- | :--- |
| **Taskbar tray system icon tweaks** | `Hide location icon` \| `Hide bell icon` \| `Show desktop width: 12` |
| **Taskbar tray auto-hide (show on hover)** | `Hidden opacity: 0` \| `Hide delay: 0` \| `Fade duration: 100` |
| **Taskbar height and icon size** | `Height: 50` \| `Icon & Small Icon: 30` \| `Button & Small Button Width: 42` |
| **Taskbar auto-hide when maximized** | `Mode: Auto-hide when maximized or intersects taskbar` |
| **Taskbar Auto-Hide Instant Show** | *See configuration below* |

Paste this into the **Advanced** tab of the **Taskbar Auto-Hide Instant Show** mod:

```json
{"animationType":"slideFade","showSpeedup":400,"hideSpeedup":400,"showDuration":100,"hideDuration":100,"frameRate":120,"unhideDelay":1,"hideDelay":1,"oldTaskbarOnWin11":0,"edgeDetection":0}

```

---

## 📦 Installation
1.  **Mod Selection:** Open **Windows 11 Taskbar Styler** in Windhawk and select the **DockLike** theme.
2.  **Download Config:** Copy the raw code from [`taskbar-config.json`](./taskbar-config.json).
3.  **Advanced Tab:** Paste the code into the configuration box in the **Advanced** tab.
4.  **Save:** Click **Save** to apply the translucent effects instantly.

---

## 📸 Showcase
*Here is the Frosty Glass taskbar in action:*

**Video Demonstration:**

https://github.com/user-attachments/assets/d1448b78-aadb-4d16-bca2-853ece6e96a7

https://github.com/user-attachments/assets/4e61b37f-efa9-460c-858c-0d7f0b29154d

**Theme Gallery:**

<img width="2879" height="1799" alt="image" src="https://github.com/user-attachments/assets/ef3821f8-b050-43f8-bd81-7225770386d6" />
<img width="787" height="584" alt="image" src="https://github.com/user-attachments/assets/07d27ad5-086a-4af0-9164-f27dcf380ec8" />
<img width="553" height="600" alt="image" src="https://github.com/user-attachments/assets/9e23aeae-22e4-4736-99cd-44c280004d8e" />
<img width="873" height="307" alt="image" src="https://github.com/user-attachments/assets/b0d3ff24-55cb-4cd0-b151-91cdf72bc46c" />
<img width="1066" height="553" alt="image" src="https://github.com/user-attachments/assets/d85aa313-ea82-4bf8-849b-cf001370b06d" />


---

## 🔗 Related Projects

Complete the look across your entire OS! Check out my other Frosty Glass styling repositories:
* [❄️ Frosty Glass Start Menu Styler](https://github.com/guidolamanna/win11-startmenu-styler-frostyglass-windhawk) to apply this exact same aesthetic to your Start Menu and Lock Screen!
* [❄️ Frosty Glass Notification Center Styler](https://github.com/guidolamanna/win11-notificationcenter-styler-frostyglass-windhawk) to theme your Notifications, Calendar, and Control Center flyouts!

---

## 🙌 Credits & Inspiration
A huge thank you to [Ramen Software](https://github.com/ramensoftware) for creating Windhawk. This configuration was heavily inspired by the official [Windows 11 Taskbar Styling Guide](https://github.com/ramensoftware/windows-11-taskbar-styling-guide).


---
*Created by [Guido Lamanna](https://github.com/guidolamanna)*
