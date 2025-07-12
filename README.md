<p align="center">
  <img src="assets/pulseflash_logo.png" alt="PulseFlash Logo" width="180" />
</p>


## ✅ PulseFlash

**Project Goal:** Companion app for WhatPulse (local Client API), focusing on **real-time stats in landscape mode** for power users, such as gamers and streamers.

---

### 💡 Core Idea

PulseFlash is the **sister app** of PulseView. It’s designed for **live data**, like clicks per second and real-time visualization. It uses the **local WhatPulse Client API** (Port 3490, JSON), runs only within the local network, and is technically **completely separate** from the regular WhatPulse API.

---

### 📱 Platform Support

| Platform   | Support Status                                             |
| ---------- | ---------------------------------------------------------- |
| iPhone     | ✅ Landscape only (except Settings/About)                   |
| iPad       | ✅ Landscape only (except Settings/About)                   |
| Apple TV   | 🔢 Planned (visual insights for living room/streaming use) |
| Android    | 🔢 Later, after iOS                                        |
| Mac, Watch | ❌ Not planned                                              |
| Vision Pro | ❌ Not planned                                              |

---

### 🧠 Feature Overview

#### 🌟 Core Features

* Live line charts for:

  * ⌨️ Keys per second
  * 🖱️ Clicks per second
  * 🔽️ Download speed
  * 🔼 Upload speed
* Chart history: **5 minutes**
* For each chart:

  * Current value
  * 1-minute average
  * 5-minute average
  * 5-minute max

#### 📊 Additional Views

* ✨ **Overview**: Shows Account Totals + Daily stats + Unpulsed stats
* ⏰ **Live**: Real-time charts as described
* 💪 **Pulse Button View**: Large button as the central tab icon, triggers pulse immediately
* 👤 **About View**: Haiku, info, Easter egg (Pelle!)
* ⚙️ **Settings View**: Input for host/IP, port, "Test Connection" button, privacy policy, imprint

---

### 🛠️ Technical Foundations

* SwiftUI (iOS + tvOS)
* WhatPulse Client API: `http://<ip>:3490/`
* Updates every second using a timer
* Landscape-only mode (Portrait shows: "Please turn your device!")
* Modular code, ready for future Android port
* Later: custom Swift module for **PixelShifting** to prevent screen burn-in (after initial release)

---

### 🎨 Design & Branding

* App name: **PulseFlash**
* Icon: ⚡️ Red lightning on dark background, matching PulseView
* Fully compatible with iOS 26 (Glass, Tinted, Dark/Light mode)
* No bright icons in dark mode (consistency matters!)

---

### 🧪 Release Roadmap

| Phase          | Description                                              |
| -------------- | -------------------------------------------------------- |
| ✅ Planning     | (Completed)                                              |
| 🔢 Kick-off    | As soon as PulseView 1.1 for iOS and watchOS is approved |
| ⚙️ Development | Real-time data, views, landscape UI                      |
| 🚀 Beta        | TestFlight phase                                         |
| 🎉 Release     | App Store submission                                     |

---

© 2025 Nebuliton
