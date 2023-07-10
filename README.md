# 2048-Console-Game


## Description:
This project aims to create an interactive console version of the popular game 2048. The game involves sliding numbered tiles on a grid and merging them to reach the target number of 2048. It is a console-based implementation of the popular game 2048. The game involves sliding numbered tiles on a 4x4 grid and merging them to reach the target number of 2048. The implementation provides a text-based interface where players can input moves and see the updated board configuration after each move.

## Features

- Simple and intuitive console interface.
- Supports four directions for moving the tiles: left, right, up, and down.
- Tiles with the same value merge into one tile when they collide.
- Random generation of new tiles with values of 2 or 4 after each move.
- The game ends when the player reaches the target number of 2048 or there are no valid moves left.

## Getting Started

1. Clone the project repository to your local machine.
2. Compile and run the source code in your preferred C++ environment.
3. Follow the instructions provided in the console to input the number of moves and the direction for each move.
4. The game will display the current board configuration after each move.
5. If a move is invalid, an appropriate message will be displayed.
6. The game will end with a message indicating whether the player wins or loses.

## Requirements

- C++ compiler

## Usage

1. Run the compiled program.
2. Enter the number of moves you want to make.
3. For each move, enter a number corresponding to the direction (1: left, 2: down, 3: right, 4: up).
4. The game will display the current board configuration after each move.
5. If a move is invalid, it will display "Invalid Move."
6. If the game is over and the player loses, it will display "Game Over, You Lose."
7. If the player reaches the target number of 2048 and wins, it will display "Game Over, You Win."

## Example

```
$ ./2048-game
4
1
2
3
4

Initial Configuration:
-   -   2   -
-   -   -   -
-   -   2   -
-   -   -   -

After Move:
-   -   2   -
-   -   -   -
-   -   2   -
-   -   -   -

After Move:
-   -   -   -
-   -   -   -
-   -   -   2
-   -   -   2

After Move:
-   -   -   2
-   -   -   2
-   -   -   -
-   -   -   -

After Move:
-   -   -   2
-   -   -   2
-   -   -   2
-   -   -   -

Game Over, You Lose.
```
## How to Play:
1. Run the game on the console.
2. Enter the number of moves you want to make.
3. For each move, enter a number (1, 2, 3, or 4) corresponding to the direction (left, down, right, or up) you want to move the tiles.
4. The game will display the current board configuration after each move.
5. If a move is invalid, it will display "Invalid Move."
6. If the game is over and the player loses, it will display "Game Over, You Lose."
7. If the player reaches the target number of 2048 and wins, it will display "Game Over, You Win."

Have fun playing 2048 on the console!

## Contributions

Contributions to the project are welcome. Feel free to fork the repository, make improvements, and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
