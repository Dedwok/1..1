def sum_negatives_between_min_max(arr):
    if not arr or len(arr) < 2:
        return 0
    
    min_val = min(arr)
    max_val = max(arr)
    
    min_index = arr.index(min_val)
    max_index = arr.index(max_val)
    
    start, end = (min_index, max_index) if min_index < max_index else (max_index, min_index)
    
    sum_neg = sum(x for x in arr[start+1:end] if x < 0)
    
    return sum_neg
