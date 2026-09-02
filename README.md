# ⚔️ Geometric Survivor 3D (Megabonk Edition) 🌌✨

[![Live Demo](https://img.shields.io/badge/🎮_Play_Live_Demo-marcuscaiado.github.io-success?style=for-the-badge&logo=githubpages&logoColor=white)](https://marcuscaiado.github.io/geometricsurvivor/)
[![Three.js](https://img.shields.io/badge/Three.js-r128-00f5ff?style=flat&logo=three.js&logoColor=white)](https://threejs.org/)
[![Arcade Hub](https://img.shields.io/badge/🕹️_Arcade_Hub-Connected-05ffa1?style=flat)](https://marcuscaiado.github.io/marcus-arcade/)
[![Mobile Ready](https://img.shields.io/badge/Mobile_Touch-Ready-ff007f?style=flat&logo=android&logoColor=white)](https://marcuscaiado.github.io/geometricsurvivor/)

A vibrant, saturated 3D cartoon roguelite survivor inspired by **Megabonk** and **Vampire Survivors**, built with **Three.js**, procedural **Web Audio API**, and juicy arcade physics. Battle swarming geometric hordes on a floating checkerboard island, evolve active weapons & passive relics, and collect in-game power-up pickups!

---

## 🎮 Play Online
👉 **[https://marcuscaiado.github.io/geometricsurvivor/](https://marcuscaiado.github.io/geometricsurvivor/)**

---

## ✨ Features & Highlights

### 👤 3 Playable Starting Heroes
- 🔨 **Sir Bonk (The Knight)**: Heavy melee bruiser wielding the Mighty Mallet. Swings in a wide 153° frontal cleave with massive knockback.
- 🏹 **Pippin (The Scout)**: Agile marksman armed with a Rapid Pea Shooter that fires piercing slingshot pellets.
- 🧙 **Sparky (The Mage)**: Mystic spellcaster channeling Homing Energy Sparks that seek out distant targets.

### 🎯 Dual Aim System
- **AUTO-AIM (Default)**: Automatically tracks and locks onto the nearest threat.
- **MANUAL 3D AIM**: Full 360° directional aiming towards your mouse cursor or analog stick. Toggle anytime with **[SPACEBAR]** or the top HUD toggle.

### 🃏 Vampire Survivors Upgrades & Relics
Collect magnetic XP gems from fallen foes to level up and draft from 3 randomized cards:
- **Active Weapons (Up to 4 concurrent slots)**:
  - ⭐ **Star Shield (Orbiters)**: Cosmic stars circling the hero, shredding surrounding hordes.
  - 🪓 **Bouncing Axe**: Heavy battleaxes thrown in high parabolic arcs that bounce across the ground.
  - 🔨/🏹/🧙 **Weapon Upgrades**: Increases damage, reduces cooldowns, or adds extra projectiles/cleave range.
- **Passive Relics**:
  - 🍩 **Sugar Donut**: +25 Max HP & passive health regeneration (+1.5 HP/s).
  - 🚀 **Rocket Boots**: +18% Movement speed.
  - 🍀 **Lucky Clover**: +25% Critical strike chance (2.2x yellow floating critical damage).
  - 🧲 **Magnet Bell**: +50% XP gem attraction radius.
  - 🌶️ **Ghost Pepper**: +25% Global damage.
  - ⏱️ **Chrono Cog**: -18% Weapon cooldown reduction.

### ❤️ Field Pickups & Active Buff Modifiers
- ❤️ **Floating Hearts**: Restores **10 to 25 HP randomly** with floating green/pink health numbers and cheerful chimes.
- ⭐ **Invincibility Shield (5s)**: Grants 5 seconds of total damage immunity, a glowing orbital bubble, and lets you ram enemies for 45 heavy impact damage! Displays live timer badge: `⭐ INVINCIBLE 5s`.
- ⚡ **Speed Buff (15s)**: Grants **+150% Movement Speed (2.5x base speed!)** with cyan wind trails. Displays live timer badge: `⚡ SPEED +150% 15s`.

### 👾 Aggressive Swarms & Titan Golem Boss
- **Simultaneous Swarm Bites**: Enemies have independent attack timers; getting surrounded deals stacked damage!
- **Minute 3 Titan Golem**: A giant stone monolith with a glowing red visor, ground stomps, and a dedicated boss health bar.

### 🕹️ Quick-Action Golf-Style HUD
- **⏸️ Pause** (`ESC` / `P`): Instant pause modal showing stats and options.
- **🔄 Retry** (`R`): Quick instant restart without reloading.
- **👤 Hero** (`C`): Open 3D hero selector on the fly.
- **🕹️ Arcade Hub**: Direct jump to the Marcus Arcade library.

---

## 🕹️ Controls

| Action | Desktop / Keyboard | Mobile / Touchscreen |
| :--- | :--- | :--- |
| **Move Hero** | `W, A, S, D` or Arrow Keys | Drag On-Screen Virtual Joystick |
| **Aim Direction** | Mouse Cursor (Ground Raycast) | Touch Aim / Virtual Stick |
| **Toggle Aim Mode** | `[SPACEBAR]` or Click Button | Tap `🎯 AUTO-AIM` button |
| **Pause Game** | `[ESC]` or `[P]` | Tap `⏸️ PAUSE` button |
| **Quick Retry** | `[R]` Key | Tap `🔄 RETRY` button |
| **Switch Hero** | `[C]` Key | Tap `👤 HERO` button |

---

## 🛠️ Tech Stack

- **Three.js (r128)** — 3D isometric camera, cartoon lighting, custom geometries, squish/stretch mesh animations.
- **Web Audio API** — Real-time synthesized 8-bit sound effects (no external audio assets).
- **Universal Arcade Leaderboard** — Global score submission and persistence.
- **Vanilla HTML5 & CSS3** — Zero framework overhead, instant 60 FPS on mobile (Galaxy A55) & PC.
