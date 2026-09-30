Algorithm OptimalMerge(files):
    Insert all file sizes into a Min-Priority Queue PQ
    total_cost = 0
    while size(PQ) > 1:
        f1 = Extract-Min(PQ)
        f2 = Extract-Min(PQ)
        merged_size = f1 + f2
        total_cost = total_cost + merged_size
        Insert(PQ, merged_size)
    return total_cost