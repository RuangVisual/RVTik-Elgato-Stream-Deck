# RVTik Stream Pro — Elgato Stream Deck Plugin

**Your LIVE. Your Control.**

Control RVTik Stream Pro directly from your Elgato Stream Deck. Simplify your live streaming workflow with 45 customizable actions, real-time music controls, secure pairing, and seamless device integration.

![Version](https://img.shields.io/badge/Version-1.0.2.0-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6)
![Actions](https://img.shields.io/badge/Actions-45-purple)
![Status](https://img.shields.io/badge/Status-Stable-success)

## ✨ Features

- 45 customizable Stream Deck actions.
- Spotify and YouTube Music Control.
- Play/Pause, Next Song, and Volume Control.
- Now Playing information and Music Request Queue.
- Music Request ON/OFF.
- Dashboard and Quick Panel shortcuts.
- OBS and TikTok LIVE Studio control shortcuts.
- Soundboard controls.
- Gift Battle controls.
- Credit Title controls.
- Live Duration controls.
- Smart Pairing and automatic reconnection.
- Secure and persistent authentication.
- Simultaneous Elgato Stream Deck and Mirabox StreamDock support.

## 🎮 Supported Devices

- Elgato Stream Deck
- Elgato Stream Deck Mini
- Elgato Stream Deck MK.2
- Elgato Stream Deck XL
- Elgato Stream Deck +
- Elgato Stream Deck Mobile

Actions are designed for compatible Stream Deck keys, including virtual keys on Stream Deck Mobile.

## 📋 Requirements

- Windows 10 or Windows 11.
- Elgato Stream Deck software version 6.9 or later.
- RVTik Stream Pro 3.9.0 or later.
- Active RVTik PRO license.

## 📥 Installation

1. Install the official Elgato Stream Deck software.
2. Download the latest `.streamDeckPlugin` file from the GitHub Releases section.
3. Double-click `com.rvtik.streampro.streamDeckPlugin`.
4. Confirm the plugin installation.
5. Launch RVTik Stream Pro.
6. Open the Stream Deck application.
7. Find the **RVTik Stream Pro** category in the action list.
8. Drag your preferred actions onto your Stream Deck keys.

No additional dependencies, Node.js installation, or manual configuration are required for end users.

## 🔗 Connecting to RVTik

1. Make sure RVTik Stream Pro is running.
2. Press any RVTik control action on your Stream Deck.
3. Approve the pairing request displayed in RVTik Stream Pro.
4. Once connected, press the action again to execute its assigned function.

Pairing is only required once. The plugin securely stores its credentials and automatically reconnects when RVTik Stream Pro becomes available.

## 🔐 Security

The plugin uses a dedicated local communication bridge to interact with RVTik Stream Pro.

- Localhost-only communication.
- User-approved device pairing.
- Independent authentication credentials.
- Secure credential storage using Windows DPAPI.
- Active PRO license validation.
- Independent device access revocation.
- No cloud credentials required for local device communication.

Elgato Stream Deck and Mirabox StreamDock can operate simultaneously without interfering with each other's pairing credentials.

## 🛠️ Troubleshooting

### Plugin not appearing

- Make sure the plugin installation has completed.
- Restart the Elgato Stream Deck application.
- Look for RVTik Stream Pro in the Keys action list.

### Unable to connect

- Make sure RVTik Stream Pro is running.
- Verify that your PRO license is active.
- Press the Pair / Connect RVTik action.
- Approve the pairing request in RVTik.

### Reset pairing

Open the RVTik system tray menu and select **Elgato Stream Deck: Cabut Pairing**. Press a RVTik action on your Stream Deck to establish a new connection.

## 📝 Release Notes

### Version 1.0.2.0 — Stable Release

- Initial stable release for Elgato Stream Deck.
- Added 45 customizable actions.
- Added official RVTik branding.
- Added Smart Pairing.
- Added persistent authentication and automatic reconnection.
- Added Multi-Device Bridge V2 compatibility.
- Added detailed runtime diagnostics.
- Verified simultaneous Elgato and Mirabox operation.

## 🌐 Official Links

- Website: [rvtikstream.com](https://rvtikstream.com)
- Stream Deck Software: [elgato.com](https://www.elgato.com/downloads)
- Stream Deck SDK: [docs.elgato.com](https://docs.elgato.com/streamdeck/)

## 👨‍💻 Developer

Developed by **Ruang Visual — RVTik**.

Built using the official Elgato Stream Deck SDK.

## Disclaimer

RVTik Stream Pro is an independently developed application and is not affiliated with or endorsed by Elgato, Corsair, Mirabox, Spotify, YouTube, or TikTok. All trademarks belong to their respective owners.

---

**RVTik Stream Pro**

Your LIVE. Your Control.

© 2026 Ruang Visual. All rights reserved.
