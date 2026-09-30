Algorithm 01Knapsack(weights, values, Capacity, N):
    Create DP matrix of size (N+1) x (Capacity+1) initialized to 0
    for i from 1 to N:
        for w from 0 to Capacity:
            if weights[i-1] <= w:
                DP[i][w] = max(values[i-1] + DP[i-1][w - weights[i-1]], DP[i-1][w])
            else:
                DP[i][w] = DP[i-1][w]
    return DP[N][Capacity]