# ?? 3D Rubik's Cube Solver - WebGL Build

[![Play Live Demo](https://img.shields.io/badge/Play-Live%20Demo-brightgreen?style=for-the-badge&logo=googlechrome)](https://hermedev.github.io/Rubiks-Cube-Solver-play/)
[![Source Code](https://img.shields.io/badge/Source-Unity%20Project-blue?style=for-the-badge&logo=unity)](https://github.com/hermedev/-Rubik-s-Cube-Solver)

This repository contains the standalone **WebGL production build** for the **3D Rubik's Cube Solver**, ready to run directly in any modern desktop or mobile web browser.

?? **Play Online:** [https://hermedev.github.io/Rubiks-Cube-Solver-play/](https://hermedev.github.io/Rubiks-Cube-Solver-play/)

---

## ?? Features

- **In-Browser 3D Simulation**: High-fidelity 3D Rubik's Cube powered by Unity 6 WebGL and Universal Render Pipeline (URP).
- **Kociemba Algorithm Solver**: Rapidly finds and demonstrates the solution for any scrambled cube state.
- **Interactive Controls**:
  - **Click & Drag Background**: Free camera orbit around the cube.
  - **Click & Drag Faces**: Rotate individual layers / slices.
  - **Shuffle**: Scramble the cube randomly.
  - **Solve**: Watch the step-by-step automated solution unfold in real-time.
- **Optimized for GitHub Pages**: Built with uncompressed WebGL distribution and `.nojekyll` support to ensure instant loading without MIME or compression header errors.

---

## ??? Controls

| Action | Input |
| :--- | :--- |
| **Orbit Cube** | Left Click + Drag on empty background |
| **Rotate Layer / Slice** | Click and drag on any cube face |
| **Scramble** | Click **Shuffle** in the UI |
| **Auto-Solve** | Click **Solve** to compute and animate moves |

---

## ??? GitHub Pages Setup

To host this repository on GitHub Pages:

1. Open your repository on GitHub: [`hermedev/Rubiks-Cube-Solver-play`](https://github.com/hermedev/Rubiks-Cube-Solver-play).
2. Go to **Settings** $\rightarrow$ **Pages** (under the "Code and automation" section).
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` and folder `/(root)`.
4. Click **Save**.
5. After 1-2 minutes, your game will be live at:
   ```
   https://hermedev.github.io/Rubiks-Cube-Solver-play/
   ```

> **Note:** The included `.nojekyll` file prevents GitHub Pages' Jekyll engine from ignoring internal WebGL files and subdirectories.

---

## ?? Project Source Code

The complete Unity 6 project source code, shaders, prefabs, and C# scripts are available at:
?? **[https://github.com/hermedev/-Rubik-s-Cube-Solver](https://github.com/hermedev/-Rubik-s-Cube-Solver)**

---

## ?? License

This project is licensed under the MIT License.
