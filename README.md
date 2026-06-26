# Chrono Slash

A high-octane, minimalist cyberpunk arcade shooter built entirely in a single file using vanilla JavaScript and HTML5 Canvas. Defend your core, time your slashes, and survive the Overdrive.

# TRY IT FOR YOURSELF : https://subtomic1833.github.io/Chrono-Slash/

---

## 🕹️ Live Demo & Gameplay

* **Objective:** Prevent the incoming enemy nodes from reaching your central blue core.
* **Controls:** Press the **`A` Key** to fire omnidirectional lock-on lasers at any enemies currently inside your active **Strike Zone**.

---

## 🎯 Core Mechanics & Features

### 1. Precision Timing System
The game features a strict skill-based scoring hierarchy depending on exactly *where* the enemy is inside your Strike Zone when you press `A`:
* 🥇 **PERFECT (+2 Pts):** Snipe enemies right as they cross the outer perimeter ring. Triggers a massive **gold** particle explosion.
* 🥈 **GOOD (+1 Pt):** Hit enemies midway through the zone. Triggers an electric **cyan** explosion.
* ❌ **LATE (0 Pts):** Hitting enemies right next to your player core rewards zero points and triggers a dull **crimson** burst.

### 2. Exploitation Proofing (No Key-Holding)
To preserve the competitive integrity of the high-score chase, the engine blocks automatic firing loop exploits. Players cannot hold down the `A` key to auto-shoot incoming threats. The weapon system locks immediately after a single discharge and requires a physical **key release (`keyup`)** before firing again.

### 3. Progressive Enemy Evolution (Level 50 Milestone)
* **LEVEL 01 // STANDARD (0–49 Points):** Enemy nodes march in a highly readable, straight linear vector toward your core.
* **LEVEL 02 // OVERDRIVE (50+ Points):** The system goes critical. Spawn frequencies accelerate, and enemies gain an organic **sine-wave weaving motion**, swaying unpredictably as they approach the center to throw off your timing windows.

### 4. Juice & Polish
* **Screen Shake:** Impacts feature responsive camera rattling that scales relative to the precision value of your kill.
* **Dynamic Backdrop:** The UI colors shift dynamically from cold cyber-blues into warning crimsons as you approach the Level 2 threshold.

---

## 🚀 Getting Started

Because the entire game engine, styles, and rendering context are packaged in a single document, launching it takes seconds.

### Prerequisites
A modern web browser (Chrome, Firefox, Edge, Safari) with JavaScript enabled.

---

## 🛠️ Built With

* **HTML5 Canvas** - High-performance 2D rendering.
* **Vanilla JavaScript** - Pure vector math, input tracking, and game loop scheduling (`requestAnimationFrame`).
* **CSS3** - Backdrop blur glassmorphism styling filters.
* **Google Fonts** - *Plus Jakarta Sans* typeface integration.

---
