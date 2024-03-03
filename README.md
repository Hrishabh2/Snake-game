# Snake Game
**This is a simple console-based Snake Game implemented in C++. The game utilizes the iostream, conio.h, and windows.h libraries for input/output and basic console manipulation.**

# Overview
**The Snake Game consists of a snake (represented by the character 'O') that moves around a 2D grid. The player controls the snake's direction using the keyboard arrows ('a' for left, 'd' for right, 'w' for up, and 's' for down). The goal is to eat the fruit ('F'), which appears randomly on the grid, and as the snake consumes the fruit, its length increases. The game ends if the snake collides with the boundaries or with itself.**

# How to Run
**To run the game, compile the code and execute the binary. Make sure your development environment supports the conio.h library for keyboard input and the windows.h library for console manipulation.**

# Game Controls
Left Arrow ('a'): Move the snake to the left.

Right Arrow ('d'): Move the snake to the right.

Up Arrow ('w'): Move the snake upwards.

Down Arrow ('s'): Move the snake downwards.

'x': Exit the game.

# Game Display
**The game is displayed in a console window, with the snake represented by 'O', the fruit by 'F', and the tail by 'o'. The score is displayed at the bottom of the screen**.

# Game Logic
**The game logic includes functions for setting up the initial game state, drawing the game grid, handling player input, and updating the game state based on the player's actions. The snake wraps around the screen when reaching the boundaries.**

# Notes
The code uses a basic pseudorandom number generator to position the fruit on the grid.
The game features a simple sleep function to control the speed of the snake.
Feel free to explore and modify the code to enhance the game or adapt it to different platforms. Have fun playing Snake!
