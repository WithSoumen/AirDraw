# 🌌 Air Draw — Gesture-Powered Air Canvas

[![License: MIT](https://img.shields.io/badge/License-MIT-00f5ff.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Web-Ready](https://img.shields.io/badge/Platform-Web%20%2F%20AR-ff2df7.svg?style=for-the-badge)](https://heyysizzii.github.io/Darling/)
[![Built With](https://img.shields.io/badge/Tech-MediaPipe%20%2B%20HTML5-ffe600.svg?style=for-the-badge)]()

An immersive, futuristic, in-browser Augmented Reality drawing application that turns your hand into a digital paintbrush. Using cutting-edge computer vision, **Air Draw** tracks your hand landmarks in real-time, allowing you to paint, hover, erase, and manipulate strokes directly in the air without touching your device.

✨ **[Live Demo — Draw in Air Now!](https://heyysizzii.github.io/AirDraw/)** ✨

---

## 🚀 Key Features

* **Real-Time Hand Tracking:** Powered by Google MediaPipe Hands for smooth, high-precision detection.
* **Dynamic Particle Engine:** Spawns glowing sparks as you sketch, enhancing visual responsiveness.
* **Glow-Infused Neon Inks:** Toggle beautiful neon bloom aesthetics across an array of color palettes.
* **Fully App-State Aware:** Complete with multi-step Undo ($Ctrl+Z$) / Redo ($Ctrl+Y$) systems and smart action inhibition to prevent ghost marks.
* **Responsive Control Panel:** Fluid brush-size adjustment, quick-clear controls, and automated high-resolution `.png` canvas exporting.

---

## 🕹️ Gesture Guide Matrix

Air Draw relies on intuitive hand configurations to trigger different operations automatically. Keep your hand visible to your webcam to interact:

| Gesture | Hand Configuration | Active Action Mode | Neon Indicator |
| :---: | :--- | :--- | :--- |
| **☝️** | **Index finger up**, all other fingers folded | **DRAW:** Paints lines on the digital board | Magenta Grid |
| **✌️** | **Index + Middle up**, ring + pinky folded | **HOVER:** Moves crosshair without committing ink | Cyan Dot |
| **🤏** | **Thumb + Index pinched tightly together** | **ERASE:** Wipes lines within the eraser boundary | Yellow Ring |
| **✋** | **Full open palm** (all fingers extended) | **MOVE:** Grabs and offsets the closest static line | Green Light |

---

## 🛠️ Built With

* **HTML5 Canvas (Dual Layer):** Separate rendering planes context-optimized for low-latency skeleton rendering and permanent brush strokes.
* **MediaPipe Hands SDK:** Machine-learning pipeline for ultra-low latency coordinate estimation.
* **CSS Next Variables & Syne Typography:** Styled around a cyberpunk cyberpunk-synthwave inspired dark-mode framework.
