# Sorting

Common Sorting Algorithms Overview
1. Bubble Sort
Stability: Stable
Time Complexity:
Best Case: 
𝑂
(
𝑛
)
O(n) (when the array is already sorted)
Average Case: 
𝑂
(
𝑛
2
)
O(n 
2
 )
Worst Case: 
𝑂
(
𝑛
2
)
O(n 
2
 )
Space Complexity: 
𝑂
(
1
)
O(1) (in-place)
Best Usage: Simple educational purposes, small datasets.
2. Selection Sort
Stability: Unstable
Time Complexity:
Best Case: 
𝑂
(
𝑛
2
)
O(n 
2
 )
Average Case: 
𝑂
(
𝑛
2
)
O(n 
2
 )
Worst Case: 
𝑂
(
𝑛
2
)
O(n 
2
 )
Space Complexity: 
𝑂
(
1
)
O(1) (in-place)
Best Usage: When memory space is limited and stability is not required.
3. Insertion Sort
Stability: Stable
Time Complexity:
Best Case: 
𝑂
(
𝑛
)
O(n) (when the array is already sorted)
Average Case: 
𝑂
(
𝑛
2
)
O(n 
2
 )
Worst Case: 
𝑂
(
𝑛
2
)
O(n 
2
 )
Space Complexity: 
𝑂
(
1
)
O(1) (in-place)
Best Usage: The array is nearly sorted.
4. Merge Sort
Stability: Stable
Time Complexity:
Best Case: 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)
Average Case: 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)
Worst Case: 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)
Space Complexity: 
𝑂
(
𝑛
)
O(n) (not in-place)
Best Usage: You have a list of tasks and you need to sort them by priority and for tasks with the same priority you need to pick them in their order of arrival.
5. Quick Sort
Stability: Unstable (but can be made stable with extra space)
Time Complexity:
Best Case: 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)
Average Case: 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)
Worst Case: 
𝑂
(
𝑛
2
)
O(n 
2
 ) (when the pivot selection is poor, e.g., always the smallest or largest element)
Space Complexity: 
𝑂
(
log
⁡
𝑛
)
O(logn) (in-place, but with recursive call stack space)
Best Usage: General-purpose sorting, when average case performance matters, arrays (rather than linked lists).
6. Heap Sort
Stability: Unstable
Time Complexity:
Best Case: 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)
Average Case: 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)
Worst Case: 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn)
Space Complexity: 
𝑂
(
1
)
O(1) (in-place)
Best Usage: When 
𝑂
(
𝑛
log
⁡
𝑛
)
O(nlogn) time complexity is needed and stability is not required, situations with limited space.
7. Counting Sort
Stability: Stable
Time Complexity:
Best Case: 
𝑂
(
𝑛
+
𝑘
)
O(n+k)
Average Case: 
𝑂
(
𝑛
+
𝑘
)
O(n+k)
Worst Case: 
𝑂
(
𝑛
+
𝑘
)
O(n+k)
Space Complexity: 
𝑂
(
𝑘
)
O(k)
Best Usage: Small range of integer keys, when auxiliary space is available and stability is required.
8. Radix Sort
Stability: Stable
Time Complexity:
Best Case: 
𝑂
(
𝑛
𝑘
)
O(nk)
Average Case: 
𝑂
(
𝑛
𝑘
)
O(nk)
Worst Case: 
𝑂
(
𝑛
𝑘
)
O(nk)
where 
𝑘
k is the number of digits/characters in the largest number/string.
Space Complexity: 
𝑂
(
𝑛
+
𝑘
)
O(n+k)
Best Usage: Large datasets of integers or strings where each item can be processed in fixed-size chunks (like digits).
