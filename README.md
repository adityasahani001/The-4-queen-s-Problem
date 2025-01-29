# The-4-queen-s-Problem
The 4-Queen Problem is a classic puzzle in the field of combinatorial optimization. It's a smaller version of the famous N-Queen Problem, where the goal is to place N queens on an N×N chessboard such that no two queens threaten each other. In this case, we are working with a 4×4 board and four queens.

This problem can be solved using backtracking, a systematic trial-and-error approach to explore all possible arrangements:

Starting from the first row, attempt to place a queen in each column one by one.

Move to the next row, placing a queen in a column that satisfies all constraints.

If no valid position is found for a row, backtrack to the previous row, adjust the queen’s position, and continue.

First Arrangement:

Queen 1: Row 1, Column 2 (1,2)

Queen 2: Row 2, Column 4 (2,4)

Queen 3: Row 3, Column 1 (3,1)

Queen 4: Row 4, Column 3 (4,3)

Second Arrangement:

Queen 1: Row 1, Column 3 (1,3)

Queen 2: Row 2, Column 1 (2,1)

Queen 3: Row 3, Column 4 (3,4)

Queen 4: Row 4, Column 2 (4,2)
