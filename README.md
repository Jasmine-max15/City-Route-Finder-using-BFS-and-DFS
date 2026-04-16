City Route Finder using BFS and DFS

This project implements graph traversal algorithms (BFS and DFS) to find a path between cities and visualize the route on a map using Python.

The program allows users to choose a starting city and destination city, select the algorithm (BFS or DFS), and view the resulting path on an interactive map generated with Folium.

Features
Implementation of Breadth-First Search (BFS)
Implementation of Depth-First Search (DFS)
City route path generation
Interactive map visualization
Simple command line interface
Automatic opening of the generated route map
Algorithms Used
Breadth-First Search (BFS)

BFS explores nodes level by level and finds the shortest path in terms of number of edges.

Depth-First Search (DFS)

DFS explores nodes by going as deep as possible before backtracking.

Both algorithms operate on a graph structure where cities are nodes and roads are edges.

Technologies Used
Python
Folium (for map visualization)
Collections (deque) for BFS queue
OS & Webbrowser modules for file handling
Project Structure
City-Route-Finder
│
├── route_finder.py
├── path_map.html
└── README.md
Installation

Clone the repository:

git clone https://github.com/yourusername/city-route-finder.git

Move to the project directory:

cd city-route-finder

Install required library:

pip install folium
How to Run

Run the Python file:

python route_finder.py

Program steps:

Displays available cities
Enter starting city
Enter destination city
Choose algorithm (BFS or DFS)
Program prints the path
Map automatically opens in browser

Example:

Available Cities:
Delhi
Agra
Jaipur
Chandigarh
Nahan

Enter Starting City: Delhi
Enter Destination City: Nahan

Choose Algorithm
1. BFS
2. DFS

Output:

Path: Delhi -> Chandigarh -> Nahan

A map showing the path will open automatically.

Example Map Output

The program generates a map showing:

City locations as markers
Route between cities
Highlighted path between start and destination

The map is saved as:

path_map.html
Learning Outcomes

This project demonstrates:

Graph data structures
Graph traversal algorithms
BFS and DFS implementation
Practical use of algorithms in route finding
Data visualization using maps
Future Improvements

Possible enhancements:

Add more cities and routes
Implement Dijkstra Algorithm
Implement A* Pathfinding
Add GUI interface
Use real-world map APIs
