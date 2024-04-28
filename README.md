
# Sudoku Solver

This is a simple C++ program to solve Sudoku puzzles using backtracking algorithm.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [How to Use](#how-to-use)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This program solves a given Sudoku puzzle using a backtracking algorithm. It takes an unsolved Sudoku grid as input, solves it, and prints the solved grid if a solution exists. If no solution exists, it prints "No solution exists".

## Features

- Solves Sudoku puzzles of size 9x9.
- Uses a backtracking algorithm to efficiently find solutions.
- Validates whether a given Sudoku puzzle is solvable or not.
- Prints the solved Sudoku grid.

## How to Use

1. Clone the repository or download the `sudoku_solver.cpp` file.
2. Compile the code using a C++ compiler (e.g., g++).
   ```bash
   g++ sudoku_solver.cpp -o sudoku_solver
   ```
3. Run the compiled executable.
   ```bash
   ./sudoku_solver
   ```
4. Enter the unsolved Sudoku grid in the code or provide it as input during runtime.
5. The program will print the solved Sudoku grid if a solution exists, otherwise it will print "No solution exists".

## Example

Input:
```cpp
// Unsolved Sudoku grid
int grid[N][N] = {
   {3, 0, 6, 5, 0, 8, 4, 0, 0},
   {5, 2, 0, 0, 0, 0, 0, 0, 0},
   {0, 8, 7, 0, 0, 0, 0, 3, 1},
   {0, 0, 3, 0, 1, 0, 0, 8, 0},
   {9, 0, 0, 8, 6, 3, 0, 0, 5},
   {0, 5, 0, 0, 9, 0, 6, 0, 0},
   {1, 3, 0, 0, 0, 0, 2, 5, 0},
   {0, 0, 0, 0, 0, 0, 0, 7, 4},
   {0, 0, 5, 2, 0, 6, 3, 0, 0}
};
```

Output:
```
3 1 6 | 5 7 8 | 4 9 2 
5 2 9 | 1 3 4 | 7 6 8 
4 8 7 | 6 2 9 | 5 3 1 
------+------+------
2 6 3 | 4 1 5 | 9 8 7 
9 7 4 | 8 6 3 | 1 2 5 
8 5 1 | 7 9 2 | 6 4 3 
------+------+------
1 3 8 | 9 4 7 | 2 5 6 
6 9 2 | 3 5 1 | 8 7 4 
7 4 5 | 2 8 6 | 3 1 9 
```

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

--- 

Feel free to modify it according to your preferences or add any additional information you think would be useful!
