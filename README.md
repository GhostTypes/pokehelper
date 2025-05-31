# 🤖 pokehelper

A powerful Pokemon GO automation tool for Android, built in C# and powered by [PGSharp](https://www.pgsharp.com/)! 

✨ **Main Features:**
- Automated shiny/shundo hunting
- Works on both rooted and non-rooted devices
- User-friendly interface
- Multi-device support (per-device configuration)

## 🔧 How does it work?

pokehelper uses Android Debug Bridge (ADB) to connect to your device either wirelessly or via USB. It monitors the game using:

- 👁️ **Pixel Detection** for real-time game state analysis
- 📝 **OCR (Optical Character Recognition)** to read in-game text and menus
- 🎮 **[UI Automator](https://developer.android.com/training/testing/other-components/ui-automator)** for precise interface interaction

## 🚀 Quick Setup

1. 📥 Download the release executable
2. 📱 Connect your phone via USB or wireless ADB
3. ⚙️ Set up positions (one-time setup per device)
4. ✅ Enable desired features
5. 🎮 Let it run!

> ⚠️ **Note:** Keep your device screen on during operation. OLED screens are not recommended for long sessions.


## ✨ Feature List

Most features utilize the [paid version](https://www.pgsharp.com/feature-comparison/) of PGSharp for enhanced functionality.

| Feature | Description |
|---------|-------------|
| 🚫 Dialog Management | Auto-dismisses interrupting dialogs (weather warnings, speed alerts, adventure summaries, level-ups) |
| ⏳ Cooldown Protection | Prevents soft bans by monitoring action cooldowns |
| 🤖 Bot Mode | Starts/restarts app, enables auto-walking, and activates [virtual go plus](https://www.pgsharp.com/features/#virtual-go-plus) |
| ✨ Shiny/Shundo Hunter | Automated pokemon checking with configurable options:<br>• Auto-catch or notification mode<br>• Transformation pokemon filtering (Zorua/Ditto)<br>• Teleport coordination |
| 🎁 Gift System | Supports both free and premium versions:<br>• Free: Manual gift sending (configurable friend count)<br>• Premium: Quick automated gift exchange |

## 🙏 Credits

Special thanks to [PGSharp](https://www.pgsharp.com/) for their incredible app that makes this automation possible!
  


