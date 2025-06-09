Rat in a Maze – Problem Description
The "Rat in a Maze" problem is a classic backtracking algorithm problem in computer science and programming. It involves finding all possible paths for a rat to travel from the starting point (top-left corner) to the destination (bottom-right corner) in a maze, moving only in allowed directions.

Problem Statement
Given an n x n maze represented as a 2D grid, where:
1 represents an open path the rat can move through.
0 represents a blocked cell the rat cannot enter.
You have to find all possible paths from the start cell (0, 0) to the destination cell (n-1, n-1). The rat can move in 4 directions:

Down (D)
Left (L)
Right (R)
Up (U)

Maze Example:
Input:
maze[][] = { {1, 0, 0, 0},
             {1, 1, 0, 1},
             {0, 1, 0, 0},
             {1, 1, 1, 1} }

Output:
DRDDRR

Constraints:
Only valid paths are through cells with value 1.
Cannot move outside the grid.
Cannot visit a cell more than once in a path (no cycles).
You need to return or print all possible paths in lexicographical order if asked.

