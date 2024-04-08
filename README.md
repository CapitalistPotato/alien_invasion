Alien Invasion on Pygame

Introduction
This is a simple implementation of the classic arcade game "Alien Invasion" using the Pygame library in Python. The game involves controlling a spaceship to shoot down a fleet of aliens while avoiding their projectiles.

 Files
1. alien.py: Defines the Alien class which represents the enemy aliens in the game.
2. bullet.py: Implements the Bullet class responsible for managing bullets fired from the ship.
3. button.py: Contains the Button class to create interactive buttons for the game interface.
4. game_functions.py: Contains various functions for handling game events, updating game elements, and managing collisions.
5. game_stats.py: Defines the GameStats class to keep track of game statistics such as score, level, and number of ships.
6. scoreboard.py: Implements the Scoreboard class to display game statistics on the screen.
7. settings.py: Contains the Settings class to store all game settings and configurations.
8. ship.py: Defines the Ship class representing the player-controlled spaceship.

How to Run
To run the game, make sure you have Python installed on your system along with the Pygame library. Then, execute the `run_game()` function in the main file (`alien_invasion.py` or any other appropriate name). This will initialize the game window and start the game loop.

Gameplay
- Use the arrow keys to move the spaceship left and right.
- Press the up arrow key to fire bullets at the aliens.
- The objective is to shoot down all the aliens before they reach the bottom of the screen.
- Avoid colliding with the aliens or their projectiles.
- The game ends when the player loses all their ships.

Features
- Scoreboard: Displays the player's current score, highest score, and current level.
- Game Over: The game ends when the player loses all their ships, and the final score is displayed.
- Play Button: Allows the player to start the game or restart after game over.
- Dynamic Difficulty: The game progressively increases in difficulty as the player advances through levels. (WIP, not functioning)
