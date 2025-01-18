# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error arises because the loop condition `i <= arr.length` includes the index that is out of bounds for the array.  The solution corrects the loop condition to ensure the loop iterates only within the valid index range of the array. 