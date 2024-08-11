# Tic-Tac-Toe Game in Python

## Project Overview

This project is a simple command-line implementation of the classic Tic-Tac-Toe game. It allows two players to take turns placing their markers ('X' or 'O') on a 3x3 grid. The game checks for a winner after each move and declares the winner when a player successfully aligns three of their markers horizontally, vertically, or diagonally.

## Features

- **Two-Player Mode**: Allows two players to play against each other.
- **Grid Display**: The game board is displayed after each move, showing the current state of the game.
- **Win Detection**: The game checks for winning conditions after every move and announces the winner if there's one.
- **Simple Input**: Players can input their move by entering a number corresponding to the grid position.

## How to Play

1. **Clone the Repository**:
   ```bash
   git clone <repository-link>
   cd <repository-folder>
   ```

2. **Run the Game**:
   - Execute the Python script in your terminal:
     ```bash
     python tic_tac_toe.py
     ```
   - The game will display a welcome message and the initial board.

3. **Gameplay**:
   - Players take turns to enter their move.
   - The positions on the grid are numbered 0-8 as shown below:

     ```
     0 | 1 | 2
     __|___|___
     3 | 4 | 5
     __|___|___
     6 | 7 | 8
     ```

   - Player 1 (X) and Player 2 (O) take turns entering the position where they want to place their marker.
   - After each move, the board is updated and displayed.

4. **Winning the Game**:
   - The game checks for a winner after each move.
   - If a player aligns three markers in a row, column, or diagonal, the game announces the winner and ends.
   - If the board is full and no player has won, the game ends in a draw.

## Code Structure

- **sum(a, b, c)**: A helper function to sum three numbers.
- **printBoard(xState, zState)**: A function that prints the current state of the game board.
- **checkWin(xState, zState)**: A function that checks if any player has won the game based on the current state.
- **Main Game Loop**: The core loop that alternates turns between players, updates the game board, and checks for a winner.

## Dependencies

- Python 3.x

No external libraries are required for this project.

## Customization

- You can extend the game by adding features like score tracking, replay options, or AI opponents.
- Modify the game board display or input method to make it more user-friendly or visually appealing.

## License

This project is open-source and available under the [MIT License](LICENSE).
