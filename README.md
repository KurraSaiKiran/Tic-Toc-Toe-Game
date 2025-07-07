# 🎮 Tic-Tac-Toe Game (Python Console)

A simple, interactive **console-based Tic-Tac-Toe** game built using Python. Two players can compete against each other on a 3x3 grid by taking turns as "X" and "O".

---

## 🌟 Overview

This project simulates a traditional Tic-Tac-Toe game in the terminal. Players alternate marking positions on the grid, aiming to align three symbols either horizontally, vertically, or diagonally.

---

## 🧠 How It Works

- The 3x3 board is represented by a 1D array with positions numbered from `0` to `8`.
- Players enter a number (0–8) corresponding to the cell they want to mark.
- The board updates after each move and checks if a player has won or if the game ends in a draw.

---

## ✨ Key Functions

- 🔳 **`printBoard(xState, zState)`**  
  Displays the current game board with "X" and "O" placed according to the current state.

- ✅ **`checkWin(xState, zState)`**  
  Checks all winning combinations to determine if "X" or "O" has won.

- ➕ **`sum(a, b, c)`**  
  Helper function used to evaluate if a line of three has the same player marks.

---

## 🕹️ How to Play

1. Open the script in any Python 3 environment.
2. Run the program:
   ```bash
   python tic_tac_toe.py
   ```
3. Follow the on-screen prompts:
   - Each player takes turns entering a number (0–8) to place their mark.
   - The game announces a winner or a draw when appropriate.

---

## 📄 Example Board (Positions)

```
0 | 1 | 2
---------
3 | 4 | 5
---------
6 | 7 | 8
```
Each number corresponds to a cell in the 3x3 grid.

---

## ✅ Winning Conditions
A player wins if they place three of their marks in any of the following patterns:

- **Rows:** `[0,1,2]`, `[3,4,5]`, `[6,7,8]`
- **Columns:** `[0,3,6]`, `[1,4,7]`, `[2,5,8]`
- **Diagonals:** `[0,4,8]`, `[2,4,6]`

---

## 📁 File Structure

```
Tic-Tac-Toe-Game/
│
├── tic_tac_toe.py       # Main Python script for the game
├── README.md            # Project documentation
```

---

## 📌 Requirements

- Python 3.x
- No external libraries required 
