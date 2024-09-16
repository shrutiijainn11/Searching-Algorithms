# Searching-Algorithms
Different searching algorithms implementation in java

Algorithms included:

## Linear Search
### Description: 
It sequentially checks each element of the list until it finds the target value or reaches the end.
### Time Complexity:
- Best case: O(1) (if the target is the first element)
- Average/Worst case: O(n)
- Space Complexity: O(1)
### Key Points:
- Simple but inefficient for large datasets.
- Works on both unsorted and sorted arrays.
- Useful when the dataset is small or unsorted.

## Binary Search
### Description: 
This algorithm works by repeatedly dividing a sorted array in half, comparing the target value to the middle element.
### Time Complexity:
- Best case: O(1)
- Average/Worst case: O(log n)
### Space Complexity: 
O(1) (iterative) or O(log n) (recursive)
Key Points:
Requires the array to be sorted.
Much faster than linear search for large datasets.
Can be implemented iteratively or recursively.
