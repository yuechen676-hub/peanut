# Two Independent p5.js Works (Archive)

This repository contains **two separate, independent p5.js projects**, stored as zip archives.  
Each work can be viewed/run on its own.

---

## 1) Darkened_burst_2026_01_15_15_06_16.zip

**Description:**  
An interactive p5.js “emoji clock” visualization that represents a day as segmented activities.  
Each segment is drawn as an emoji grid, where emoji count corresponds to duration. The sketch supports both **real-time mode** and **accelerated simulation mode**.

**Activity Segments (default setup):**
- Daytime games 🕹️☀️ (330 minutes)  
- Night game 🎮🌛 (180 minutes)  
- Social time 📱📺 (350 minutes)  
- Commuting time 💻🚌 (75 minutes)  
- Mealtime 🍜🍱 (80 minutes)  
- Bath and Sleep 🛁😴 (425 minutes)

**How to Run:**
- Open the sketch with **p5.js** (p5 Web Editor or a local p5.js setup)
- Run the main JavaScript sketch file inside the zip archive (e.g., `sketch.js`)

**Keyboard Controls:**
- `T` — Toggle **Real Time** / **Simulation**  
- `← / →` — Switch displayed segment (visual override only)  
- `1–6` — Jump to a segment display (visual only)  
- `+ / -` — Increase/decrease simulation speed (Simulation mode only)  
- `A` — Return to automatic display following time  

**Adjustable Parameters (in code):**
- `MINUTES_PER_EMOJI` (default: 15)  
- `simSpeed` (default: 60 virtual minutes per second)

---

## 2) FIGHTING_APPLE_2026_01_11_18_41_04.zip  
*(If your actual filename is slightly different, please rename this line to match.)*

**Description:**  
A responsive p5.js + p5.sound microphone game with **3 levels**. The player is a pixel-art apple runner that moves forward based on **voice volume**.  
Sustained, steady voice spawns **affirmation bubbles** rising bottom→top (always rendered on the top layer). The world “remembers” these affirmations: more bubbles gradually make the game easier by lowering the threshold and reducing chain strength.

**Core Mechanics:**
- **Louder voice → faster movement**
- **Steady voice → affirmation bubbles**
- **More affirmations → easier world**
  - Lowers effective volume threshold  
  - Weakens chain resistance requirement  

**How to Play / Run:**
- Requires **p5.js** and **p5.sound**
- Run the main sketch file inside the zip archive (e.g., `sketch.js`)
- Click **START** and allow microphone access
- Stay quiet for ~2 seconds for calibration, then speak to play

**Controls:**
- Mouse: Click **START** to begin and enable microphone  
- Drag slider: Adjust **sensitivity**  
- `SPACE`: Continue to next level (after “Level Clear”)  
- `R`: Restart  

**Notable Features:**
- Pixel-art sprite + custom 5x7 bitmap font
- Pixel UI panels + HUD bars (VOL / ENG / NUR)
- Screen shake feedback on chain collision
- Bubbles always render above HUD/overlays

---

## Notes
- These are **two independent works** packaged as zip archives.
- If GitHub blocks large files, consider using **Git LFS** or hosting the zip elsewhere and linking it here.
