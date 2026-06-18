# 📝 Release Notes

## YouTube Morphe — 20.51.39
**Release Date:** 2026-06-18  
**YouTube Version:** 20.51.39  
**Version Code:** `1561173315`  
**Morphe Patcher:** v1.32.0  

---

### 📌 Overview

This release brings **YouTube 20.51.39** under the hood, patched with the latest **Morphe Patches v1.32.0**, **Morphe CLI v1.8.0-dev.5**, and **Morphe Manager v1.9.0-dev.4**.

The module continues to deliver a premium, ad-free, customizable YouTube experience via systemless root (Magisk / KernelSU).

---

### ✨ What's New in This Release

#### 1. YouTube 20.51.39 Base
- Latest stable YouTube build with all upstream bug fixes, performance improvements, and feature additions from Google.
- Full compatibility with Morphe patch set — all patches applied cleanly without conflicts.

#### 2. Morphe Patches v1.32.0
- **AMOLED Dark Theme Expansion** — The signature pure-black OLED theme is now extended to the GitHub app as well, keeping your entire modded app ecosystem battery-friendly on AMOLED displays.
- **Broader App Support** — Patch definitions updated for the latest app versions in the Morphe ecosystem.
- **Patch Stability** — Improved patch application success rate on newer YouTube obfuscation layers.

#### 3. Morphe CLI v1.8.0-dev.5
- **Faster Patching** — Dex-rebuilding pipeline optimized for speed and reduced RAM usage.
- **Strip Libs Re-enabled** — Unnecessary native libraries are stripped during build, shrinking final ZIP size.
- **License Viewer** — In-app dependency license viewer for full transparency.

#### 4. Morphe Manager v1.9.0-dev.4
- **Expert Mode Patching** — Granular control over which patches to apply during the patching workflow.
- **Smoother UI** — Reduced frame drops and stuttering during long-running patch operations.
- **Smart Update Notifications** — Android-native notifications when new patch versions become available.

---

### 🎯 Included Patches (YouTube)

| Patch Category | Description |
|----------------|-------------|
| **Ad Blocking** | Removes all video ads, banner ads, and home-feed advertisements. |
| **SponsorBlock** | Auto-skips sponsored segments, intros, outros, and non-music sections. |
| **Return Dislikes** | Restores community-powered dislike counts. |
| **Background Playback** | Audio playback continues with screen off or while using other apps. |
| **Picture-in-Picture** | Native PiP support for multitasking. |
| **4K / 8K Unlock** | Forces high-resolution playback options on all devices. |
| **AMOLED Black Theme** | True deep-black theme optimized for OLED displays. |
| **UI Customization** | Hide Shorts, adjust navigation bar, remove unwanted layout elements. |
| **Player Enhancements** | Custom playback speeds, default video quality, improved seekbar. |
| **Swipe Controls** | Brightness and volume gestures. |
| **Privacy Improvements** | Link sanitization, tracking parameter removal, signature spoofing. |
| **Material You / Themes** | Dynamic color support and additional theme styles. |

---

### ⚙️ Technical Details

- **Min Magisk:** 24.0
- **Min KernelSU:** 0.9.0
- **Architecture:** Universal (arm64-v8a, armeabi-v7a, x86, x86_64)
- **Mount Type:** Systemless
- **Size:** Optimized via library stripping

---

### 📥 Installation

1. Download `YouTube.Morphe-v20.51.39.zip` from the Assets below.
2. Open **Magisk** or **KernelSU** → Modules → Install from Storage.
3. Select the ZIP and flash.
4. **Reboot** your device.
5. Launch YouTube — select **"Keep use experimental"** if prompted on first run.

### 🔄 Updating

If you have a previous version installed:
1. Open Magisk / KernelSU → Modules.
2. Tap **Update** on the YouTube Morphe card (if auto-update is configured).
3. Reboot.

---

### ⚠️ Disclaimer

This project is for **educational and customization purposes only**. The developer is not responsible for any device damage or account restrictions. All original application credits and trademarks belong to **Google LLC**.

---

### 🙏 Credits

- **@Jordanx_09** — Lead Developer & Maintainer
- **j-hc** — Co-Author & Module Scripting
- **Morphe Team** — Morphe Patcher core engine
- **Magisk / KernelSU** — Systemless root framework

---

*Release 20.51.39 · Published 2026-06-18*
