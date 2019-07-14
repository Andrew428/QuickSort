# QuickSort
CS concepts showing the implimtaion of QuickSort in javascript.

Popular and efficient sorting algorithm.  


The way it works is you pick a pivot element usually in the center of the array.  Then you scan through array from both the left and the right side of the pivot.  As you scan you will swap element if they are out of order, meaning elements less than you pivot element value should come before elements greater than you pivot element value.  This will lead to a sub-set of values `less than` and `greater than` the pivot element value.  
 
Next you will continue to run each `less than` and `greater than` sub-set through the quick sort.  Continuing this process will result in a sorted array.  

The BigO for a quick sort is `O(n log n)` on average and `O(n^2)` in the worst case scenario.  Worst case scenario would arise if you were to pick your pivot point index at the beginning or end of the array. 
