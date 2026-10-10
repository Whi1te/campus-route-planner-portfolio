# Campus Route Planner

**University of Wisconsin–Madison | CS 400: Programming III**

**Project Type:** Collaborative Course Project  
**Technologies:** Java, Dijkstra's Algorithm, Hash Tables, Graph Data Structures, JUnit 5

## Project Overview

Campus Route Planner is a Java-based application developed as part of a collaborative software engineering project in CS 400 at the University of Wisconsin–Madison.

The application uses a directed, weighted graph to represent campus locations and walking routes. It allows users to find the shortest path between two locations, calculate travel times, and identify the furthest reachable destination from a given starting point.

## My Contributions

My responsibilities focused on data structures, shortest-path algorithms, backend development, and testing.

### 1. Dijkstra's Shortest-Path Algorithm
- Implemented Dijkstra's algorithm using Java's `PriorityQueue`.
- Developed shortest-path calculations for directed, weighted graphs.
- Implemented path reconstruction and total path cost calculations.

### 2. Custom Hash Table
- Implemented a generic hash table using separate chaining with linked lists.
- Supported insertion, retrieval, removal, and key lookup operations.
- Implemented automatic resizing and rehashing when the load factor reached 0.8.

### 3. Backend Development
- Implemented parsing of campus map data stored in DOT files.
- Developed methods for retrieving locations, shortest paths, and travel times.
- Implemented functionality to identify the furthest reachable destination.

### 4. Testing and Integration
- Developed JUnit tests for backend functionality.
- Created integration tests connecting graph algorithms, backend logic, and frontend functionality.
- Tested graph loading, path retrieval, and invalid-location handling.

## Project Architecture

The application was developed collaboratively using modular components:

- **Graph and Data Structures:** Directed, weighted graph representation and a custom hash table.
- **Shortest-Path Computation:** Dijkstra's algorithm for route calculations.
- **Backend:** Graph data loading and route-related operations.
- **Frontend:** HTML-based user interaction.
- **Web Application:** Integration of frontend and backend components.

My individual contributions included `DijkstraGraph.java`, `HashtableMap.java`, `MapADT.java`, `Backend.java`, and `BackendTests.java`.

## Source Code Availability

The source code is maintained in a private University of Wisconsin–Madison GitLab repository.

To respect course academic integrity and prevent unauthorized distribution of assignment solutions, the source code is not publicly available.

This repository serves as a portfolio description of the project and my individual contributions.
