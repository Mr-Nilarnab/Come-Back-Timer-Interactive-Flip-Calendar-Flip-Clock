# Come Back Timer — Interactive 2026–2027 Flip Calendar & Flip Clock

**Come Back Timer** is a zero-dependency, single-file web application built with semantic HTML5, modern CSS3 (3D transforms, CSS Grid, custom properties, and responsive layouts), and vanilla JavaScript. Created by **Mr Nilarnab**, it combines a 24-month (2026–2027) interactive habit/goal-tracking flip calendar with a full-screen 3D flip clock and countdown timer, complete with synthesized Web Audio sound effects and `localStorage` persistence.

---
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:FF4500,100:0D1117&height=3&animation=fadeIn" width="100%"/>

<img width="1910" height="947" alt="Screenshot 2026-11-20 212056" src="https://github.com/user-attachments/assets/c482521a-58f9-4358-88b0-caea24849846" />
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:FF4500,100:0D1117&height=3&animation=fadeIn" width="100%"/>

<img width="1919" height="1079" alt="Screenshot 2026-11-20 212035" src="https://github.com/user-attachments/assets/3e7e7cda-f57a-4925-a877-bd2ef782000a" />
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:FF4500,100:0D1117&height=3&animation=fadeIn" width="100%"/>
YOUTUBE LINK =https://youtu.be/FwqOqM2cKqM
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,50:FF4500,100:0D1117&height=3&animation=fadeIn" width="100%"/>


## Key Features

* **24-Month Interactive Flip Calendar (2026–2027)**
  * Smooth 3D top-hinged page-flip animations with realistic back-page reveal and cast-shadow transitions across all 24 months (January 2026 – December 2027)
  * Quick-jump month navigation chips, **◀ PREV / NEXT ▶** controls, **⌖ JUMP TO TODAY**, keyboard arrow navigation (`←` / `→`), and mobile swipe gestures
  * Monthly hero banners with dynamic hue shifting, scanline overlays, and daily/monthly motivational quotes
* **Daily Habit & Progress Tracking**
  * Toggle **✓ TICK**, **✗ CROSS**, or **⌫ ERASE** modes (also accessible via `T`, `X`, and `E` keys)
  * Live statistics sidebar displaying monthly ticks, monthly crosses, circular SVG completion percentage ring, longest streak across 2026–2027, all-time totals, and per-month reset with confirmation
  * Automatic persistence to `localStorage` (`nilarnab-cal`) plus animated canvas pulse rings and floating ambient embers
* **Full-Screen Flip Clock & Countdown Timer**
  * Switch seamlessly between **CALENDAR** and **CLOCK** views (`C` key)
  * Supports **12H / 24H** format, **SECONDS** toggle, auto-hiding idle controls/cursor, and **Screen Wake Lock API** (`navigator.wakeLock`) to keep the display awake in clock mode
  * Built-in **TIMER** mode with quick presets (`5`, `10`, `15`, `25`, `45` min), `−1 MIN` / `+1 MIN` adjustments, `START` / `PAUSE` / `RESUME`, `RESET`, visual completion flash, and alarm beeps
* **Procedural Web Audio Sound Engine**
  * Synthesizes paper/flap sounds, page turns, and timer alarms live via the Web Audio API—no external audio files required, with mute toggle (`M` key) saved in `localStorage` (`nilarnab-snd`)

---

## Tech Stack & Architecture

* **Markup & Styling:** Single `.html` file using CSS variables, Grid/Flexbox, 3D `perspective` / `rotateX` animations, SVG progress rings, and Google Fonts (`Orbitron` and `Inter`)
* **Client-Side Logic:** Vanilla ES6+ JavaScript handling state, DOM rendering, Web Animations API sequences, HTML5 Canvas particle/pulse effects, and Web Audio synthesis
* **Storage:** Browser `localStorage` for calendar marks (`nilarnab-cal`) and audio preferences (`nilarnab-snd`)

---

## Getting Started & Controls

1. Download or clone `come-back-timer.html` and open it in any modern web browser (no build step or server required)
2. **Shortcuts:**
   * `C` — Toggle Calendar / Flip Clock view
   * `←` / `→` — Flip previous / next month (in Calendar view)
   * `T` / `X` / `E` — Select Tick, Cross, or Erase tool
   * `F` — Toggle Fullscreen
   * `M` — Mute / Unmute Web Audio sound effects

---

## Author

Created by **Mr Nilarnab** ([GitHub](https://github.com/Mr-Nilarnab))
```[cite: 1]
