# Simple Snake Game in C++

## Description

This is a simple implementation of the classic Snake game in C++. The game is played on a console, where the player controls the snake to eat food that appears at random positions. Each time the snake eats food, it grows in length. The game ends if the snake runs into the wall or itself.

## Features

- Control the snake using the arrow keys.
- Randomly appearing food.
- Score tracking.
- Game over detection when the snake hits the wall or itself.

## Requirements

- C++ Compiler (e.g., g++, clang++)
- Compatible with Windows, Linux, and macOS

## How to Compile and Run

### Windows

1. Open Command Prompt.
2. Navigate to the directory where the source code is located.
3. Compile the game using the following command:
    ```sh
    g++ -o snake_game snakemain.cpp
    ```
4. Run the game using the following command:
    ```sh
    snake_game.exe
    ```

### Linux / macOS

1. Open Terminal.
2. Navigate to the directory where the source code is located.
3. Compile the game using the following command:
    ```sh
    g++ -o snake_game snakemain.cpp
    ```
4. Run the game using the following command:
    ```sh
    ./snakemain.cpp
    ```

## Controls

- Use the arrow keys to control the direction of the snake:
  - Up arrow: Move up ('w')
  - Down arrow: Move down ('s')
  - Left arrow: Move left ('a')
  - Right arrow: Move right ('d')

## Code Overview

The main components of the game include:

- **Main Function**: Sets up the game loop and handles user input.
- **Game Initialization**: Initializes the game state, including the snake's starting position and the first piece of food.
- **Game Loop**: Continuously updates the game state, renders the game board, and processes user input until the game is over.
- **Collision Detection**: Checks for collisions with the walls and the snake's own body.
- **Food Generation**: Randomly places food on the game board.
- **Score Tracking**: Keeps track of the player's score, which increases each time the snake eats food.

## Example Code Snippet

Here is a snippet of the game loop:

```cpp
    while (!gameOver) {
        if (dir == LEFT || dir == RIGHT)
        {
        Sleep(5);
        }

        Sleep(100);

        if (dir == UP || dir == DOWN)
        {
        Sleep(60);
        }
      draw();
      input();
      logic();
    

}
