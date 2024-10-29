# Tic-Toc-Toe-Game
This project is a simple, console-based Tic Tac Toe game built with Python. The game allows two players to compete on a 3x3 grid, taking turns as either "X" or "O". The first player to align three of their marks in a row, column, or diagonal wins the game, otherwise, it ends in a draw if the grid fills up.

 How It Works:
The game board is represented by an array where each index corresponds to a cell on the 3x3 grid.
X and O players take turns choosing an available cell by entering the cell's number (0–8).
The game displays the updated board after each turn and checks for winning conditions.
The first player to align three marks wins, and a message displays the winner. If no player wins, the game continues until all cells are filled, resulting in a draw.
 Key Functions:
printBoard(xState, zState): Displays the current board, showing where "X" and "O" are placed.
checkWin(xState, zState): Checks for all possible winning combinations after each move and returns the winner if a winning condition is met.
sum(a, b, c): Helper function that calculates the sum of three values, used in checking winning conditions.
Running the Game
 To play:
Run the code in a Python environment.
Enter the cell number (0–8) when prompted to place your mark.
Continue taking turns until a winner is declared or the game ends in a draw.
