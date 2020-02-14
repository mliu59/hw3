# Discussion

## Part A
1. Discuss from a design perspective whether or not iterating over a MeasuredArray should affect the accesses and mutation counts. 

2. Can you inherit ArrayIterator from SimpleArray and override the relevant methods, or not? Explain.

## Part B
Include the results of experiments (must have concrete time measurements and size of data set used).
1. There is an intentional mistake in one of the provided data files. The goal of this assignment is to use the measurements to catch that mistake. 
2. Does the actual running time correspond to the asymptotic complexity as you would expect?
3. What explains the practical differences between these algorithms? (Theoretically, the algorithm runs in O(X) time, where X is a function of the input size, but in practice (i.e running it on datasets), you may observe that it is slower/faster compared to the other algorithms)
4. Does it matter what kind of data (random, already sorted in ascending
 order, sorted in descending order) you are sorting? How should each algorithm behave (in terms of performance) based on
  the
  type of data it
  receives?
5. How do your implementations compare to the sorting done by Java
 Collections? Do you think that the standardized code is just better written than yours or is more asymptoticly efficient? How would you go about determining which is the case?

## Part C
1. Determine exactly how many comparisons C(n) and assignments A(n) are performed by this implementation of selection sort in the worst case. Both of those should be polynomials of degree 2 since you know that the asymptotic complexity of selection sort is O(n^2).

