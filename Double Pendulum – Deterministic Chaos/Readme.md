# 🌀 Double Pendulum
### Deterministic Chaos in Motion

> A simple pendulum is perfectly predictable.  
> A double pendulum follows the same deterministic physics — yet becomes wildly chaotic.  
> This project makes that difference visible.

![Status](https://img.shields.io/badge/Status-Educational%20Simulation-blue?style=for-the-badge)
![Concept](https://img.shields.io/badge/Concept-Chaos%20Theory-orange?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20Canvas%20%7C%20JS-yellow?style=for-the-badge)

---

## 📌 About The Project

This simulation shows two systems side by side:

- **Left**: Single pendulum (orderly and predictable)
- **Right**: Double pendulum (deterministic but chaotic)

Both systems use pure physics equations with no randomness. The chaos emerges purely from the sensitivity of the double pendulum to its initial conditions.

---

## 🧠 Core Concepts

- Deterministic chaos
- Sensitivity to initial conditions
- Phase space and strange attractors
- Why some systems are predictable and others are not (even with perfect math)

---

## 🛠️ Tech Stack

**Recommended (start here):**
- HTML + CSS + JavaScript
- HTML5 Canvas
- `requestAnimationFrame`

**Optional upgrades later:**
- p5.js (easier drawing)
- Matter.js or custom RK4 integrator for higher accuracy
- WebGL for smoother trails

---

## 🏗️ How to Build It

1. Create two canvases side by side
2. Implement a simple pendulum using basic trigonometry / angular acceleration
3. Implement a double pendulum using the standard Lagrangian equations (or simplified physics)
4. Draw the arms and bobs
5. Add fading trails so the chaotic path becomes visible
6. Add controls: reset, change initial angles, toggle trails, slow-motion

---

## ✨ Features (Version 1)

- Side-by-side single vs double pendulum
- Real-time animation
- Trail rendering
- Reset button
- Adjustable initial angles

---

## 🔮 Future Features

- Multiple double pendulums with tiny differences in starting angle
- Phase space plot
- Energy display
- Slow-motion / speed control
- Export path as image
- 3D double pendulum (advanced)

---

## 📄 License

MIT License
