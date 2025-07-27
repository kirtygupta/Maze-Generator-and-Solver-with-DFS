# 🧩 Maze Generator and Solver with DFS

**Developer:** Kirty Gupta
**Technology Stack:** Python, Pygame

## 📌 Overview

This project implements a **maze generator and solver** using **Depth-First Search (DFS)** with backtracking. It visually demonstrates the step-by-step maze creation and solution process, making it ideal for understanding core algorithmic concepts such as recursion, graph traversal, and stack-based backtracking.

---

## 🎯 Features

* Maze generation using **Recursive Backtracking**
* Real-time animation using **Pygame**
* Color-coded visual cues:

  * 🟩 Green: Current path
  * 🔵 Blue: Backtracking
  * 🟡 Yellow: Final solution
* 20x20 grid visualization
* Efficient and randomized path generation

---

## 🧠 Motivation

This project was developed to:

* Visualize classic algorithms for better educational understanding
* Explore practical applications of DFS and recursion
* Create a foundational tool for AI, game development, and robotics

---

## 🧩 Problem Statement

Maze generation is essential in gaming and simulations. Challenges addressed:

* Random path generation with a unique solution
* Handling dead ends efficiently
* Real-time visualization and animation
* Clear solution path identification
* Optimal algorithm selection

---

## 🔧 Technology Stack

| Component    | Description                           |
| ------------ | ------------------------------------- |
| Python       | Core programming language             |
| Pygame       | Visualization and real-time rendering |
| Stack/Grid   | DFS backtracking and grid management  |
| Time Library | Animation delay control               |

---

## 🚀 How It Works

### ✅ Maze Generation:

* Implemented using **DFS with a stack** to backtrack when no unvisited neighbors exist.
* Each cell is visited, and walls are removed to create the path.

### ✅ Maze Solving:

* The solution path is traced using a dictionary that stores parent relationships between cells.

### ✅ Visual Output:

* The maze is dynamically drawn on a 20x20 grid.
* Color coding shows active paths, backtracked cells, and the final solution.

---

## 🛠️ Getting Started

### Prerequisites

* Python 3.x
* `pygame` module

```bash
pip install pygame
```

### Run the Program

1. Clone the repository:

   ```bash
   git clone https://github.com/kirtygupta/Maze-Generator-and-Solver-with-DFS.git
   cd Maze-Generator-and-Solver-with-DFS
   ```
2. Run the main Python script:

   ```bash
   python maze_generator.py
   ```

---

## 🖼️ Sample Output

✅ Randomized maze generation each run

  <img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/2ba6a762-4f7b-4067-acce-9b37a864f569" />

✅ Animated path creation and backtracking

  <img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/ee001a8f-da4e-4a8c-811f-5926fd5d337d" />
  <img width="300" height="300" alt="image" src="https://github.com/user-attachments/assets/bf42bee9-8c9a-4b38-9883-bccb4e1c23b0" />

✅ Final solution path drawn in yellow

  <img width="300" height="600" alt="image" src="https://github.com/user-attachments/assets/022a2025-f940-48eb-bba5-b5c724264364" />

---

## 📚 Future Scope

* Add alternative algorithms: Prim’s, Kruskal’s
* Scale to larger or custom grid sizes
* 3D maze generation for VR/AR
* AI integration: A\* or Dijkstra’s algorithm
* Interactive GUI for custom maze generation

---

## 📌 References

* [Depth-First Search - Wikipedia](https://en.wikipedia.org/wiki/Depth-first_search)
* [Backtracking - Wikipedia](https://en.wikipedia.org/wiki/Backtracking)
* [Pygame Documentation](https://www.pygame.org/docs/)

---

## 🙌 Acknowledgements

Special thanks to the academic resources and open-source contributors that inspired this educational project.

---

## 🧑‍💻 Author

**Kirty Gupta**
[GitHub Profile] : (https://github.com/kirtygupta)

---
