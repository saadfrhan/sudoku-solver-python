# Sudoku Solver

This is a Python implementation of a backtracking algorithm to solve 9x9 Sudoku puzzles. The empty cells in the Sudoku puzzle are represented by `-1`.

## How it Works

The solver uses recursion and backtracking to try out guesses for the empty cells. It checks if the guess is valid for the current row, column, and 3x3 box. If a guess leads to a valid solution, it fills the cell. If not, it backtracks and tries another number.

## Features

- Solves any valid 9x9 Sudoku puzzle
- Uses a simple backtracking algorithm
- Handles empty cells denoted by `-1`
