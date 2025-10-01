# SudukoSolver

Sudoku Solver with Backtracking and AC3

This project solves Sudoku puzzles using backtracking search, AC3 (arc consistency), and two variable selection heuristics: MRV (Minimum Remaining Values) and First Available. It also measures and visualizes performance.

Features

Grid Representation: Stores domains for all 81 cells, supports reading puzzles from strings and printing the grid.

Variable Selection:

FirstAvailable: Picks the first unassigned cell.

MRV: Picks the cell with the smallest domain.

AC3: Enforces arc consistency to reduce search space.

Backtracking Search: Combines inference and variable heuristics.

Performance Visualization: Plots running time comparison between heuristics.

Usage

Place a text file of puzzles (81-character strings) in the project folder.

Run the solver:

python sudoku_solver.py


Output includes success counts, running times, and a scatter plot comparing MRV vs First Available.

Dependencies
pip install matplotlib numpy
