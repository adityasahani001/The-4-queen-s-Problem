# The-4-queen-s-Problem
The 4-Queen Problem is a classic puzzle in the field of combinatorial optimization. It's a smaller version of the famous N-Queen Problem, where the goal is to place N queens on an N×N chessboard such that no two queens threaten each other. In this case, we are working with a 4×4 board and four queens.

This problem can be solved using backtracking, a systematic trial-and-error approach to explore all possible arrangements:

Starting from the first row, attempt to place a queen in each column one by one.
Move to the next row, placing a queen in a column that satisfies all constraints.
If no valid position is found for a row, backtrack to the previous row, adjust the queen’s position, and continue.
