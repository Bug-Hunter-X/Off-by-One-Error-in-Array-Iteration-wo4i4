# Off-by-One Error in Java Array Iteration

This repository demonstrates a common off-by-one error in Java when iterating over an array. The error occurs because the loop condition is incorrectly checking `i <= arr.length` which leads to an attempt to access an index out of bounds.