# 🚁 Interactive Drone Explorer

> **A fully interactive web-based drone education project** — fly drones in real-time, click components to learn their theory, and explore professional drone filming & panoramic photography techniques through live animated camera simulations.

---

## 📸 Project Overview

This project was built as an academic presentation on **Drones in Filming and Panoramic Picturing**. It features:

- A **real-time interactive drone simulator** based on an actual BONKA 5200mAh quadcopter build
- **Clickable glowing components** with detailed theory for each drone part
- A **Cinema & Panoramic mode** with 6 fully animated live canvas scenes showing real drone filming techniques

---

## ✨ Features

### 🛸 Drone Explorer (4 Drone Types)

| Drone | Description |
|-------|-------------|
| **My Drone** *(YOURS)* | Exact replica of a real BONKA 5200mAh Carbon X-Quad |
| **Standard Quadcopter** | Generic 4-rotor multirotor |
| **Hexacopter** | 6-rotor multirotor with redundancy |
| **Fixed-Wing UAV** | Conventional airplane-style drone |

**Interactive Controls:**

| Control | Action |
|---------|--------|
| `Arrow Keys` | Move drone in all 4 directions |
| `W` / `S` | Increase / Decrease altitude |
| `Q` / `E` | Rotate left / right (Yaw) |
| `R` | Reset drone to center |
| `P` | Toggle propeller spin on/off |
| `Mouse Drag` | Drag the drone freely |

**Component Glow System:** Click any part of the drone — it pulses with an animated orange glow indicator. Each component reveals detailed theory covering:
- Structure & Materials
- Propulsion & Motors
- Aerodynamics
- Electronics & Flight Controllers
- Power Systems

---

### 🎬 Cinema & Panoramic Mode (6 Live Animated Scenes)

Each scene is a real-time HTML Canvas animation running at 60fps, simulating what a drone camera actually sees:

| # | Scene | What You See |
|---|-------|-------------|
| 1 | **Aerial Cinematography** | Animated golden hour sunset, moving clouds, drone flying across horizon with camera path arc |
| 2 | **360° Panoramic** | Starfield city skyline at night, live spinning 360° sweep indicator showing capture progress |
| 3 | **Real Estate & Architecture** | Isometric top-down property view, drone orbiting house in real-time |
| 4 | **Cinematic FPV Freestyle** | Full motion-blur speed tunnel, artificial horizon tilt, FPV OSD overlay |
| 5 | **Subject Tracking** | Animated car driving around a race track with live AI tracking box following it |
| 6 | **Hyperlapse & Timelapse** | Day-night sky cycle, city lights turning on/off, compressed time clock |

Every scene includes:
- ⏱ Live timecode counter (HH:MM:SS:FF)
- 🎞 Cinematic letterbox bars
- 📐 Rule-of-thirds grid overlay
- 🔵 Corner bracket viewfinder markers
- 🔴 REC 4K indicator
- 📊 Full flight & camera specs panel
- 💡 Pro tips from real aerial cinematographers

---

## 🛠 Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Structure & layout |
| **CSS3** | Animations, dark theme, responsive design |
| **Vanilla JavaScript** | All interactivity, drone controls, component logic |
| **HTML Canvas API** | All 6 live animated cinema scenes |
| **SVG** | Drone diagrams with clickable components |
| **Google Fonts** | Orbitron, Share Tech Mono, Exo 2 |

> **Zero dependencies.** No frameworks, no libraries, no npm. Single self-contained HTML file.

---

## 🚀 Getting Started

### Option 1 — Open Locally

```bash
# Just double-click the file — no server needed
open index.html
```

Works in any modern browser: Chrome, Edge, Firefox, Safari.

### Option 2 — Deploy to Vercel (Live URL)

```bash
# 1. Fork or clone this repository
git clone https://github.com/YOUR_USERNAME/drone-explorer.git

# 2. Push to your GitHub account
cd drone-explorer
git add .
git commit -m "Initial commit"
git push origin main

# 3. Go to vercel.com → Import your repo → Click Deploy
# Your site will be live at: drone-explorer.vercel.app
```

### Option 3 — GitHub Pages

```
Repository Settings → Pages → Source: main branch → / (root) → Save
Your site: https://YOUR_USERNAME.github.io/drone-explorer
```

---

## 📁 Project Structure

```
drone-explorer/
│
└── index.html          # The entire project — all HTML, CSS, JS in one file
└── README.md           # This file
```

---

## 🎓 Academic Context

**Subject:** Drone Technology & Applications  
**Topic:** Drones in Filming and Panoramic Picturing  
**Hardware Referenced:** BONKA 5200mAh 35C 6S LiPo · Carbon Fiber X-Frame · Brushless BLDC Motors  

### Component Theory Covered

- Carbon Fiber Frame construction & material science
- Brushless DC Motor principles (KV ratings, CW/CCW rotation)
- Propeller aerodynamics (pitch, disc area, tip speed)
- LiPo Battery chemistry (C rating, cell count, discharge curves)
- Flight Controller PID loops & IMU sensor fusion
- ESC signal protocols (DSHOT, BLHeli_32)
- Power Distribution & wiring gauge selection
- GPS navigation & RTK positioning
- 3-Axis Gimbal stabilization systems

### Filming Techniques Covered

- Aerial cinematography (180° shutter rule, ND filters, golden hour)
- 360° panoramic photography (nodal point alignment, equirectangular stitching)
- Real estate orbital shots & orthomosaic mapping
- FPV freestyle (power loops, proximity flying, ProTune color profiles)
- Subject tracking (AI lock-on, latency, lead tracking)
- Hyperlapse & timelapse (interval shooting, motion blur, waypoint automation)

---

## 🖥 Presentation Mode

1. Open `index.html` in Chrome or Edge
2. Press `F11` for fullscreen
3. Start on **MY DRONE** tab — walk through components
4. Switch to **CINEMA & PANORAMIC** tab
5. Use **Next →** button to present each filming mode as a slide
6. Each scene auto-animates — no clicks needed during transitions

---

## 📷 Screenshots

| Drone Explorer | Cinema Mode |
|----------------|-------------|
| Interactive quadcopter with glowing components | Live animated FPV scene with motion blur |

---

## 🔗 Live Demo

🌐 **[drone-explorer.vercel.app](https://drone-explorer.vercel.app)**

---

## 👩‍💻 Author

Built as an interactive academic project on drone technology.  
Drone hardware: **BONKA 5200mAh 35C 6S LiPo · Carbon X-Frame Quadcopter**

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> *"The best drone shot is the one your professor has never seen before."*