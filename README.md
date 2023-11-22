# Sorting Algorithms
<hr>

A `sorting algorithm` is an algorithm that puts elements of a list into an order. The most frequently used orders are `numerical order` and `lexicographical order`, and either ascending or descending. Efficient sorting is important for optimizing the efficiency of other algorithms (such as search and merge algorithms) that require input data to be in sorted lists. Sorting is also often useful for `canonicalizing data` and for producing `human-readable` output.

Formally, the output of any sorting algorithm must satisfy two conditions:

 1. The output is in monotonic order (each element is no smaller/larger than the previous element, according to the required order).
 2. The output is a permutation (a reordering, yet retaining all of the original elements) of the input.
 
# Various Sorting Algorithms are as follows:


## Insertion Sort
Insertion sort is a simple sorting algorithm that builds the final sorted array (or list) one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.
Insertion sort iterates, consuming one input element each repetition, and growing a sorted output list. At each iteration, insertion sort removes one element from the input data, finds the location it belongs within the sorted list, and inserts it there. It repeats until no input elements remain.

Time complexity analysis:

|Worst Case|Average Case|Best Case|
|---|---|---|
|O(n<sup>2</sup>)|Θ(n<sup>2</sup>)|Ω(n)|

|In-place?|Stable?|
|---|---|
|Yes|Yes|


