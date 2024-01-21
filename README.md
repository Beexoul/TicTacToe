# Tic-Tac-Toe Game

This is a simple implementation of the classic Tic-Tac-Toe game using Python and Tkinter.

++
![Watch a demo ](hereisademo.gif)
++
## How to Play

1. Run the game by executing the `main.py` script.
2. The game window will appear, presenting a 3x3 grid for Tic-Tac-Toe.
3. Players take turns clicking on empty cells to place their marks ('X' or 'O').
4. The game will automatically detect if there's a winner or if it's a draw and display a message accordingly.
5. To reset the game, close the game window and run it again.

## Features

- Two players, 'X' and 'O', take turns to play.
- The game checks for a winner after each move and displays a message if a player wins.
- The game checks for a draw and displays a message if the board is full without a winner.

## Implementation Details

- The game is implemented using the Tkinter library for the graphical user interface.
- The game logic is handled by the `TicTacToe` class, which keeps track of the current player, and the state of the board, and handles button clicks.
- The `check_winner()` method is used to check if a player has won after each move.
- The `show_winner()` and `show_draw()` methods display appropriate messages when the game is over.
- The `reset_game()` method resets the game board for a new round.

## How to Contribute

If you'd like to contribute to this project, you can fork the repository and submit pull requests. Feel free to suggest new features or improvements.

## Dependencies

This project uses Python and the Tkinter library, which is included in most standard Python installations.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the README according to your preferences, and add any additional information or sections you find relevant.
