# ⚙️ The Edge of Rules and Chaos
### Rigid Logic vs. Emergent Chaos

> A visual exploration of determinism versus complexity.  
> One side follows perfect mathematical rules. The other follows simple local rules injected with chaos — and produces unpredictable, emergent behavior.

![Status](https://img.shields.io/badge/Status-Educational%20Demo-blue?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Interactive%20Simulation-orange?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20CSS%20%7C%20JavaScript-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📌 About The Project

This project places two systems side by side:

- **Left – Rigid Logic (Deterministic)**  
  A system built from pure mathematics (trigonometry and constant angular increments).  
  It is completely predictable and will loop forever without deviation.

- **Right – Emergent Grid (Complex System)**  
  A cellular automaton based on Conway’s Game of Life rules, with an adjustable mutation rate.  
  Small random changes snowball into complex, unpredictable patterns.

The goal is to make the difference between **perfect determinism** and **emergence through local rules + chaos** visible and interactive.

---

## 🎯 Learning Goals

- Understand what a deterministic system looks like in practice
- See how simple local rules can create complex behavior
- Observe the effect of injecting randomness (mutation) into a rule-based system
- Explore concepts from complexity science and chaos theory in a visual way
- Practice canvas animation and real-time simulation in vanilla JavaScript

---

## ✨ Features

- Side-by-side comparison of two systems
- Smooth 60 FPS animation loop
- Adjustable **Chaos / Mutation Rate** slider (0–15%)
- Reset button for the emergent grid
- Clean dark UI
- Fully self-contained (single HTML file)

---

## 🧠 How It Works

### Rigid Logic (Left Canvas)
- Uses trigonometry (`Math.cos`, `Math.sin`) to position colored dots
- Alternating rotation directions
- Constant angle increment every frame → perfectly predictable and looping

### Emergent Grid (Right Canvas)
- 40×40 grid
- Classic Conway’s Game of Life rules:
  - A dead cell with exactly 3 live neighbors becomes alive
  - A live cell with fewer than 2 or more than 3 neighbors dies
- **Mutation layer**: On every update, cells have a chance (controlled by the slider) to randomly flip state
- Higher mutation rates create more chaotic, less stable patterns

---

## 🛠️ Tech Stack

| Part       | Technology              |
|------------|-------------------------|
| Structure  | HTML5                   |
| Styling    | CSS3 (Flexbox, modern dark theme) |
| Logic      | Vanilla JavaScript      |
| Rendering  | HTML5 Canvas API        |
| Animation  | `requestAnimationFrame` |

No frameworks. No build tools. Just open the file in a browser.

---

## 📂 Project Structure

```text
edge-of-rules-and-chaos/
│
├── index.html          # Complete application (HTML + CSS + JS)
└── README.md
