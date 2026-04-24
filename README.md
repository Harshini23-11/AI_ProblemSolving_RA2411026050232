# AI Problem Solving Assignment

## Problem 2: Map Coloring Problem (CSP)

This project solves the map coloring problem using Constraint Satisfaction Problem (CSP) approach.

### Algorithm Used:

* Backtracking (CSP)

### Features:

* User-defined regions and adjacency
* Valid color assignment
* No adjacent regions share same color

---

## How to Run

1. Open MapColoring_CSP folder
2. Open index.html in browser
3. Enter input and click solve

---

## Sample Output

(<img width="1895" height="1012" alt="image" src="https://github.com/user-attachments/assets/704e5e49-7986-4894-a1c0-ff349070b79c" />
)

---

## GitHub Repository

(https://github.com/Harshini23-11/AI_ProblemSolving_RA2411026050232)

## Website Link

(https://harshini23-11.github.io/AI_ProblemSolving_RA2411026050232/MapColoring_CSP/MapColoring_CSP/)

## Performance Comparison

The Map Coloring problem is solved using the Constraint Satisfaction Problem (CSP) approach with Backtracking.

- Backtracking Algorithm:
  - Tries assigning colors to regions one by one.
  - Checks constraints (no adjacent regions share same color).
  - If a conflict occurs, it backtracks and tries a different color.

### Performance Analysis:
- Execution Time:
  - Fast for small maps (few regions and colors).
  - Increases as the number of regions and constraints grow.

- Number of Nodes Explored:
  - Backtracking explores multiple combinations of color assignments.
  - Worst case: exponential growth in search space.

- Efficiency:
  - Avoids invalid solutions early using constraint checking.
  - More efficient than brute-force because it stops exploring invalid paths.

### Conclusion:
- Backtracking provides a correct and optimal solution for CSP.
- Suitable for small to medium-sized problems.
- Performance can be improved using heuristics like:
  - Minimum Remaining Values (MRV)
  - Forward Checking

