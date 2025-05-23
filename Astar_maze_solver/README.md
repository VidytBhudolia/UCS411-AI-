# Enhanced A* Maze Solver

A web-based application that generates and solves mazes using an enhanced A* algorithm with multiple heuristic functions.

## Features

- **Maze Generation**: Create random mazes of various sizes
- **Multiple Heuristics**: Solve mazes using different heuristic approaches:
  - Manhattan Distance (traditional)
  - KNN-based heuristic (machine learning enhanced)
  - Decision Tree heuristic (machine learning enhanced)
- **Performance Comparison**: Compare the execution time of different heuristics
- **Visual Representation**: See the solution path for each heuristic
- **Interactive Web Interface**: User-friendly interface for maze generation and solution visualization

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/astar_maze_solver.git
   cd astar_maze_solver
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Start the web application:
   ```
   python app.py
   ```

2. Open your web browser and navigate to:
   ```
   http://localhost:5000
   ```

3. Using the interface:
   - Adjust the maze size using the slider
   - Click "Generate Maze" to create a new maze
   - Click "Solve Maze" to solve the maze using multiple heuristics
   - View the comparison results and solution paths

## Project Structure

- `/static` - Frontend assets (CSS, JavaScript)
- `/templates` - HTML templates
- `/app.py` - Flask application and API endpoints
- `/maze_generator.py` - Maze generation algorithms
- `/maze_solver.py` - A* algorithm implementation with multiple heuristics

## Technical Details

- **Frontend**: HTML, CSS, JavaScript, Chart.js
- **Backend**: Python, Flask
- **Algorithms**: A* pathfinding with enhanced heuristics
- **Machine Learning**: KNN and Decision Tree approaches for heuristic estimation

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Further Information

For more detailed information about the algorithms and implementation, please refer to the [synopsis document](./synopsis.md).
