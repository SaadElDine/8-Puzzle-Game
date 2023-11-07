# 8-Puzzle-Game
This is an 8-Puzzle solver application that uses various search algorithms to find the optimal solution to the classic 8-Puzzle game. The 8-Puzzle is a sliding puzzle that consists of a 3x3 grid with 8 numbered tiles and an empty space. The objective is to rearrange the tiles from their initial state to a target state by sliding them into the empty space.

This project provides a graphical user interface (GUI) for you to input the initial state of the puzzle and choose from three different search algorithms: Depth-First Search (DFS), Breadth-First Search (BFS), and A* Search. A* Search also allows you to select between two heuristic functions: Manhattan Distance and Euclidean Distance.

![Screenshot 2023-11-03 235100](https://github.com/SaadElDine/8-Puzzle-Game/assets/113860522/df5adddd-a916-4d21-b459-bbac0e804edd)

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [How to Use](#how-to-use)
- [Algorithms](#algorithms)
- [Demo](#demo)

## Introduction

The 8-Puzzle Solver is a Python application that allows you to interactively solve the classic 8-Puzzle game using various search algorithms. The 8-Puzzle is a sliding puzzle consisting of a 3x3 grid with 8 numbered tiles and an empty space. The goal is to rearrange the tiles from an initial state to a target state by sliding them into the empty space. This application provides a graphical user interface (GUI) for inputting the initial state, selecting search algorithms, and visualizing the solution path.

## Prerequisites

Before using this application, you'll need to have the following installed on your system:

- Python 3
- `tkinter` (Python's standard GUI library)
- numpy, matplotlib, dequeue, time, PriorityQueue, PIL

## Algorithms

This application provides three different search algorithms for solving the 8-Puzzle:

### 1.Depth-First Search (DFS)
Depth-First Search explores the search space by expanding the deepest unexpanded node first. It may not always find the optimal solution but is memory-efficient.

### 2.Breadth-First Search (BFS)
Breadth-First Search explores the search space level by level. It guarantees finding the optimal solution but may require a lot of memory for large puzzles.

### 3.A* Search
A* Search is an informed search algorithm that uses heuristics to estimate the cost to reach the goal. It combines the cost to reach a node with a heuristic that estimates the remaining cost. This algorithm can find the optimal solution and is used with two heuristic functions:

-Manhattan Distance: This heuristic calculates the sum of the Manhattan distances of each tile from its goal position.
-Euclidean Distance: This heuristic calculates the Euclidean distance of each tile from its goal position.
You can choose your preferred algorithm and heuristic from the GUI.

## Demo
The GUI allows you to:

Enter the initial state of the puzzle.
Select the search algorithm (DFS, BFS, or A*).
For the A* algorithm, you can choose between Manhattan and Euclidean heuristics.
Solve the puzzle.
Step through the solution using "Previous" and "Next" buttons.
View metrics such as cost, nodes expanded, search depth, and running time.



