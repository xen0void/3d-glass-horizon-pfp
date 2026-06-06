# 3D Glass Horizon PFD ✈️

<p align="center">
  <a href="https://instagram.com/guicarvalho_86" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-guicarvalho__86-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
  <a href="mailto:guicarvalho8492@gmail.com">
    <img src="https://img.shields.io/badge/Email-guicarvalho8492@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://discord.com/users/Xen0void.v3" target="_blank">
    <img src="https://img.shields.io/badge/Discord-Guilherme%20Carvalho-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <img src="https://img.shields.io/badge/License-MIT-1e293b?style=for-the-badge" alt="License">
</p>

<p align="center">
  A high-fidelity, modern Primary Flight Display (PFD) and artificial horizon designed for web browsers. Utilizing Three.js for smooth 3D rendering and realistic spatial behavior, this instrument recreates a premium glass-cockpit experience with real-time physics, dynamic telemetries, and responsive mobile gyroscope binding.
</p>

---

## ✨ Features

* **Immersive 3D Attitude Sphere:** Powered by Three.js with precise multi-axis pitch and roll rendering.
* **Next-Gen Glass Cockpit UI:** Sleek, high-end avionics design including glass reflections, glowing neon hud metrics, and clean instrument bezels.
* **Dynamic HUD Tapes:** Live-updating speed and altitude tapes that react naturally to the aircraft's pitch attitude changes.
* **Dual Input System:** Seamless testing workflow. Use your computer keyboard for desktop simulation or sync via device orientation API for mobile hardware testing.
* **Zero Dependencies (Core):** Built natively on top of standard WebGL/Three.js web tech without heavy frameworks.

---

## 🛠️ Tech Stack & Powered By

<p align="left">
  <a href="https://threejs.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/threejs/threejs-original.svg" alt="threejs" width="40" height="40"/>
  </a>
  &nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  </a>
  &nbsp;
  <a href="https://www.w3.org/TR/html5/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="html5" width="40" height="40"/>
  </a>
  &nbsp;
  <a href="https://www.w3.org/Style/CSS/specs.en.html" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="css3" width="40" height="40"/>
  </a>
</p>

---

## 🚀 Live Demo & Controls

<details>
<summary><b>📐 Click to expand Keyboard & Hardware Mapping</b></summary>
<br>

### Desktop Simulation
* `Arrow Up` / `Arrow Down` ➔ Adjust Pitch (Climb/Dive)
* `Arrow Left` / `Arrow Right` ➔ Adjust Roll (Bank Left/Right)
* `G` Key ➔ Instant Auto-Level Recovery

### Mobile Tethering
Tap **"CONECTAR GIROSCÓPIO"** to lock the horizon to your smartphone's internal IMU sensor.

> ⚠️ *Note: Mobile browsers strictly require a secure HTTPS connection and explicit user runtime permission to stream hardware orientation telemetry.*
</details>

---

## 📂 Project Structure

```text
├── index.html       # Application layout and HUD UI overlays
├── style.css        # Glass cockpit styling, color variables, and typography
└── script.js       # Three.js 3D environment setup, render loop, and input handling
