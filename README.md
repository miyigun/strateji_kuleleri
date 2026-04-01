# Strateji Kuleleri (Strategy Towers)

This repository contains a **3D strategic puzzle game** inspired by the Tower of Hanoi, featuring a unique "Prime Power" mechanic. Built with **Three.js**, it offers a high-fidelity, interactive browser experience with progressive difficulty levels.

---

## Features

### 1. 3D Game Engine (Three.js)
- **Immersive Environment:** Futuristic dark-themed arena with dynamic lighting, shadows, and fog effects.
- **Interactive Camera:** Full **OrbitControls** support (Drag to rotate, scroll/pinch to zoom, right-click to pan).
- **Smooth Animations:** Cinematic camera transitions between levels and procedural particle effects for victory celebrations.

### 2. Gameplay Mechanics
- **The Core Goal:** Move all disks from the starting tower to the **illuminated target tower** in a perfect pyramid shape.
- **Prime Power Mechanic:** Disks **2, 3, 5, and 7** are special. These "Prime Disks" can be placed on top of any other disk, regardless of size, acting as strategic bridges.
- **Standard Rule:** Except for Primes, a larger disk cannot be placed on top of a smaller one.

### 3. Progression & Scoring
- **8 Difficulty Levels:** Starting from 3 disks up to a challenging 10-disk arrangement.
- **Dynamic Scoring:** Points are calculated based on completion time and total moves.
- **Level Multipliers:** Higher levels grant significantly more points ($multiplier \times score$).

### 4. Technical UI/UX
- **Glassmorphism Design:** Modern UI overlay with blur effects and neon accents using **Tailwind CSS**.
- **Mobile Optimized:** Full touch support and a dedicated **Orientation Warning** system for the best landscape experience.
- **Audio System:** Web Audio API driven sound effects (click, error, success) and toggleable background music.

---

## 🛠️ Technologies Used
- **Three.js** (3D Rendering & Animations)
- **Tailwind CSS** (Modern UI Styling)
- **jQuery** (DOM Manipulation & Event Handling)
- **Web Audio API** (Procedural Sound Generation)

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone [https://github.com/miyigun/strateji_kuleleri.git](https://github.com/miyigun/strateji_kuleleri.git)

2. Open index.html in any modern web browser.

3. Note: For the best experience (and to ensure audio loads correctly), serving the file via a local server (e.g., Live Server in VS Code) is recommended.

### 📜 License
    This project is licensed under the MIT License.