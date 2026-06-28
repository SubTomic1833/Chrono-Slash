# Chrono Slash

A high-octane, minimalist cyberpunk arcade rhythm-slasher built entirely in a single file using vanilla JavaScript and HTML5 Canvas. Defend your core, adapt to changing vector patterns, and survive the system overload.

## TRY IT FOR YOURSELF: https://subtomic1833.github.io/Chrono-Slash/

---

## Live Demo & Gameplay

* **Objective:** Prevent incoming enemy nodes from reaching your central blue core.
* **Controls:** Press **SPACEBAR** or the **"O" KEY** to fire omnidirectional lock-on lasers at any enemies currently inside your active Strike Zone.

---

## Core Mechanics & Features

### 1. Advanced Enemy Archetype Matrix
The defense matrix must adapt to three distinct structural threat variants, each introducing unique movement logic and durability:
* 🔴 **Vector Node (Standard):** The classic threat. Moves at a baseline pace in a predictable, straight linear trajectory.
* ⚡ **Glitch Node:** A high-speed system variance. It spawns with a $1.6\times$ speed modifier and a significantly reduced target radius, utilizing a erratic sinusoidal weaving pattern to throw off your timing windows.
* 🟣 **Quantum Node:** A heavily reinforced armor frame. This tank archetype requires **2 distinct impact slashes** to destroy, flashing a bright white shield overlay and feeding back `ABSORBED` metrics on the first hit.

### 2. Precision Timing Zones
The system features a strict, skill-based scoring hierarchy depending on exactly where a node rests inside your Strike Zone at the millisecond of engagement:
* 🥇 **PERFECT (+2 Pts):** Snipe enemies right as they cross the outer perimeter ring. Triggers a massive gold particle explosion and maximum camera rattle.
* 🥈 **GOOD (+1 Pt):** Hit enemies midway through the active threshold zone. Triggers an electric cyan explosion.
* ❌ **LATE (0 Pts):** Hitting enemies right next to the core rewards zero points and triggers a dull crimson burst.

### 3. Exploitation Proofing (No Spamming)
To preserve the competitive integrity of the high-score chase, the engine blocks automatic firing loop exploits. Players cannot hold down the action key to auto-shoot incoming threats. The weapon system locks immediately after a single discharge and strictly requires a physical key release (`keyup`) before registering the next strike initialization.

### 4. Progressive Overdrive Threshold (Score 50 Milestone)
* **LEVEL 01 // STANDARD (0–49 Points):** Baseline structural threats approach your core at readable, manageable vector lines.
* **LEVEL 02 // OVERDRIVE (50+ Points):** The architecture goes critical. Base spawn frequencies drastically accelerate, and even standard nodes gain an organic sine-wave weaving motion, forcing extreme reflex coordination.

### 5. Arcade Juice & Professional Polish
* **Dynamic Resolution Diagnostic Panel:** The boot menu features a built-in, left-aligned tactical directory explaining enemy nodes cleanly across any layout resolution without text overlapping.
* **Screen Shake Engine:** Visual impacts feature responsive camera rattling that scales dynamically relative to the precision value of your kill.
* **Ambient Backdrop Blur:** The CSS grid shifts cleanly under a backdrop blur glassmorphism UI, shifting ambient colors from cold cyber-blues into warning crimsons as the core limits are pushed.

---

## Getting Started

Because the entire game engine, styles, and rendering context are packaged in a single document, launching it locally takes seconds.

### Prerequisites
* A modern web browser (Chrome, Firefox, Edge, Safari) with JavaScript enabled.

### Running Locally
1. Clone this repository or copy the code from `index.html`.
2. Save it locally as an `.html` file.
3. Double-click the file to open it directly in your browser. No local server or dependencies required!

---

## Built With

* **HTML5 Canvas** - High-performance 2D vector pixel rendering.
* **Vanilla JavaScript** - Pure vector math, input tracking state machines, and frame loop scheduling via `requestAnimationFrame`.
* **CSS3** - Perspective transforms and neon grid keyframe animations.
* **Google Fonts** - *Plus Jakarta Sans* typeface integration.
