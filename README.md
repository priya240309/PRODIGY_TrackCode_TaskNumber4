# Sudoku Solver

This is a simple Java application to solve Sudoku puzzles. The application uses a backtracking algorithm to find the solution for a given 9x9 Sudoku board.

## How to Use

1. **Clone the repository** or download the `SudokuSolver.java` file to your local machine.

2. **Open the `SudokuSolver.java` file** in your favorite Java IDE or text editor.

3. **Modify the `board` array** in the `main` method to represent the Sudoku puzzle you want to solve. The empty cells should be represented by `0`.

    ```java
    int[][] board = {
        {5, 3, 0, 0, 7, 0, 0, 0, 0},
        {6, 0, 0, 1, 9, 5, 0, 0, 0},
        {0, 9, 8, 0, 0, 0, 0, 6, 0},
        {8, 0, 0, 0, 6, 0, 0, 0, 3},
        {4, 0, 0, 8, 0, 3, 0, 0, 1},
        {7, 0, 0, 0, 2, 0, 0, 0, 6},
        {0, 6, 0, 0, 0, 0, 2, 8, 0},
        {0, 0, 0, 4, 1, 9, 0, 0, 5},
        {0, 0, 0, 0, 8, 0, 0, 7, 9}
    };
    ```

4. **Compile and run the program** using the command line or your IDE.

    If you are using the command line, navigate to the directory where the `SudokuSolver.java` file is located and run:

    ```sh
    javac SudokuSolver.java
    java SudokuSolver
    ```

5. **View the solution**. If a solution exists, the solved Sudoku board will be printed to the console. If no solution exists, a message stating "No solution exists." will be printed.

## Example

For the provided example board in the `SudokuSolver.java` file, the output will be:

