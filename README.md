# Snake Game

This is a simple Snake game implemented using Python's Turtle Graphics module. The game allows you to control a snake to eat food, grow longer, and avoid collisions with itself and the walls. The game also includes a high score feature and the ability to pause and unpause the game with a mouse click.

## Features

- Control the snake using the arrow keys (Up, Down, Left, Right).
- The snake changes color based on its length:
  - Blue: Length <= 5
  - Dark Blue: Length <= 10
  - Pink: Length > 10
- The game saves the high score in a file (`high_score.txt`) and displays it in the game window.
- Pause and unpause the game by clicking the mouse.

## Installation

1. Ensure you have Python installed. You can download it from [python.org](https://www.python.org/).
2. Download the Turtle Graphics module if you don't already have it. It comes with the standard Python library, but if it's missing, you can install it using pip:
   ```bash
   pip install PythonTurtle
   ```
