# DSA
# Graphs, Traversals and Topological Sort

An interactive web-based learning resource for understanding **Graphs and Graph Traversal Algorithms** in Data Structures.

This material is designed for students to learn graph concepts through simple explanations, examples, algorithms, complexity analysis, and interactive visualizations.

## Topics Covered

The webpage covers:

- Introduction to Graphs
- Graph Terminology
- Types of Graphs
- Graph Representations
  - Adjacency Matrix
  - Adjacency List
  - Edge List
- Depth First Search (DFS)
- Breadth First Search (BFS)
- DFS vs BFS
- Topological Sorting
  - Kahn's Algorithm
  - DFS-based Topological Sort
- Time and Space Complexity
- Graph representation complexity
- BFS and DFS complexity in the AI search model
- Self-check questions

## Interactive Features

The webpage includes interactive demonstrations for:

- Graph traversal
- DFS stack operations
- DFS backtracking
- BFS queue operations
- Step-by-step BFS traversal
- Adjacency matrix and adjacency list representation
- Kahn's Topological Sort
- In-degree updates
- Topological ordering
- Complexity visualization
- Self-check questions

Users can move through algorithms using controls such as:

- **Next**
- **Back**
- **Run**
- **Reset**

The traversal examples use alphabetical neighbour ordering so that the generated traversal sequence is reproducible.

## Learning Objectives

After using this resource, students should be able to:

1. Define a graph and identify its basic components.
2. Explain common graph terminology.
3. Differentiate directed, undirected, weighted, and acyclic graphs.
4. Represent graphs using adjacency matrices and adjacency lists.
5. Perform DFS and BFS traversals.
6. Explain the role of stacks and queues in graph traversal.
7. Perform topological sorting using Kahn's algorithm.
8. Explain DFS-based topological sorting.
9. Derive the time complexity of graph algorithms.
10. Select an appropriate graph representation for a given problem.

## Complexity Summary

| Algorithm | Adjacency List | Adjacency Matrix |
|-----------|----------------|------------------|
| DFS | O(V + E) | O(V²) |
| BFS | O(V + E) | O(V²) |
| Kahn's Topological Sort | O(V + E) | O(V²) |
| DFS Topological Sort | O(V + E) | O(V²) |
| Cycle Detection | O(V + E) | O(V²) |

Here:

- **V** = Number of vertices
- **E** = Number of edges

The course material also explains how the familiar `O(V + E)` graph-complexity model relates to the AI search complexity notation using branching factor `b`, solution depth `d`, and maximum depth `m`.

## How to Run Locally

Download or clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
