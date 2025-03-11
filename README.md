  # Searching and Sorting 

Searching is the process of finding an element in a collection of data (like an array, list, or database). You want to locate a specific item or value and possibly return its position or presence in the collection. 

Sorting is the process of arranging data in a specific order, typically in ascending or descending order. This is often done to make searching faster and to help with various types of analysis. 

## Common Searching Algorithms 

-  **Linear Search** - Checks every element in the collection one by one. It's simple but not efficient for large data sets.
- **Binary Search** - Requires a sorted collection and checks the middle element to repeatedly narrow down the search space, making it much faster than linear search.

## Common Sorting Algorithms

- **Bubble Sort** - Steps through the list, compares adjacent items, and swaps them if they're in the wrong order.
- **Quick Sort** - Divides the collection into smaller sublists and sorts them independently.
- **Merge Sort** - Divides the collection into halves, sorts each half, and then merges them back together.
- **insertion Sort** - Builds the sorted list one item at a time.

### Bubble Sort

Bubble sort is one of the simplest sorting algorithms, but it's also one of the least efficient. It works by repeatedly stepping through the list, comparing adjacent items, and swapping them if they are in the wrong order. This process is repeated until the list is sorted.

**Algorithm**
- Start at the beginning of the list.
- Compare each pair of adjacent elements.
- If the current element is greater than the next, swap them.
- Repeat steps 2 and 3 for each pair of elements, moving from left to right.
- After each pass through the list, the largest element "bubbles up" to the end.
- Repeat the process for the remaining unsorted portion of the list.
- Stop when no more swaps are needed
-
- START
INPUT n, i
Procedure BubbleSort(array)
    n = length of array
    Repeat
        swapped = false
        For i from 0 to n-2 do
            If array[i] > array[i+1] then
                Swap array[i] and array[i+1]
                swapped = true
            End If
        End For
        n = n - 1  
    Until swapped = false
End Procedure
END



