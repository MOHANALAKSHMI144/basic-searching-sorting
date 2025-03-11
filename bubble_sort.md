# Bubble Sort

Bubble sort psuedocode

```
# Write the psuedocode 
START
def bubble_sort(list):
    n = len(list)
    for i in range(n - 1):
        swapped = False
        for j in range(0, n - i - 1):
            if list[j] > list[j + 1]:
                list[j], list[j + 1] = list[j + 1], list[j]
                swapped = True
        if not swapped:
            break
    return list
END
```
