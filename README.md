# SudokuSolver

A simple Python-based Sudoku solver that uses backtracking to solve standard 9x9 Sudoku puzzles. This project demonstrates how to represent a Sudoku board, check for valid moves, and recursively solve the puzzle.

---

## Features

- Solves any 9x9 Sudoku puzzle using backtracking
- Displays the board before and after solving
- Checks for the validity of moves (row, column, and 3x3 box constraints)
- Simple and readable code structure for educational purposes

---

## How It Works

1. **Board Representation:**  
   The Sudoku board is represented as a 2D list (`board`). Empty cells are denoted by `0`.

2. **Solving Algorithm:**  
   The `solve(board)` function uses recursion and backtracking to fill empty cells. It tries numbers 1-9 in each empty cell and checks if the placement is valid using the `valid()` function. If a solution is found, it fills the board and returns `True`.

3. **Validation:**  
   The `valid(board, number, position)` function checks if the attempted number placement is valid according to Sudoku rules (row, column, and 3x3 box).

4. **Board Display:**  
   The `print_board(board)` function formats and prints the board in a human-readable way.

---

## Getting Started

### Prerequisites

- Python 3.x

### Installation

Clone the repository:
```bash
git clone https://github.com/vishwavinayak/SudokuSolver.git
cd SudokuSolver
```

---

## Usage

Run the solver using Python:

```bash
python SudokuSolver.py
```

The output will display the board before and after solving.

---

## Example Board

```python
board = [
    [7,8,0,4,0,0,1,2,0],
    [6,0,0,0,7,5,0,0,9],
    [0,0,0,6,0,1,0,7,8],
    [0,0,7,0,4,0,2,6,0],
    [0,0,1,0,5,0,9,3,0],
    [9,0,4,0,6,0,0,0,5],
    [0,7,0,3,0,0,0,1,2],
    [1,2,0,0,0,7,4,0,0],
    [0,4,9,2,0,6,0,0,7]
]
```

You can modify the initial `board` variable in `SudokuSolver.py` to solve different puzzles.

---




