# Maze Game

This is a simple maze game created as an extracurricular project in 2021 for a Python course. The game uses the `turtle` graphics module and includes methods from TokyoEdtech. The objective of the game is to navigate the player through the maze, collect treasures, avoid enemies, and reach the finish line with enough gold.

## Features
- **Player Movement**: Move the player up, down, left, and right using keyboard arrow keys.
- **Treasures**: Collect coins to increase the player's gold.
- **Enemies**: Avoid enemies that move randomly within the maze.
- **Finish Line**: Reach the finish line with sufficient gold to win the game.

## How to Play
1. **Start the Game**: Run the script to open the game window.
2. **Move the Player**: Use the arrow keys to move the player around the maze.
3. **Collect Treasures**: Navigate to the coins to collect them and increase your gold.
4. **Avoid Enemies**: Stay away from enemies to avoid losing the game.
5. **Reach the Finish Line**: Get to the finish line with enough gold to win the game.

## Code Overview

### Importing Modules
```python
import turtle
import math
import random
```

### Game Setup
- **Window Setup**: Initialize the game window with `turtle.Screen()`.
- **Register Shapes**: Register custom shapes for the player, enemies, treasures, and other game elements.
- **Pen Class**: Draw the maze walls.
- **Player Class**: Control the player character, handle movement, and check for collisions.
- **Treasure Class**: Define the treasure items that the player can collect.
- **Finish Class**: Define the finish line the player must reach to win the game.
- **Enemy Class**: Define enemy characters that move randomly and pose a threat to the player.

### Maze Level Design
The maze is designed using a list of strings, where each character represents a different element in the game (e.g., walls, player start position, treasures, enemies, finish line).

### Game Loop
The main game loop handles:
- Updating the screen.
- Checking for collisions between the player and treasures, enemies, or the finish line.
- Moving enemies and updating their positions.

## Controls
- **Up Arrow**: Move the player up.
- **Down Arrow**: Move the player down.
- **Left Arrow**: Move the player left.
- **Right Arrow**: Move the player right.

## Running the Game
To run the game, simply execute the script. Ensure you have the `turtle` module installed and the custom shape files (`.gif` images) in the same directory as the script.

## Example Usage
```bash
python maze_game.py
```

Enjoy navigating through the maze, collecting treasures, avoiding enemies, and reaching the finish line!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
