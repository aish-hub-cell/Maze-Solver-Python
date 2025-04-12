# Maze Solver

A Python-based maze solver that solves a maze using a search algorithm and outputs the solution both in text format and as a visual image. The program reads a maze from a text file (`maze.txt`), finds the path from the start point ('A') to the goal ('B'), and displays the solution on the console and in an image format.

## Features:
- Solves mazes using a **Depth-First Search** algorithm (implemented with a stack frontier).
- Outputs the maze with the solution marked.
- Supports **visualization** of the maze and solution using an image.
- Can show the **explored** states in the maze during the solution process.

## How to Use:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/Maze-Solver-Python.git
    cd Maze-Solver-Python
    ```

2. **Install dependencies:**
    This project uses `Pillow` for image generation, so you'll need to install it using pip:
    ```bash
    pip install pillow
    ```

3. **Prepare your maze text file:**
    Create a file called `maze.txt` in the same directory as the `maze.py` file. The maze should be represented by characters:
    - `A` = Start point
    - `B` = Goal point
    - `█` = Wall
    - Space (` `) = Empty cell

    Example maze:
    ```
    █████████
    A       █
    █ █ █ █ █
    █     █ █
    █ █ █   B
    █████████
    ```

4. **Run the program:**
    ```bash
    python maze.py maze.txt
    ```

    - This will print the solved maze in the terminal and save an image (`maze.png`) showing the solution.

## Maze File Format:

The maze file must be a plain text file with the following rules:
- Exactly one start point (`A`).
- Exactly one goal point (`B`).
- Walls are represented by `█`.
- Empty spaces are represented by a space (` `).


## Features to be added:
- Support for different solving algorithms (e.g., Breadth-First Search).
- More advanced visualization features (e.g., animated solving steps).


