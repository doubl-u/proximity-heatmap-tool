# Proximity Heatmap Tool 🌡️🔍

An interactive grid-based heatmap that visualizes spatial relationships using attractor/repeller mechanics. Built with vanilla JavaScript.

![Screenshot](https://github.com/user-attachments/assets/928f7f2d-c771-4e48-ac1e-803e64d9652c)

## Key Features
- **Dynamic Heatmaps**: Real-time color gradients (red → blue) reflect proximity values
- **Attractor/Repeller System**:
  - `X` marks **attractors** (highlight proximity)
  - `O` marks **repellers** (highlight distance)
- **Customizable Grid**: Adjustable rows/columns
- **Distance Algorithm**: Uses Manhattan distance (`|x₁-x₂| + |y₁-y₂|`)

## How to Use
1. Click cells to place `X` (attractor) or `O` (repeller)
2. Watch the heatmap update instantly
3. Adjust grid size using the input fields
4. Click "Clear" to reset

## Live Demo
[Try it here!](https://doubl-u.github.io/proximity-heatmap-tool)

## Installation
```bash
git clone https://github.com/your-username/Proximity-Heatmap-Tool.git
cd Proximity-Heatmap-Tool
open prototype[3.3].html
