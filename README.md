# Adversarial Search and Uninformed/ Informed Search Algorithms for Pac-Man # 🟡👾

## Overview
This project applies various artificial intelligence techniques to the classic Pac-Man game. It includes implementations of different search algorithms to navigate and solve problems in Pac-Man's maze environment. The main focus is on three categories of search algorithms: **Uninformed Search**, **Informed Search**, and **Adversarial Search**.

### 1. Uninformed Search
Uninformed search algorithms explore the state space without any additional information about the goal. The following algorithms are implemented:
- **Depth-First Search (DFS)**: Expands nodes by exploring the deepest node first.
- **Breadth-First Search (BFS)**: Explores all nodes at the present depth before moving to nodes at the next depth level.
- **Uniform-Cost Search (UCS)**: Expands the node with the least total cost.

### 2. Informed Search
Informed search algorithms use additional knowledge (heuristics) to make the search process more efficient.
- **A* Search**: A combination of UCS and heuristic guidance, minimizing the total cost from start to goal.
- **Heuristic Solutions**: Implemented for specific Pac-Man problems like finding corners and eating all dots, guiding the search using the Manhattan distance.

### 3. Adversarial Search
This category involves simulating interactions between Pac-Man and ghosts, where the optimal strategy needs to account for the adversarial nature of the problem.
- **Reflex Agent**: A basic agent that reacts to the current state without any planning.
- **Minimax Algorithm**: A decision-making algorithm for two-player games.
- **Alpha-Beta Pruning**: An optimization of the minimax algorithm to avoid redundant calculations.

## Requirements
- Python 3.x
- Required libraries: `numpy`, `pacman` etc.\
  

This project highlights the power of search algorithms in AI-driven game strategies, demonstrating their applications in real-time decision-making and adversarial planning. 🚀
