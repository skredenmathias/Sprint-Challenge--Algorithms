#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n^3)
    given input size n, we run a while loop with range n^3.


b) O(n)
    for i in range(n) (O(n)), perform an operation on j. 


c) O(2n) --> O(n)

## Exercise II


We want to find the floor with maximum efficiency, as to minimize broken eggs.
A safe way to do that is a binary search.

# Set low to 0
# Set high to height of n-story building
# set midpoint

# check if target == midpoint
# if so, return midpoint

# if not, then if target < midpoint, we search that half of the array
# set high to midpoint

# if target > midpoint:
# set low to midpoint + 1

# else, return -1

# Runtime of this is O(log(n))