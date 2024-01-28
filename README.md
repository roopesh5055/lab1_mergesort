Merge Sort Program in Python:

The provided Python program implements the Merge Sort algorithm, which is a popular and efficient sorting algorithm. Merge Sort follows the divide-and-conquer strategy, breaking the input array into smaller halves, sorting them recursively, and then merging the sorted halves to produce the final sorted array.

Program Description:

merge_sort(arr): This function takes an unsorted array arr as input and recursively sorts it using the Merge Sort algorithm.

merge(left, right): This helper function is used to merge two sorted arrays (left and right) into a single sorted array.

main(): In the main section, an example array is initialized. The merge_sort function is then called to sort the array, and the sorted result is printed.

How Merge Sort Works:

Divide: The array is recursively divided into smaller halves until each sub-array contains only one element.

Conquer: The single-element sub-arrays are then merged in a sorted manner, combining them into larger sorted sub-arrays.

Combine: The merging process is repeated until the entire array is sorted.