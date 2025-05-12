# Java_Sudoku_Solver

This is a simple Java program that solves a 9x9 Sudoku puzzle using backtracking. It checks for valid placements and recursively fills the grid until the solution is complete.

## 🧠 How It Works

- The algorithm uses **backtracking** to try numbers from 1 to 9 in empty cells.
- Before placing a number, it checks if it is safe using:
  - Row check
  - Column check
  - 3x3 subgrid check
- If a placement leads to a dead-end, it backtracks and tries another number.
