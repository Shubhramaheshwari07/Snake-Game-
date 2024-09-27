Project Overview:
This project is a simple implementation of the classic Snake game using Python and the Pygame library. The game allows the player to control a snake that grows in length as it eats food pellets, while avoiding collision with itself and the game boundaries.

Game Features:
-A snake that grows in length as it eats food pellets.
-The snake can move in four directions (up, down, left, right).
-The game checks for collision with itself and the game boundaries.
-The game displays the player's score.
-The game can be restarted after game over.

How to Play:
-Run the game by executing the Python script.
-The game window will appear with a snake and a food pellet.
-Use the arrow keys to move the snake.
-Eat the food pellets to grow the snake.
-Avoid collision with itself and the game boundaries.
-The game will display the player's score.
-If the snake collides with itself or the game boundaries, the game will end.
-Press Q to quit or C to play again.

Code Explanation:
The code is organized into several functions:

gameLoop()-
This is the main game loop function that runs the game. It initializes the game state, handles user input, and updates the game state.

your_score(score)-
This function displays the player's score on the game window.

our_snake(snake_block, snake_list)-
This function draws the snake on the game window.

message(msg, color)
This function displays a message on the game window, such as the game-over message.

Game State Variables-
The game state is maintained using several variables:

x and y: the snake's current position-
x_change and y_change: the snake's movement direction.
snake_list: a list of the snake's body parts.
length_of_snake: the snake's current length.
food_x and food_y: the food pellet's position.

Game Logic:
The game logic is implemented using the following steps:

Initialize the game state:
-Handle user input (arrow keys).
-Update the snake's position and direction.
-Check for collision with itself and the game boundaries.
-Check if the snake eats the food pellet.
-Update the game state and display the score.
-Repeat steps 2-6 until the game ends.

Code Structure:
The code is organized into a single Python file, snake_game.py. The file contains several functions for displaying the game elements, handling user input, and updating the game state.

Dependencies:
-Python 3.x .
-Pygame library (install with pip install pygame).
