# -N-Queens-Problem-Solver
This project solves the classic **N-Queens** problem using **backtracking** in Python. The N-Queens problem is the challenge of placing N chess queens on an N×N chessboard so that no two queens threaten each other.


## 🧠 Problem Description

- No two queens can be in the same row, column, or diagonal.
- This implementation finds **all possible solutions** for a given `n`.
- Uses a simple 1D list to represent the board state efficiently.

## 📦 Features

- Finds all valid solutions for the N-Queens problem.
- Prints each solution in a human-readable board format.
- Allows showing only a subset of the solutions (e.g., first 2 solutions).

## 🧮 Example: 8-Queens

When run with `n = 8`, this program finds all **92** possible solutions to the 8-Queens problem and displays the first 2 as output.

### Sample Output:

Number of solutions: 92

Solution 1:
. Q . . . . . .
. . . . Q . . .
. . . . . . Q .
. . Q . . . . .
. . . . . Q . .
Q . . . . . . .
. . . Q . . . .
. . . . . . . Q

Solution 2:
. Q . . . . . .
. . . . . Q . .
. . . Q . . . .
Q . . . . . . .
. . . . . . Q .
. . Q . . . . .
. . . . Q . . .
. . . . . . . Q


## 🚀 How to Run

1. Clone the repository or download the Python script:
   ```bash
   git clone https://github.com/yourusername/n-queens-solver.git
   cd n-queens-solver

    Run the program:

python n_queens.py

To change the board size (n), modify the line:

    solve_n_queens(8, board=[], solutions=solutions)

🧾 Files

    n_queens.py: Main script to solve and print N-Queens solutions.

    README.md: Project overview and instructions.

🛠️ Requirements

    Python 3.x (no additional libraries needed)

📚 Concepts Used

    Backtracking algorithm

    Recursive functions

    Board representation using 1D list

📜 License

This project is licensed under the MIT License.
