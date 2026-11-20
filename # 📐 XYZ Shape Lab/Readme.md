# 📐 XYZ Shape Lab
### 3D Coordinate System & Shape Builder (Godot)

> An interactive 3D environment with permanent XYZ axes as the foundation.  
> Build, place, and examine shapes in real 3D space while learning how coordinates actually work.

![Status](https://img.shields.io/badge/Status-In%20Development-blue?style=for-the-badge)
![Engine](https://img.shields.io/badge/Engine-Godot%204-blueviolet?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-GDScript-orange?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Educational%20Tool-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 📌 About The Project

**XYZ Shape Lab** is an interactive 3D tool built in Godot that keeps the classic XYZ coordinate axes permanently visible as the background reference.

The goal is simple but powerful:

- See the three axes clearly (like the three-finger demonstration taught in school)
- Build and place 3D shapes using those axes as a guide
- Rotate and inspect the scene freely
- Develop a real intuition for 3D space and coordinates

This project is part of the Sci-Projects collection and is designed both as a learning tool and as practice in building a complete running application.

---

## 🎯 Why This Project

Most people only see static diagrams of the XYZ axes in textbooks.  
This tool makes the axes alive and lets you construct shapes directly on them.

It is also a deliberate exercise in:
- Learning a new engine (Godot)
- Building something that runs as a real application
- Debugging problems that appear while the program is running
- Strengthening spatial and problem-solving skills

---

## 🧠 Learning Goals

By building this project you will learn:

- Core Godot 3D workflow (scenes, nodes, MeshInstance3D, cameras)
- How coordinate systems work in practice
- Camera controls and spatial navigation
- Basic 3D mesh creation and manipulation
- Structuring a small but complete interactive application
- Debugging a live running program

---

## ✨ Features

### Phase 1 – Foundation
- Permanent, color-coded XYZ axes with arrows and labels
- Ground grid (XZ plane)
- Orbit camera (rotate, zoom, pan)
- Basic lighting so shapes are clearly visible

### Phase 2 – Shape Creation
- Spawn basic shapes (Box, Sphere, Cylinder, Prism, etc.)
- Place shapes at specific coordinates
- Simple UI panel to control shape creation

### Phase 3 – Interaction & Learning Tools
- Select and move existing shapes
- Display live coordinates of selected objects
- Reset scene
- Optional: distance and angle measurement

### Future Ideas
- Custom shape building (place vertices → form faces)
- Right-hand rule visual helper
- Save / load scenes
- Export current view as an image

---

## 🛠️ Tech Stack

| Component       | Technology     | Purpose                        |
|-----------------|----------------|--------------------------------|
| Engine          | Godot 4        | Full 3D application framework  |
| Language        | GDScript       | Main scripting language        |
| Rendering       | Godot 3D       | Real-time 3D graphics          |
| UI              | Godot Control nodes | Menus and side panels     |
| Platform        | Desktop        | Runs as a standalone app       |

---

## 📂 Suggested Project Structure

```text
xyz-shape-lab/
│
├── scenes/
│   ├── Main.tscn
│   ├── AxisSystem.tscn
│   └── UI.tscn
│
├── scripts/
│   ├── Main.gd
│   ├── AxisSystem.gd
│   ├── ShapeSpawner.gd
│   └── CameraController.gd
│
├── meshes/               # Optional custom meshes
├── materials/
├── project.godot
└── README.md
