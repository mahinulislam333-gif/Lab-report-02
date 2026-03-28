# Lab-report-02
A* Search Algorithm

Name: Mahinul Islam Rabby
Id: 232002011
Section: 232_D7
Course code: CSE316

**OBJECTIVES/AIM**

The objective of this lab is to implement the A* Search algorithm to find the shortest path in a 2D grid from a given start position to a target position.

1.To understand the working principle of the A* Search algorithm.
2.To learn how heuristic functions (Manhattan distance) improve search efficiency.
3.To implement A* to find the shortest path in a grid-based environment.
4.To analyze path cost and ensure optimality of the solution.
5.To track and display the shortest path from start to goal node.

**How to Run**

You are given a 2D grid representing a maze, where each cell is either an empty space (0) or a wall (1). Your task is to implement a Python program that uses the A* search algorithm to determine the shortest path from a given start cell to a specified target cell.

You may move up, down, left, or right to adjacent empty cells, but you cannot pass through walls. Each move has a cost of 1. The algorithm uses Manhattan distance as a heuristic to estimate the cost from the current cell to the target cell.


**Sample Input & Output**
**Case#1**
**Input:**
4 4
0 0 0 0
1 1 0 1
0 0 0 0
0 1 1 0
0 0
3 3

**Output:**
Path found with cost 6 using A*
Shortest Path: [(0,0), (0,1), (0,2), (1,2), (2,2), (2,3), (3,3)]

**Case#2**

**Input:**
3 3
0 1 0
0 1 0
0 1 0
0 0
2 2

**Output:**
Path not found using A*
