# Graph Algorithm Animations
### Chapter 13 · Lesson 7

Interactive step-by-step animations for the four fundamental graph algorithms covered in Chapter 13. Built with plain HTML, CSS, and JavaScript — no frameworks or dependencies required.

---

## Live Demo

Deploy via GitHub Pages and access at:
```
https://<your-username>.github.io/<repo-name>/
```

---

## Pages

| File | Algorithm | Section |
|------|-----------|---------|
| `index.html` | Home / Lesson 7 overview | — |
| `bfs_dfs_animation.html` | BFS & DFS Traversal | §13.1–13.2 |
| `prims_two_examples.html` | Prim's Algorithm | §13.8.2 |
| `kruskals_example.html` | Kruskal's Algorithm | §13.8.3 |
| `dijkstra_example.html` | Dijkstra's Algorithm | §13.8.4 |

---

## Algorithms Covered

**BFS & DFS** — Graph traversal using a Queue (BFS) and Stack (DFS). Demonstrates level-by-level vs depth-first exploration on a directed graph. Time complexity: O(V + E).

**Prim's Algorithm** — Minimum Spanning Tree built by greedily adding the cheapest fringe edge. Two textbook examples (Fig 13.31 and Fig 13.32). Time complexity: O(E log V).

**Kruskal's Algorithm** — Minimum Spanning Tree built by sorting all edges and adding them if they don't form a cycle, using a Union-Find forest. Graph A–F, total MST weight = 17. Time complexity: O(E log E).

**Dijkstra's Algorithm** — Single-source shortest path on a directed weighted graph (Fig 13.36), starting from node D. Time complexity: O((V + E) log V).

---

## How to Use

Each page has three controls:

- **▶ Play** — auto-plays through all steps with a delay
- **Next Step** — manually advance one step at a time
- **Reset** — return to the initial state

Every page also has a **← Back to Lesson 7** link at the top to return to the index.

---

## Deploying to GitHub Pages

1. Push all files to the **root** of your repository's `main` branch
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Save — your site will be live in a few seconds

> All 5 files must be in the same folder for the links between pages to work.

---

## File Structure

```
/
├── index.html
├── bfs_dfs_animation.html
├── prims_two_examples.html
├── kruskals_example.html
├── dijkstra_example.html
└── README.md
```

---

*Chapter 13 · Data Structures and Algorithms*
