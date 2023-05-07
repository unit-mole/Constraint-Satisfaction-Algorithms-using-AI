# Constraint-Satisfaction-Algorithms-using-AI <br>

This is a Python implementation of a Sudoku solver for 9 x 9 Sudoku puzzles, based on Constraint Satisfaction Algorithms. <br>

## Algorithms Used:
1) Backtracking: Backtracking is a commonly used technique in solving constraint satisfaction problems, including Sudoku puzzles. The backtracking algorithm works by systematically trying different values for each empty cell in the puzzle, and undoing any changes when a contradiction is found, until a solution is found or all possible combinations have been tried. <br>

2) Breadth First search: Breadth-First Search (BFS) is a widely used algorithm for traversing or searching through a graph or a tree structure in a breadth-first order. In the context of Sudoku, BFS can be used to systematically explore different possible solutions to a puzzle by considering all possible combinations of numbers that could fill in the empty cells. <br>

3) Constraint Propagation: Constraint propagation is a technique used in constraint satisfaction problems to reduce the search space by iteratively applying constraints to eliminate inconsistent values from the domain of variables. In the context of Sudoku, constraint propagation involves using the constraints of the puzzle to iteratively eliminate possible values from the domains of the empty cells until a solution is found or no more progress can be made. <br>

4) Depth First search: Depth-First Search (DFS) is a widely used algorithm for traversing or searching through a graph or a tree structure in a depth-first order. In the context of Sudoku, DFS can be used to systematically explore different possible solutions to a puzzle by recursively trying out all possible values that could fill in the empty cells. <br>

5) Forward search: Forward search is a technique used in constraint satisfaction problems to reduce the search space by identifying the most promising variables and values to try first. In the context of Sudoku, forward search involves iteratively selecting an empty cell with the fewest remaining possible values, and trying out each of these values in turn until a solution is found or no more progress can be made. <br>

6) Genetic Algorithms: Genetic Algorithms (GA) is a type of optimization algorithm that is inspired by the process of natural selection. In the context of Sudoku, GA can be used to find a good solution to a puzzle by treating it as a search space of possible solutions and using evolutionary principles to iteratively generate and evaluate new candidate solutions. <br>

7) Local Search: Local search is a type of optimization algorithm that starts with an initial solution and iteratively improves it by making small changes to the current solution. In the context of Sudoku, local search can be used to find a good solution to a puzzle by starting with a random or partially filled solution and iteratively improving it by swapping values in neighboring cells until no more improvements can be made. <br>

8) Simulated Annealing Algorithm: Simulated Annealing is a type of stochastic optimization algorithm that is inspired by the process of annealing in metallurgy. In the context of Sudoku, simulated annealing can be used to find a good solution to a puzzle by starting with a random or partially filled solution and iteratively perturbing the solution to explore the search space and avoid getting stuck in local optima. <br>

## Puzzle Input: <br>
[ <br>
        [5, 3, 0, 0, 7, 0, 0, 0, 0], <br>
        [6, 0, 0, 1, 9, 5, 0, 0, 0], <br>
        [0, 9, 8, 0, 0, 0, 0, 6, 0], <br>
        [8, 0, 0, 0, 6, 0, 0, 0, 3], <br>
        [4, 0, 0, 8, 0, 3, 0, 0, 1], <br>
        [7, 0, 0, 0, 2, 0, 0, 0, 6], <br>
        [0, 6, 0, 0, 0, 0, 2, 8, 0], <br>
        [0, 0, 0, 4, 1, 9, 0, 0, 5], <br>
        [0, 0, 0, 0, 8, 0, 0, 7, 9] <br>
    ] <br>


## Important Notes: <br>
(1) The implementation uses the set data type to represent the domain of each variable. <br>
(2) The ac3() function performs arc consistency, which reduces the domain of each variable by eliminating inconsistent values. <br>
(3) The backtrack() function performs backtracking search to find a solution to the Sudoku puzzle. <br>
(4) The get_neighbors() function returns the neighbors of a variable, which are the variables that share the same row, column, or 3 x 3 box. <br>
(5) The other algorithms are alternative approaches to solving Sudoku puzzles using constraint satisfaction methods. <br>
(6) The program can be run with different algorithms by changing the function called in the solve_sudoku() function. <br>



