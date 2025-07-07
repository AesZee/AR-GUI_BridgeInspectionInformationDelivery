# 🏗️ Enhancing Bridge Inspection through Hierarchical Information Delivery in AR-GUI

**Bachelor's Graduation Project – Creative Technology (CreaTe)**  
**Developer:** Aes Lee  
**University:** University of Twente  
**Supervisor:** Dr. D.V. Le Viet Duc

---

## 🔗 Live Deployment

👉 [Try the AR-GUI Application (WebXR)](https://aes-ygvm1z2vuotk-z20nrjc.needle.run/)

---

## 📁 Source Code

This repository contains the complete Unity + Needle Engine project for an AR-based graphical user interface prototype, intended to enhance infrastructure inspection workflows through spatial, layered information.

---

## 🛠️ Software & Hardware Requirements

### Software
- **Unity**: 2022.3 LTS (URP enabled)
- **Needle Engine**: [Needle Tools](https://engine.needle.tools/)
- **Web Browser**: Chrome or Firefox with WebXR support

### Hardware
- Smartphone or tablet with:
  - Camera
  - WebXR compatibility
- PC/Mac for local development
- Optional: AR test surface or visual markers

### Performance & Compatibility Testing
- 📊 [FPS Monitor](https://engine.needle.tools/samples/framerates/?room=needle334)
- 📱 [Device Detection Tool](https://engine.needle.tools/samples/device-detection/?room=needle334&overlay=samples&tag=devices)

---

## ▶️ Running the Application

### Option 1 – Online
1. Open [Live Link](https://aes-ygvm1z2vuotk-z20nrjc.needle.run/) in a supported browser.
2. Point your device at the test area to interact with the AR-GUI.

### Option 2 – Local
1. Clone this repository.
2. Open in Unity (2022.3 LTS).
3. Install Needle Engine via Package Manager.
4. Select the `Export` object in the scene.
5. Click `Needle → Export` to deploy locally.
6. Use a local server to host the WebGL output (`npx serve`, Python HTTP server, etc.).

---

## 🧠 Working with the Source Code

### Key Components

| Component | Description |
|----------|-------------|
| `EverywhereConfigurator` | Controls system logic and connects triggers to UI content. |
| `LoD1 (LoD Switcher)` | Manages Level of Detail content per trigger state. |

### Customization

To modify or add new AR tasks:
1. Define a trigger in `SpotSwitcher`.
2. Set desired visual or textual content in `LoD1`.
3. Link them using the `EverywhereConfigurator`.

