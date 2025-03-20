# Sudoku Solver in Java

A simple **Sudoku Solver** implemented in Java using a **backtracking algorithm**. The program fills in missing numbers in a 9x9 Sudoku grid while ensuring the solution follows Sudoku rules.

## How It Works
1. The program initializes a 9x9 Sudoku board with some prefilled numbers.
2. It applies a **recursive backtracking algorithm** to find a valid solution.
3. If a solution exists, the solved board is printed; otherwise, a message indicates that the board is unsolvable.

## Features
- Uses **backtracking** to find a valid solution.
- Prints the Sudoku board **before and after** solving.
- Ensures:
  - Each row contains unique numbers (1-9).
  - Each column contains unique numbers (1-9).
  - Each 3x3 subgrid contains unique numbers (1-9).

## Installation & Usage
1. **Clone this repository**  
   ```bash
   git clone https://github.com/sofiasawczenko/sudoku.git
   cd sudoku-solver

2. **Compile and Run**
 ```bash
javac SudokuSolver.java
java SudokuSolver
