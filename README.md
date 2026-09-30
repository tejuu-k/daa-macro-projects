# Design and Analysis of Algorithms (DAA) - Macro Projects

This repository contains selected project implementations for Units I through V of the DAA course.

---

## Project Index

| Unit | Topic | Selected Project | Technique |
| :--- | :--- | :--- | :--- |
| **Unit I** | Algorithm Analysis | Recursion Tree for Merge Sort | Divide & Conquer Analysis |
| **Unit II** | Divide & Conquer / Greedy | Optimal Merge Pattern Tree | Greedy Strategy |
| **Unit III** | Dynamic Programming | 0/1 Knapsack DP Table | Dynamic Programming |
| **Unit IV** | Backtracking | N-Queens State Space Tree | Backtracking Traversal |
| **Unit V** | Branch and Bound | Knapsack Search Tree | Branch and Bound Pruning |

---

## Detailed Project Descriptions

### Unit I: Merge Sort Recursion Tree
* **Prompt Used:** *"Draw a recursion tree for Merge Sort dividing an array of 8 elements."*
* **Core Concept:** Demonstrates $O(N \log N)$ complexity by recursively dividing inputs into $O(\log N)$ levels with $O(N)$ merge cost per level.

### Unit II: Optimal Merge Pattern
* **Prompt Used:** *"Draw a binary tree showing optimal merge pattern for files of sizes 10, 20, 30, 40."*
* **Core Concept:** Minimizes file read/write operations by applying a Min-Heap based Greedy strategy.

### Unit III: 0/1 Knapsack DP
* **Prompt Used:** *"Draw a DP table for 0/1 Knapsack with 4 items and capacity 10."*
* **Core Concept:** Solves overlapping subproblems through bottom-up memoization matrix optimization.

### Unit IV: 4-Queens Backtracking
* **Prompt Used:** *"Visualize the state space tree for N = 4 queens, marking invalid branches."*
* **Core Concept:** Systematically explores placement possibilities using Depth-First Search (DFS) while pruning dead ends.

### Unit V: Branch & Bound Knapsack
* **Prompt Used:** *"Illustrate bounding and pruning in 0/1 Knapsack using node values."*
* **Core Concept:** Best-First Search using linear programming bounds to prune sub-optimal subtrees.
