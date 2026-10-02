# 🧬 Reaction-Diffusion
### How Nature Creates Patterns

> Simple chemical rules can generate spots, stripes, and organic textures — the same patterns seen on animal coats and shells.

![Status](https://img.shields.io/badge/Status-Educational%20Simulation-blue?style=for-the-badge)
![Concept](https://img.shields.io/badge/Concept-Self--Organization%20%7C%20Turing%20Patterns-orange?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20Canvas%20%7C%20JS-yellow?style=for-the-badge)

---

## 📌 About The Project

This simulation implements a **Gray-Scott reaction-diffusion system**. Two virtual chemicals interact and diffuse, creating complex patterns from simple rules.

You can adjust parameters live and watch spots, stripes, and labyrinths form and evolve.

---

## 🧠 Core Concepts

- Alan Turing’s morphogenesis theory
- Self-organization
- How local interactions create global patterns
- Parameter sensitivity in complex systems

---

## 🛠️ Tech Stack

**Recommended:**
- HTML + JavaScript + Canvas
- Two 2D grids (or one grid with two values)

**Performance upgrades:**
- Typed arrays (`Float32Array`)
- WebGL shader version (very fast)

---

## 🏗️ How to Build It

1. Create two grids (chemical A and chemical B)
2. Implement the Gray-Scott formulas
3. Apply diffusion + reaction each frame
4. Map values to colors
5. Add sliders for feed rate, kill rate, and diffusion rates
6. Add a “seed” brush so users can draw initial patterns

---

## ✨ Features (Version 1)

- Live parameter sliders
- Color mapping
- Reset / random seed
- Pause / play

---

## 🔮 Future Features

- Brush tool to paint chemicals
- Preset patterns (spots, stripes, worms, etc.)
- High-resolution export
- WebGL version for real-time high resolution
- 3D reaction-diffusion (advanced)

---

## 📄 License

MIT License
