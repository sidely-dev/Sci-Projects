# 🐦 Boids: Order vs Chaos
### Emergence in Flocking Behavior

> Simple local rules create elegant flocking.  
> Add noise or fear, and the same system collapses into chaos.

![Status](https://img.shields.io/badge/Status-Educational%20Simulation-blue?style=for-the-badge)
![Concept](https://img.shields.io/badge/Concept-Emergence%20%7C%20Swarm%20Intelligence-orange?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20Canvas%20%7C%20JS-yellow?style=for-the-badge)

---

## 📌 About The Project

This project implements Craig Reynolds’ classic **Boids** algorithm and lets you compare:

- **Ordered mode**: Clean separation, alignment, and cohesion
- **Chaotic mode**: Same rules + noise, random forces, or predator fear

You can watch organized flocks form and then break apart as chaos is introduced.

---

## 🧠 Core Concepts

- Emergence
- Self-organization
- Local rules → global behavior
- Swarm intelligence
- How noise affects coordinated systems

---

## 🛠️ Tech Stack

**Recommended:**
- HTML + CSS + JavaScript
- HTML5 Canvas

**Later upgrades:**
- p5.js
- Offscreen canvas for performance
- Web Workers if simulating hundreds of agents

---

## 🏗️ How to Build It

1. Create a `Boid` class with position, velocity, and acceleration
2. Implement the three classic rules:
   - Separation
   - Alignment
   - Cohesion
3. Add boundary wrapping or steering
4. Create two simulation panels (or one with a chaos toggle)
5. Add a chaos/noise slider and a “predator” mode
6. Render boids as triangles pointing in their direction of movement

---

## ✨ Features (Version 1)

- Adjustable number of boids
- Separation / Alignment / Cohesion strength sliders
- Chaos / noise slider
- Reset button
- Trail option

---

## 🔮 Future Features

- Predator that scares the flock
- Obstacle avoidance
- Multiple species
- 3D boids
- Save/load rule presets

---

## 📄 License

MIT License
