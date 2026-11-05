# GPS Navigation with Road Weights

About the Project: 
GPS Navigation with Road Weights is an interactive web application that finds routes between different locations using pathfinding algorithms,
The project represents a simplified city road network as a weighted graph, where intersections are 
represented by nodes and roads are represented by edges with distance and speed information,
Users can select a starting point, a destination, and a search algorithm to find and visualize a route

1)Technologies Used
- Python
- Shiny for Python
- Plotly
- Pandas
- Heapq
- Collections (Deque)
- Math

2) Features
- Interactive Navigation: Select starting and destination intersections from dropdown menus
- A* Algorithm: Find routes using actual distance and estimated remaining distance
- BFS Algorithm: Explore the graph using Breadth-First Search
- Interactive Map:Visualize the road network, explored nodes, and the final route
- Route Statistics: Display total distance, estimated travel time, and number of explored nodes
- Algorithm Comparison: Compare A* and BFS based on distance and number of explored nodes
- Reset Function: Clear the current search results and start again

3) Algorithms Used
a) A* Search
Uses:
- G-score: Actual distance from the starting node.
- Heuristic: Euclidean distance estimating the remaining distance.
- F-score: Sum of the G-score and heuristic.
- 
b) Breadth-First Search (BFS)
Explores nodes level by level using a FIFO queue.

4) Road Network
The project includes:
- 25 intersections (nodes).
- Bidirectional roads (edges).
- Road distances in kilometers.
- Speed limits in km/h.

The road network is a simplified representation designed for demonstrating graph search algorithms.

4) Visualizations
The application provides:
- A map highlighting the selected route.
- Explored nodes visualization.
- A comparison table between A* and BFS.
- A pie chart showing search effort distribution.
- A bar chart comparing the number of explored nodes.

5)How to Run

1. Clone or download this repository.
2. Install the required libraries:
  pip install shiny plotly pandas
3. Run the Python application:
  shiny run --reload app.py
4. Open the local URL provided in the terminal.

finally: Project Goal

To understand and apply graph representation and pathfinding algorithms through an interactive navigation application, 
while comparing their search efficiency and visualizing their behavior.

A team worked project.
