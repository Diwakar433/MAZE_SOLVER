# MAZE_SOLVER

# Introduction
The project is about building a ME (Maze Solver) application using Java language.
The ME solver is a 2D grid with a starting and ending point, and the goal is to find the shortest possible path between them.
The grid will have different colored blocks, white blocks represent obstacles, and black blocks are the ones through which the path can go.
The GUI of the application will be built after the business logic.
The project features will be listed and organized systematically to proceed with the development.
The focus will be on the GUI, which should be visually attractive and user-friendly.

# Building GUI
Write the coding for a maze solver project using Java and NetBeans.
A new Java project is created with the name "maze" and a default class "mazeSolverProject.java".
The class is extended with a JFrame to create an output window for the project.
The maze is represented by a 2D array named "grid" that contains 0, 1, and 9 elements.
The boundaries of the grid have 1 elements, 0 elements represent points from which we can traverse, and 9 represents the destination point.
The 1 elements represent obstacles that block the passage of the maze solver.
The maze solver can only move toward directions that don't have obstacles.
The project will use Java Swing to implement the graphical interface.

# Logic
Need for an array traversal algorithm to access and check data stored in the array.
Definition of array traversal as the process of accessing each element stored in the array.
Purpose of array traversal is to check or use data as part of a process.
Three conditions for accessing and checking values in the array: zero (accessible), one (blocker), and nine (destination point).
Requirement to access and check values in the array until the destination point (array value 9) is reached.
Introduction of two techniques for array traversal: Breadth First Search (BFS) and Depth First Search (DFS).
Discussion of DFS as the chosen algorithm for the maze solver project.
Definition of DFS as an algorithm to traverse or search elements in a 2D array or graph.
Purpose of DFS to reach far away from the starting point while accessing elements in the array.
Importance of marking visited elements or nodes during traversal using DFS.
Example of how DFS may need to move in a different direction if blocked and there are two directions left.
