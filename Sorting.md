# Sorting
Sorting is the process of arranging a collection of items or data in a specific order, often following some criteria.
</br>
Sorting algorithms are step-by-step procedures or methods used to arrange a collection of items or data into a specific order. These algorithms determine how the items are compared and rearranged to achieve the desired sorting order, such as ascending or descending.

# Bubble Sort
Bubble Sort is a simple sorting algorithm that works by repeatedly stepping through a list of items, comparing adjacent items, and swapping them if they are in the wrong order.
</br>
Bubble Sort is simple to understand and implement, but it's not very efficient, especially for large lists. Its average and worst-case time complexity is O(n^2), where "n" is the number of items in the list. This means that as the number of items increases, the time it takes to sort the list grows significantly.

# Insertion Sort
Insertion Sort is a simple sorting algorithm that builds the final sorted list one item at a time. It's like sorting a hand of cards: you start with an unsorted hand and gradually insert cards into their correct positions.
Start from already sorted part and compare the next element one by one with the sorted elements and find a place for it, then go for another element
Best case scenario O(n). Worst: O(n^2)

# Selection Sort
 Selection sort involves selecting the smallest (or largest) element from the unsorted part of the list and swapping it with the element in the first position of the unsorted part.

# Merge Sort

Merge sort divides the list into smaller sublists, sorts them, and then merges the sorted sublists to create a fully sorted list.

# Quick Sort

It finds an element called Pivot which divides the array into two halves in such a way that elements in the left half are smaller than pivot, and elements in the right are greater than pivot
O(log n) 

# Heap Sort
Heap sort uses a binary heap data structure to efficiently build a sorted array. It repeatedly extracts the maximum (or minimum) element from the heap and rebuilds the heap.
O(n log n)

# Counting Sort
Counting sort works well for integers with a limited range. It counts the occurrence of each element and uses this information to place the elements in the correct order.

# Radix Sort
Radix sort is used for sorting numbers with a fixed number of digits. It sorts the numbers digit by digit.
</br>
The choice of sorting algorithm depends on factors like the size of the data, the specific requirements of the task, and the efficiency goals. Some sorting algorithms are more suitable for smaller data sets, while others are optimized for larger data sets. 
