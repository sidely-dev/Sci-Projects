# 📟 Cellular Automata Rule Explorer
### 256 Universes in One Grid

> Rule 30 produces chaos.  
> Rule 110 is Turing complete.  
> Rule 90 creates perfect fractals.  
> This project lets you explore all 256 elementary cellular automata.

![Status](https://img.shields.io/badge/Status-Educational%20Tool-blue?style=for-the-badge)
![Concept](https://img.shields.io/badge/Concept-Complexity%20%7C%20Emergence-orange?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20Canvas%20%7C%20JS-yellow?style=for-the-badge)

---

## 📌 About The Project

Elementary Cellular Automata are one-dimensional binary systems with extremely simple rules. Despite their simplicity, they produce four broad classes of behavior (Wolfram’s classification):

- Class 1: Dies out
- Class 2: Stable / periodic
- Class 3: Chaotic
- Class 4: Complex / edge of chaos

This tool lets you select any rule (0–255) and watch it evolve.

---

## 🧠 Core Concepts

- Emergence from simple rules
- Wolfram’s classification of complexity
- Deterministic systems that still look random
- The edge of chaos

---

## 🛠️ Tech Stack

- HTML + CSS + JavaScript
- Canvas (or even pure DOM for learning)
- Optional: p5.js

---

## 🏗️ How to Build It

1. Represent the current row as an array of 0s and 1s
2. Create a function that takes three cells and returns the next state according to the selected rule
3. Generate new rows over time
4. Draw the history as a 2D grid (time goes downward)
5. Add a rule number input / slider (0–255)
6. Show the binary rule breakdown

---

## ✨ Features (Version 1)

- Rule selector (0–255)
- Random or single-cell starting condition
- Speed control
- Color themes

---

## 🔮 Future Features

- Side-by-side rule comparison
- Rule favorites / bookmarks
- Export image
- Automatic classification (chaotic vs complex)
- 2D cellular automata mode later

---

## 📄 License

MIT License
