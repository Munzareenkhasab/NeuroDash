# NeuroDash: Antigravity Edition 🚀🧠

**NeuroDash** is an interactive, browser-based cognitive decision-making game built entirely with HTML5 Canvas, CSS, and Vanilla JavaScript. Designed with a sleek, modern space aesthetic, the game challenges players to make rapid split-second decisions while tracking detailed cognitive metrics under pressure.

### 🎮 Gameplay Overview
* **Collect. Decide. Survive.** — Navigate your spacecraft to collect the "Good" items (green ✚) while simultaneously dodging the "Bad" items (red ✕).
* **Escalating Difficulty** — The speed and spawn rates increase dynamically as you progress through higher levels.
* **Combo System** — Build your combo multiplier by stringing together correct decisions to maximize your score.

### 📊 Cognitive Tracking & Analytics
NeuroDash acts as a mini-experiment in measuring human reaction times. During your session, the game actively records data and outputs a comprehensive post-game performance report, including:
* **Accuracy:** Percentage of correct choices made versus wrong moves.
* **Average Reaction Time (ms):** The speed at which you react to new items spawning on screen.
* **Miss Rate:** How many positive items slipped by uncollected.
* **Stress Score (out of 100):** A custom algorithm that calculates your "stress" level based on accumulated miss rates and slowed reaction times under pressure.
* **CSV Export:** Easily download your performance log (`neurodash_session.csv`) locally for further analysis or data science projects!

### 💻 Technologies Used
* **HTML5 Canvas:** For rendering the high-performance starfield background, ship physics, and particles.
* **CSS3:** For the glassmorphism UI, floating popups, and the clean Google-inspired Heads-Up Display (HUD).
* **Vanilla JavaScript:** For the core game loop, entity management, collision tracking, and CSV data generation.

### 🚀 How to Play
1. Clone or download this repository.
2. Open `neurodash_antigravity.html` in any modern web browser.
3. Use the `Left / Right Arrow` keys or `A / D` to steer your ship.
4. Hold `Spacebar` for a speed boost.
