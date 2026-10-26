
# 🤖 Braitenberg Vehicles
### Simple Feedback, Complex Behavior

> A visual simulation of Braitenberg Vehicles — simple machines whose behavior looks intelligent, emotional, or purposeful, even though they are built from nothing more than sensors, motors, and feedback connections.

![Status](https://img.shields.io/badge/Status-Educational%20Simulation-blue?style=for-the-badge)
![Concept](https://img.shields.io/badge/Concept-Cybernetics%20%7C%20Intelligence-orange?style=for-the-badge)
![Stack](https://img.shields.io/badge/Stack-HTML%20%7C%20Canvas%20%7C%20JavaScript-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📌 About The Project

This project simulates **Braitenberg Vehicles**, a classic idea from cybernetics and the study of intelligence.

Each vehicle is extremely simple:
- Sensors (usually light sensors)
- Motors
- Wires connecting sensors to motors

By changing only how the sensors are connected to the motors, the vehicles produce surprisingly rich behaviors that look like:
- Fear
- Aggression
- Attraction
- Exploration
- Indifference

The deep question this project explores:

> How much of what we call “intelligence” can emerge from simple feedback loops?

---

## 🧠 Core Concepts

- **Cybernetics**: Control and communication through feedback
- **Feedback loops**: Sensor → decision → action → environment → sensor
- **Emergence**: Complex behavior from simple rules
- **Intelligence as control**: The ability to act in relation to goals or conditions
- **Synthetic psychology**: Understanding behavior by building it

This project sits at the intersection of cybernetics, artificial life, and theories of mind.

---

## ✨ Features

### Version 1
- Multiple vehicle types with different sensor-motor wirings
- Light sources in the environment
- Real-time movement and interaction
- Clear visual distinction between vehicle “personalities”
- Ability to add/remove lights and vehicles

### Planned
- Obstacle sensors
- Noise / imperfect sensors
- Adjustable connection strengths
- Vehicle trails
- Side-by-side comparison mode
- More complex vehicles (multiple sensors, internal states)

---

## 🛠️ Tech Stack

| Part            | Technology              | Purpose                     |
|-----------------|-------------------------|-----------------------------|
| Language        | JavaScript              | Core logic                  |
| Rendering       | HTML5 Canvas            | Visual simulation           |
| UI              | HTML + CSS              | Controls and layout         |
| Architecture    | Vanilla JS (or p5.js)   | Keep it simple and clear    |

No heavy frameworks required. Clarity is more important than sophistication here.

---

## 📂 Suggested Project Structure

```text
braitenberg-vehicles/
│
├── index.html
├── css/
│   └── styles.css
├── js/
│   ├── main.js
│   ├── vehicle.js
│   ├── sensor.js
│   ├── environment.js
│   └── utils.js
└── README.md
