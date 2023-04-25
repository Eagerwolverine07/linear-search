# linear-search

Introduction
Linear search is a simple search algorithm that searches for an element in an array by sequentially checking each element until a match is found or the end of the array is reached. It is also known as a sequential search.

The time complexity of linear search is O(n) in the worst case, where n is the size of the array. This means that for large arrays, linear search can be slow, and other algorithms such as binary search may be more efficient.

Algorithm
1.Start from the first element of the array.
2.Compare the current element with the element to search for.
3.If the current element is equal to the element to search for, return its index.
4.If the current element is not equal to the element to search for, move to the next element in the array.
Repeat steps 2 to 4 until a match is found or the end of the array is reached.
If the end of the array is reached and the element to search for is not found, return -1.
