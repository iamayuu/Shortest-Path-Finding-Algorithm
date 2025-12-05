<h1 align="center"> Shortest-Path-Finding-Visualizer-A*-Algorithm</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Algorithm-A*%20Search-blue" />
  <img src="https://img.shields.io/badge/Language-Python-green" />
  <img src="https://img.shields.io/badge/Library-Pygame-orange" />
  <img src="https://img.shields.io/github/license/ayush/repo?color=yellow" />
</p>

<p align="center">
  An interactive grid based visualization of the A* shortest path algorithm.
</p>

---

## 📌 Features

- 🟩 Real time A* search visualization  
- 🟧 Click to place start, end, and walls  
- 🟥 Clear coloring for open, closed, and path nodes  
- 🎯 Manhattan heuristic for optimal path  
- 🪟 Clean 50 x 50 interactive grid

---

## 🎨 Color Legend

| Color | Meaning |
|-------|---------|
| 🟧 Orange | Start node |
| 🟦 Turquoise | End node |
| ⬛ Black | Barrier |
| 🟩 Green | Open node |
| 🟥 Red | Closed node |
| 🟪 Purple | Final path |

---

## 🧠 How It Works

A* ranks nodes based on  
**f = g + h**,  
where g is the cost from the start and h is the Manhattan distance to the target.

A priority queue selects the next best node. Once the end is reached, the path is reconstructed by backtracking through parent references.

---

## 🎮 Controls

| Action | Input |
|--------|--------|
| Place start, end, walls | Left click |
| Remove tile | Right click |
| Run algorithm | Spacebar |
| Clear grid | C key |

---

## 🛠 Installation

Install Python and Pygame.

```bash
pip install pygame

```
---
## 🚀 Future Ideas

- Add diagonal movement and weighted terrain for more realistic pathfinding.
- Provide multiple algorithms such as Dijkstra, BFS, and Greedy Best First.
- Introduce UI buttons and on screen controls instead of keyboard only input.
- Allow saving and loading grid layouts for reuse.
- Add performance stats like explored nodes and execution time.

