# Search-and-Problem-Solving-AI
Optimization Problems using Search Algorithms (BFS, DFS and UCS)

# Optimal Graph Structures Search and Problem Solving

This repository contains the implementation of various search algorithms to find the optimal ordering of vertices in a graph, aimed at minimizing the cost of parent sets associated with each vertex. This optimization problem is significant in various fields, including Bayesian Network Learning.

## Problem Description

The problem is defined as follows:

- We are given a set of vertices ( V_1, .... , V_n ) and possible parent sets for each vertex.
- Each parent set has an associated cost.
- Given an ordering (O) (a permutation) of the vertices, a parent set of vertex (V_i) is consistent with (O) if all of the parents come before (V_i) in the ordering.
- The objective is to find an ordering (O) that minimizes the total cost of the network:

## Search Algorithms Implemented

The following search algorithms were implemented to solve the optimization problem:

1. **Breadth-First Search (BFS)**
2. **Depth-First Search (DFS)**
3. **Uniform Cost Search (UCS)**

## Datasets

Three datasets are provided for experimentation, in addition to the simple examples described above. The datasets contain vertices and their possible parent sets along with the associated costs.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/optimal-graph-structures.git

