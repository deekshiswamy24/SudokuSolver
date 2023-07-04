# SudokuSolver


This project implements a Sudoku solver and provides a graphical user interface (GUI) to interactively solve Sudoku puzzles. The solver algorithm is implemented using backtracking, while the GUI is built using the Pygame library.

## Features

- GUI-based Sudoku puzzle solver
- Interactive grid for user input
- Solve button to automatically solve the puzzle
- Clear button to reset the grid
- Real-time visual feedback for incorrect inputs
- Timer to track solving time
- Strikes counter to keep track of incorrect inputs

## Installation

1. Clone the repository:

   ```shell
   git clone <repository-url>\


Navigate to the project directory:
   cd sudoku-solver-gui

Install the required dependencies:
   pip install pygame


Usage
To run the Sudoku solver GUI, execute the following command:

   python guiapp.py

Once the GUI is launched, follow these steps:

Click on a cell to select it.
Use the number keys (1-9) to enter a value in the selected cell.
Press the Enter key to place the value in the cell.
If the value is valid, it will be displayed in the cell.
If the value is invalid (conflicts with existing values in the same row, column, or box), the cell will be highlighted and a strike will be added.
Repeat steps 1-5 to fill in the entire puzzle.
Once the puzzle is filled, click the "Solve" button to automatically solve it.
To clear the grid and start over, click the "Clear" button.
The timer at the top of the window displays the solving time.
The strikes counter indicates the number of incorrect inputs.


Algorithm
The Sudoku solver algorithm uses a recursive backtracking approach. It starts by finding an empty cell in the grid and tries all possible values (1-9) in that cell. If a value leads to a valid solution, it moves on to the next empty cell and repeats the process. If a value is invalid, it backtracks and tries the next value. This process continues until a solution is found or all possible combinations are exhausted.



Acknowledgements
The Pygame library: https://www.pygame.org
Sudoku puzzles sourced from https://www.sudoku.com 

 
