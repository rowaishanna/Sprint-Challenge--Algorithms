#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) This pseudocode has a runtime of O(n).  Even though the loop has a n to the third as a condition, the code increments by n squared each pass.


b) This pseudocode has a runtime of O(nlogn).  A linear for loop that will run through the entire range of n.


c) This pseudocode has a runtime of O(n).

## Exercise II
Step 1: check if the top floor is greater than the bottom floor.
if yes:
Step 2: take the top floor value plus the bottom floor value and // by 2 to find the middle floor.
Step 3: drop an egg from the middle floor.
Step 4: if broken, the middle floor would be the new top floor.  Return to step 2 and repeat the process.
Step 4: if not broken, the middle floor would be the new bottom floor.  Return to setep 2 and repeat the process.
If no:
Step 2: return the value of the top or bottom floor, as the should be the same.

Value of floor f is found.
Runtime complexity of this solution is O(logn) because it is a binary search. 

