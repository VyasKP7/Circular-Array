# Circular-Array
Simple implementation of a circular array

This is a dynamic circular array, that makes use of templates to allow the user to create any kind of array.

Includes some simple functions like AddEnd(element), AddFront(element), DelEnd(element), DelFront(element). Which are used to maintain the array.
operator[]           Allows the user to use the array like a regular array.
Length()             Returns the size of the array.
Capacity()           Returns the capacity of the array.
Clear()              Empties the array and sets capacity to 1.
Ordered()            Returns a boolean that checks the ordered flag (whether it is sorted). 
SetOrdered()         Sets the ordered flag.
Select(int k)        Returns the kth smallest element. (Makes use of quick select).
InsertionSort()      Sorts the array using insertion sort.
QuickSort()          Sorts the array using quick sort.
CountingSort(int m)  Sorts integer arrays using counting sort.
Search(e)            Returns index of the element e.
