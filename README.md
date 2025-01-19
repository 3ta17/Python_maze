# Maze Game

A fun and interactive maze game developed in Python using the `tkinter` library. Players navigate through a series of mazes, painting all the tiles to progress through stages.

## Features

- **Multiple Levels**: Five unique stages, each with increasing difficulty.
- **Interactive Gameplay**: Control the player using keyboard keys to navigate the maze.
- **Restart Option**: Restart the current stage if needed.
- **Dynamic Feedback**: Displays "Stage Clear" or "All Stages Clear" upon completion.

## How to Play

1. **Objective**:
   - Move the pen across the maze, painting all unpainted tiles.
   - Avoid hitting the walls (represented by tiles labeled `9`).

2. **Controls**:
   - Use the **Arrow Keys** to move the pen:
     - **Up**: Move upward.
     - **Down**: Move downward.
     - **Left**: Move left.
     - **Right**: Move right.
   - Press **Shift** or **G** to restart the stage.

3. **Win Condition**:
   - Complete all 5 stages by painting every tile in each maze.

## Requirements

To run the game, ensure you have the following:
- Python 3.x installed.
- The `tkinter` library (pre-installed with Python).
- The image files `pen.png` (player icon) and `wall.png` (wall icon) located in the same directory as the script.

## Setup and Execution

1. Clone or download the repository.
2. Place the `pen.png` and `wall.png` files in the same folder as `maze_game.py`.
3. Run the script:
   ```bash
   python maze_game.py
