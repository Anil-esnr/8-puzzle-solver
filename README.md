# 8-Puzzle Solver

This project implements a solver for the classic 8-puzzle problem using multiple search algorithms.  
It was developed as part of an Artificial Intelligence course project.

## Implemented Algorithms

- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Uniform Cost Search (UCS)
- Depth Limited Search
- Iterative Deepening Search
- Greedy Search
- A* Search
- Generalized A* Search

## Heuristic

The A* implementation uses the **Manhattan Distance with Linear Conflict** heuristic to improve search efficiency.

## Project Structure

- `GRAPH_SEARCH.c / .h` – Graph search implementations  
- `HashTable.c / .h` – Data structure used for visited states  
- `SpecificToProblem.c` – Puzzle-specific logic  
- `Standart_Search.c` – Search algorithm implementations  
- `data_types.h` – Data structures used in the project  

## Language

C
