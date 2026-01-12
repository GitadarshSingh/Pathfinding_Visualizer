# Pathfinding_Visualizer
# 🚀 Pathfinding_Visualizer

![Build](https://img.shields.io/badge/Build-Static-success)
![Tech](https://img.shields.io/badge/Tech-JavaScript%20%7C%20HTML%20%7C%20CSS-blue)
![Algorithms](https://img.shields.io/badge/Algorithms-BFS%20%7C%20DFS%20%7C%20Dijkstra%20%7C%20A*-orange)

---

## 🧠 Overview

A **web-based pathfinding visualizer** designed to expose how classical graph algorithms explore a grid and compute optimal paths. This project prioritizes **algorithmic transparency**, **deterministic behavior**, and **visual clarity** over cosmetic complexity.

---

## 🎯 What This Project Demonstrates

* Real-time visualization of graph traversal
* Internal decision flow of search algorithms
* Separation of algorithm logic and UI rendering
* Production-ready static frontend build

---

## 🧩 Algorithms Implemented

| Algorithm   | Purpose                                       |
| ----------- | --------------------------------------------- |
| 🟦 BFS      | Guarantees shortest path in unweighted graphs |
| 🟨 DFS      | Explores depth-first, non-optimal             |
| 🟥 Dijkstra | Weighted shortest path algorithm              |
| 🟩 A*       | Heuristic-guided optimal search               |

All algorithms operate on the **same grid model**, enabling direct comparison.

---

## ✨ Core Features

* 🧱 Interactive grid system
* 🎯 Start & target node placement
* 🚧 Wall / obstacle creation
* 🎞️ Step-by-step animation
* 🧭 Shortest path reconstruction
* 🔁 Deterministic output for identical inputs

---

## 🛠️ Tech Stack

| Layer      | Tools                          |
| ---------- | ------------------------------ |
| Frontend   | HTML5, CSS3, JavaScript (ES6+) |
| Build Tool | Vite                           |
| Deployment | Static (Browser-ready)         |

---

## 📂 Project Structure

```text
Pathfinding_Visualizer/
├── dist/               # Production build output
│   ├── assets/
│   ├── index.html
│   ├── favicon-16x16.png
│   └── vite.svg
├── .vite/              # Vite dependency cache
├── .gitignore
└── README.md
```

---

## ⚙️ How It Works

* Each grid cell is treated as a **graph node**
* Adjacent cells form **edges**
* Algorithms track visited nodes and parents
* On reaching the target, the path is reconstructed via backtracking

---

## ▶️ Running the Project

This repository contains a **production build**.

Steps:

1. Clone the repository
2. Open `dist/index.html` in any modern browser

No server. No dependencies.

---

## 📚 Learning Outcomes

* Practical mastery of pathfinding algorithms
* Visual debugging of traversal logic
* Understanding of time vs space trade-offs
* Experience with modern frontend build tooling

---

## ⚠️ Limitations

* No diagonal movement
* Uniform grid cost
* Single-source to single-destination

---

## 🔮 Future Improvements

* 🧮 Weighted nodes
* ↘️ Diagonal movement
* 🌀 Maze generation algorithms
* 📊 Performance benchmarking overlay

---

## 👨‍💻 Author

**Adarsh Singh**

---

## 📜 License

Open-source. Intended for educational and demonstrative use.
