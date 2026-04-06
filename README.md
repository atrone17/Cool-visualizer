# Pathfinding Visualizer

A browser-based tool that lets you watch pathfinding algorithms work in real time. Draw walls, generate mazes, and see how different algorithms find (or fail to find) a path.

Built this mostly to understand the difference between algorithms like A* and BFS — turns out watching them visually makes it way easier to grasp.

---

## Algorithms

- **A\*** — uses a heuristic to guide the search toward the goal, usually the fastest
- **Dijkstra's** — explores by shortest distance, guaranteed optimal path
- **BFS** — explores layer by layer, good for unweighted grids
- **DFS** — goes deep fast, doesn't always find the shortest path

---

## How to use

1. Click and drag on the grid to draw walls
2. Press **S** then click to move the start point
3. Press **E** then click to move the end point
4. Hit **Run** and watch it go
5. Use **Gen Maze** to auto-generate a maze to solve

You can also adjust the speed slider to slow it down and actually see what the algorithm is doing step by step.

---

## Run it locally

No install needed. Just open `index.html` in your browser.

```
git clone https://github.com/yourusername/pathfinding-visualizer
cd pathfinding-visualizer
open index.html
```

Or visit the live demo on GitHub Pages.

---

## Stack

Plain HTML, CSS, and vanilla JS. No frameworks, no dependencies, no build step.

---

Made by Aditya
