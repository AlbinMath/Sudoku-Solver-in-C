# Sudoku Solver in C

A simple command-line Sudoku solver written in C.

## How to Use

1. Compile the program:
   ```sh
   gcc sudoku.c -o sudoku
   ```

2. Run the program:
   ```sh
   ./sudoku
   ```

3. Enter the Sudoku puzzle row by row.  
   - Use numbers for known cells.
   - Use `0` or `.` for empty cells.

### Example Input (Numbers and Zeros)

```
5 3 0 0 7 0 0 0 0
6 0 0 1 9 5 0 0 0
0 9 8 0 0 0 0 6 0
8 0 0 0 6 0 0 0 3
4 0 0 8 0 3 0 0 1
7 0 0 0 2 0 0 0 6
0 6 0 0 0 0 2 8 0
0 0 0 4 1 9 0 0 5
0 0 0 0 8 0 0 7 9
```

### Example Input (Dots for Empty Cells)

```
. . 5 3 . . . . .
8 . . . . . . 2 .
. 7 . . 1 . 5 . .
4 . . . . 5 3 . .
. 1 . . 7 . . . 6
. . 3 2 . . . 8 .
. 6 . 5 . . . . 9
. . 4 . . . . 3 .
. . . . . 9 7 . .
```

## Output

The program will validate and solve the puzzle, displaying the solution in a formatted grid.

---

Created by AlbinMath