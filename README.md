# Pathfinding Visualization

A web-based pathfinding visualization tool that demonstrates various pathfinding algorithms and heuristics, including **Directional Heuristic**, **Angular Heuristic**, **Octile Heuristic**, and **Dijkstra's Algorithm**. Users can dynamically generate obstacles, visualize the paths, and compare the performance of these algorithms.

---

## Features

- **Interactive Grid**: A 20x20 grid where you can observe how the pathfinding algorithms work.
- **Pathfinding Algorithms**:
  - Directional Heuristic
  - Angular Heuristic
  - Octile Heuristic
  - Dijkstra's Algorithm
- **Dynamic Obstacles**: Randomly generate obstacles to challenge the algorithms.
- **Visualization**: Visual representation of start point, goal point, obstacles, and the computed path.

---

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling for the grid and controls.
- **JavaScript**: Logic for pathfinding algorithms and visualization.

---

## How It Works

1. The grid is initially empty with a **Start Point (Green)** at the top-left and a **Goal Point (Red)** at the bottom-right.
2. **Obstacles (Black)** can be generated randomly by clicking the "Generate Obstacles" button.
3. Use the available buttons to run different algorithms:
   - **Directional Heuristic**: Prioritizes moving toward a pre-defined goal direction.
   - **Angular Heuristic**: Considers angular deviation from the straight line toward the goal.
   - **Octile Heuristic**: Approximates distances for diagonal moves in grid-based paths.
   - **Dijkstra's Algorithm**: Finds the shortest path from the start to the goal, avoiding obstacles.
4. The **Path (Blue)** is visualized on the grid after an algorithm runs.

---

## Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, etc.).

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Ayan-Dutta-ai/MLAI_LAB_18_08.git

### Project Structure

|-- index.html       # Main HTML file
|-- styles.css       # Styling for the grid and UI
|-- script.js        # Core JavaScript logic for algorithms and visualization
|-- README.md        # Documentation

## Algorithms Explained

### Directional Heuristic

Prioritizes movement toward a specific goal direction (e.g., bottom-right). Adjusts dynamically based on the start and goal positions.

### Octile Heuristic

Estimates the distance to the goal considering both straight and diagonal moves on the grid.


---

## Future Enhancements

- Add A* algorithm with customizable heuristics.
- Allow users to draw custom obstacles on the grid.
- Improve visualization with animations for algorithm steps.
- Add performance metrics for each algorithm.

---

## Contributing

Contributions are welcome! Feel free to fork the project, make improvements, and submit a pull request.
