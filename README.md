# # Tic-Tac-Toe Game in Java

## Overview
This is a simple command-line based implementation of the classic Tic-Tac-Toe game written in Java. The game is designed for two players, where they take turns to place their marks ('X' and 'O') on a 3x3 grid. The objective is to get three of their marks in a row—horizontally, vertically, or diagonally—before their opponent does.

## Features
- Two-player mode (Player 1 uses 'X', and Player 2 uses 'O').
- Input validation to ensure that players choose valid moves (only available spots can be selected).
- Win detection for all possible winning combinations (rows, columns, diagonals).
- Displays the board after every move.
- Option to restart the game after a win or a draw.

## Game Rules
1. The game is played on a 3x3 grid.
2. Players take turns to place their mark ('X' or 'O') in an empty spot on the grid.
3. The first player to place three marks in a row (horizontally, vertically, or diagonally) wins the game.
4. If all spots on the grid are filled and no player has won, the game ends in a draw.
5. Players can choose to replay the game after it ends.

## How to Play
1. Run the Java program.
2. The game will display the current state of the 3x3 board, and it will prompt Player 1 (X) to enter a position (1-9) corresponding to the desired location on the grid.
3. Player 2 (O) will take their turn next, following the same process.
4. The game checks after each turn whether there is a winner or if the game has ended in a draw.
5. If a player wins or the game ends in a draw, you will be prompted to either restart the game or exit.

## Installation & Execution
### Prerequisites
- Java Development Kit (JDK) installed on your system.

### Steps
1. Clone the repository or download the source code.
2. Open the project in your preferred Java IDE or compile it via the terminal.
3. To compile via terminal:
   ```bash
   javac TicTacToe.java
   ```
4. Run the compiled class:
   ```bash
   java TicTacToe
   ```

## File Structure
- `TicTacToe.java`: Contains the main logic for the game, including input handling, board display, win checking, and the game loop.

## Future Improvements
- Add a graphical user interface (GUI) for a more interactive experience.
- Implement a single-player mode with an AI opponent.
- Add difficulty levels for the AI.

## License
This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it.

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue to discuss any changes.

## Contact
For any questions or feedback, please feel free to reach out.

---

Enjoy playing Tic-Tac-Toe!
