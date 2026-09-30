Algorithm KnapsackBranchAndBound(Items, Capacity):
    Sort items by value-to-weight ratio descending
    PQ = PriorityQueueOrderedByUpperBound()
    Root = Node(level=0, profit=0, weight=0, bound=CalculateBound(0))
    PQ.insert(Root)
    while PQ is not empty:
        curr = PQ.extractMax()
        if curr.bound > maxProfit:
            left = IncludeNextItem(curr)
            right = ExcludeNextItem(curr)
            Update maxProfit and insert children if bound > maxProfit