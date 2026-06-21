GPS Navigation System

Overview
GPS Navigation System is a C++ application that simulates route planning and navigation between different locations. The project uses **Dijkstra's Algorithm** to calculate the shortest path and minimum distance between a source and destination within a road network. Users can create a graph of locations connected by roads, specify a starting point and destination, and obtain the optimal route along with the total travel distance. The project demonstrates the practical implementation of graph theory and shortest path algorithms used in real-world navigation systems such as Google Maps and GPS devices.

Features
- Shortest path calculation using Dijkstra's Algorithm
- Distance optimization between locations
- Graph-based road network representation
- Source and destination selection
- Path reconstruction and display
- Efficient route finding using Priority Queue
- Undirected weighted graph implementation

Technologies Used
- C++
- STL (Standard Template Library)
- Priority Queue
- Vectors
- Graph Data Structures
- Dijkstra's Shortest Path Algorithm

How It Works
1. Enter the number of locations (vertices).
2. Enter the number of roads (edges).
3. Input road connections with distances.
4. Select a source location.
5. Select a destination location.
6. The system calculates:
   - Shortest distance
   - Optimal route/path

Example
Input
Number of Locations: 5
Number of Roads: 6
Road Connections:
0 1 4
0 2 2
1 2 1
1 3 5
2 3 8
3 4 3
Source: 0
Destination: 4

Output
Shortest Distance: 11
Shortest Path:
0 → 2 → 1 → 3 → 4

Concepts Implemented
- Graph Theory
- Dijkstra's Algorithm
- Priority Queue
- Path Reconstruction
- Dynamic Data Structures
- Algorithm Optimization
