# Snake Game

This is a simple implementation of the classic Snake game using Python's Tkinter library, based on a tutorial from a YouTube video.

## How to Play

- Use the arrow keys to control the direction of the snake:
  - Up: Move up
  - Down: Move down
  - Left: Move left
  - Right: Move right
- The goal is to eat the red food to grow the snake and increase your score.
- The game is over if the snake runs into the walls or itself.

## Installation

1. Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).
2. Tkinter should be included with Python, but if it's not, you can install it using the following command:
   ```bash
   pip install tk
   ```
3. Download or clone this repository.

## Running the Game

Navigate to the directory where the game script is located and run the following command:
```bash
python Snake.py
```

## Code Overview

- `Tile` class: Represents a single tile in the game, used for both the snake and the food.
- The game window is created using Tkinter and centered on the screen.
- The `change_direction` function handles the direction change based on the user's key presses.
- The `move` function updates the position of the snake and checks for collisions.
- The `draw` function draws the snake and the food on the canvas and handles the game over scenario.

## Future Improvements

- Add levels with increasing difficulty.
- Add a high score feature.
- Implement different types of food with different effects.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This game is inspired by the classic Snake game.
