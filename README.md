# Route Optimization and Sketch-to-Route System

## Project Overview

This project is a route optimization system that combines graph theory algorithms with an interactive map-based interface. The system is implemented using a real geographic map of France, allowing routes to be computed and visualized on an actual national road network.

An innovative sketch-to-route feature is included, enabling users to draw a preferred route directly on the map of France and have the system compute the closest valid and optimized path that follows the drawn trajectory.

The project was developed in the context of operations research and algorithmic problem solving, with a strong focus on shortest path algorithms and user-centered route definition.

---

## Main Objectives

* Model the French road network as a weighted graph
* Compute optimal routes on a real map of France
* Implement shortest path algorithms for routing problems
* Enable intuitive route definition using freehand sketches
* Convert sketched routes into valid paths on the French map graph

---

## Key Features

* Interactive map of France for route visualization
* Graph representation of cities and roads in France
* Shortest path computation between French cities or nodes
* Sketch-to-route functionality on the France map
* Automatic matching of sketched paths to nearby French road nodes
* Visualization of final optimized routes over the map of France

---

## Sketch-to-Route Feature

The sketch-to-route feature allows users to draw a route directly on the map of France instead of manually selecting start and end locations.

Workflow:

1. The user sketches a route on the France map using the mouse.
2. The system captures the geographic coordinates of the sketch.
3. The drawn path is simplified and filtered.
4. Nearby nodes from the French road network are selected.
5. A valid path is reconstructed using shortest path algorithms constrained by the sketch.
6. The optimized route is rendered on the map of France.

This approach improves usability by allowing users to express route preferences visually.

---

## Algorithms Used

* Dijkstra algorithm for shortest paths on the France road graph
* Bellman-Ford algorithm for weighted routing
* Breadth-First Search (BFS) for traversal
* Depth-First Search (DFS) for traversal
* Spatial filtering to align sketches with French road nodes

---

## Technologies and Tools

* Python for backend logic and routing algorithms
* Flask for server-side processing
* JavaScript for client-side interaction
* Leaflet for displaying the interactive map of France
* HTML and CSS for the user interface
* Operations research and graph theory methods

---

## Project Structure

```
OR Project/
│
├── backend/
│   ├── algorithms/
│   ├── graph/
│   └── app.py
├── frontend/
│   ├── js/
│   ├── css/
│   └── index.html
├── data/
│   └── france_road_network
├── utils/
├── docs/
└── README.md
```

Folder names may vary depending on the implementation.

---

## How to Run the Project

1. Extract the project directory.
2. Install the required Python dependencies.
3. Start the backend server.
4. Open the frontend interface in a web browser.
5. Load the map of France.
6. Draw a route or select locations and compute the optimized path.

---

## Use Cases

* Route planning within France
* Delivery and logistics optimization on French roads
* Urban and intercity mobility analysis
* Educational demonstrations of graph algorithms using real maps
* User-driven routing through sketch-based input

---

## Limitations

* Routing accuracy depends on the resolution of the France road network data
* Sketch interpretation is sensitive to drawing precision
* Large-scale networks may affect performance

---

## Future Improvements

* Higher-resolution French road data
* Real-time traffic integration
* Improved sketch smoothing and constraint handling
* Mobile and touch interface support

---

## Author

This project was developed for academic purposes, combining operations research, graph theory, and interactive routing on a real map of France.
