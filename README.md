# Proximity Heatmap Tool 🌡️🔍

An interactive grid-based heatmap that visualizes spatial relationships using attractor/repeller mechanics. Built with vanilla JavaScript.

![Demo Screenshot](https://via.placeholder.com/800x400?text=Proximity+Heatmap+Demo) *(replace with actual screenshot)*

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
[Try it here!](https://your-username.github.io/Proximity-Heatmap-Tool)

## Installation
```bash
git clone https://github.com/your-username/Proximity-Heatmap-Tool.git
cd Proximity-Heatmap-Tool
open prototype[3.3].html
