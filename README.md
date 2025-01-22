# Tic-Tac-Toe Game

## Overview
This project is a simple command-line implementation of the classic Tic-Tac-Toe game, where two players take turns placing their symbols ('X' and 'O') on a 3x3 grid. The game determines the winner or declares a tie based on the standard rules of Tic-Tac-Toe.

## Features
- Two-player gameplay.
- Validates user input and provides error messages for invalid moves.
- Automatically checks for a winner or a tie after each turn.
- Displays the game board after every move.

## How to Play
1. The game starts with Player X.
2. Players take turns entering a position (1-9) to place their symbol on the board.
3. The positions on the board are numbered as follows:

   ```
    1 | 2 | 3
   ---------
    4 | 5 | 6
   ---------
    7 | 8 | 9
   ```

4. The game checks for a winner after every move. A player wins if they align three of their symbols horizontally, vertically, or diagonally.
5. If all positions are filled and there is no winner, the game ends in a tie.

## Code Overview
- **board**: A list representing the 3x3 grid, initialized with empty spaces.
- **display_board()**: Displays the current state of the board.
- **check_winner(player)**: Checks if the specified player has won.
- **is_board_full()**: Determines if the board is full.
- **play_game()**: The main function to control the game flow.

## Example Gameplay
```
   |   |  
---------
   |   |  
---------
   |   |  
Player X's turn.
Enter position (1-9): 5

   |   |  
---------
   | X |  
---------
   |   |  
Player O's turn.
Enter position (1-9): 1
```
