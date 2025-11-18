<div align="center">
  <h1>pokehelper</h1>
  <p>A powerful Pokemon GO automation tool for Android, built in C# and powered by <a href="https://www.pgsharp.com/">PGSharp</a></p>
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-C%23-blue?style=for-the-badge">
  <img src="https://img.shields.io/github/downloads/GhostTypes/pokehelper/total?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/GhostTypes/pokehelper?style=for-the-badge">
</p>

---

<div align="center">
  <h2>Main Features</h2>
</div>

- Automated shiny/shundo hunting
- Works on both rooted and non-rooted devices
- User-friendly interface
- Multi-device support (per-device configuration)

---

<div align="center">
  <h2>How does it work?</h2>
</div>

pokehelper uses Android Debug Bridge (ADB) to connect to your device either wirelessly or via USB. It monitors the game using:

- **Pixel Detection** for real-time game state analysis
- **OCR (Optical Character Recognition)** to read in-game text and menus
- **[UI Automator](https://developer.android.com/training/testing/other-components/ui-automator)** for precise interface interaction

---

<div align="center">
  <h2>Quick Setup</h2>
</div>

1. Download the release executable
2. Connect your phone via USB or wireless ADB
3. Set up positions (one-time setup per device)
4. Enable desired features
5. Let it run!

> **Note:** Keep your device screen on during operation. OLED screens are not recommended for long sessions.

---

<div align="center">
  <h2>Feature List</h2>
</div>

<div align="center">

> Most features utilize the [paid version](https://www.pgsharp.com/feature-comparison/) of PGSharp for enhanced functionality.

</div>

<div align="center">
<table>
  <tr>
    <th>Feature</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><strong>Dialog Management</strong></td>
    <td>Auto-dismisses interrupting dialogs (weather warnings, speed alerts, adventure summaries, level-ups)</td>
  </tr>
  <tr>
    <td><strong>Cooldown Protection</strong></td>
    <td>Prevents soft bans by monitoring action cooldowns</td>
  </tr>
  <tr>
    <td><strong>Bot Mode</strong></td>
    <td>Starts/restarts app, enables auto-walking, and activates <a href="https://www.pgsharp.com/features/#virtual-go-plus">virtual go plus</a></td>
  </tr>
  <tr>
    <td><strong>Shiny/Shundo Hunter</strong></td>
    <td>Automated pokemon checking with configurable options:<br>• Auto-catch or notification mode<br>• Transformation pokemon filtering (Zorua/Ditto)<br>• Teleport coordination</td>
  </tr>
  <tr>
    <td><strong>Gift System</strong></td>
    <td>Supports both free and premium versions:<br>• Free: Manual gift sending (configurable friend count)<br>• Premium: Quick automated gift exchange</td>
  </tr>
</table>
</div>

---

<div align="center">
  <h2>Credits</h2>
</div>

<div align="center">

Special thanks to [PGSharp](https://www.pgsharp.com/) for their incredible app that makes this automation possible!

</div>
