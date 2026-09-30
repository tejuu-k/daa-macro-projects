Algorithm SolveNQueens(board, row, N):
    if row == N:
        Print Solution
        return
    for col from 0 to N-1:
        if IsSafe(board, row, col):
            board[row] = col
            SolveNQueens(board, row + 1, N)
            board[row] = -1 // Backtrack