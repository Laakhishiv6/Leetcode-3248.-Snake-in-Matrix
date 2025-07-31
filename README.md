# Leetcode-3248.-Snake-in-Matrix
# Description
There is a snake in an n x n matrix grid and can move in four possible directions. Each cell in the grid is identified by the position: grid[i][j] = (i * n) + j.

The snake starts at cell 0 and follows a sequence of commands.

You are given an integer n representing the size of the grid and an array of strings commands where each command[i] is either "UP", "RIGHT", "DOWN", and "LEFT". It's guaranteed that the snake will remain within the grid boundaries throughout its movement.

Return the position of the final cell where the snake ends up after executing commands.

# Solution
In the given problem we have been given an array of string which contains the commands . An n x n matrix in which we can have 4 possible moves or commands as : UP,RIGHT,LEFT and DOWN.

We need to find me position of the cell with the final cell.

The position can be identified using  grid[i][j] = (i * n) + j.
----> i
+-----------+-----------+  |
| [0][0]    | [0][1]    |  |
+-----------+-----------+  j
| [1][0]    | [1][1]    |
+-----------+-----------+

<img width="488" height="330" alt="image" src="https://github.com/user-attachments/assets/7cfa44d9-9d29-4db6-869a-484b68db848d" />
