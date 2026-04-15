# Sudoku Solver using CSP
# This project implements a Sudoku Solver using Constraint Satisfaction Problem (CSP) techniques in Python. It uses AC-3 for constraint propagation and backtracking with MRV and forward checking to efficiently solve Sudoku puzzles of different difficulty levels.
## Features
- Solves Sudoku puzzles (Easy to Very Hard)
- Uses AC-3 algorithm for domain reduction
- Backtracking search with MRV heuristic
- Forward checking for pruning
- Displays solution in a readable format
- Tracks execution time and backtracking stats
## How to Run
1. Make sure Python is installed
2. Run the file:
   python l230714_A5_AI.py
## Input
- Sudoku board is given as a string of 81 digits
- '0' represents empty cells
## Output
- Solved Sudoku grid
- Number of backtracking calls
- Number of failures
- Execution time
