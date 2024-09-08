# Overview

This project visualizes the process of using Dijkstra's algorithm to find the shortest path in a self-generated maze.

## Project Structure

### 1. Vertices and Grid Build Definition

- **File Name**: `vertex.py`
- **Description**:
  - Defines the key element of the grid - a vertex object.
  - Lays the foundational structure upon which the maze will be generated, and Dijkstra's algorithm will be run.

### 2. Maze Generation

- **File Name**: `maze_generator.py`
- **Description**:
  - Generates a random maze on the grid using the structure defined in `vertex.py`.
  - A path is guaranteed to exist.

### 3. Dijkstra's Algorithm Implementation

- **File Name**: `dijkstra.py`
- **Description**:
  - Implements Dijkstra's algorithm to find the shortest path from start to finish.

### 4. Visualization of Dijkstra's algorithm

- **File Name**: `visualization.py`
- **Description**:
  - Builds a GUI using PyGame library to visualize the maze and the path-finding process.

### 5. Driver

- **File Name**: `main.py`
- **Description**:
  - Runs the entire program.
  - Connects each part of the program, integrating the grid build, maze generation, and Dijkstra's algorithm to create and solve the maze.
