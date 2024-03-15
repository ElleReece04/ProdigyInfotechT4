# ProdigyInfotechT4
# Sudoku Solver

This Python program automatically solves Sudoku puzzles using a backtracking algorithm.

## Program Explanation

This program solves Sudoku puzzles by iteratively filling in empty cells with numbers from 1 to 9, ensuring that no number is repeated in the same row, column, or 3x3 subgrid. If a number violates any of these rules, the program backtracks and tries a different number. This process continues until a valid solution is found or the puzzle is determined to be unsolvable.

## Techniques Used

- **Backtracking Algorithm**: Utilized to systematically explore possible solutions and backtrack when necessary.
- **Validity Checking**: Ensures that each move (placement of a number) does not violate Sudoku rules.
- **Recursion**: The solving process is implemented recursively, trying different numbers for each cell until a solution is found.
- **Printing**: A function is included to print the Sudoku puzzle in a human-readable format, aiding visualization before and after solving.

## Usage

1. Run `main.py`.
2. Modify the Sudoku puzzle by editing the `sudoku_board` variable in the code. Empty cells are represented by zeros (0).

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.
