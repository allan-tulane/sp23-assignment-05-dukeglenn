# CMPS 2200 Assignment 5
## Answers

**Name:** Duke Glenn


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**
To produce as few coins as possible to sum to N, we can use this greedy algorithm:

1. Make an empty list of coins
2. While N > 0:
3.   Find the largest denomination such that the coin is less than the value of n
4.   Add the largest denomination to the list
5.   Subtract the denomination from n

This algorithm is optimal, as since the coins are all a power of 2, the greedy algorithm will always output the correct number of coins.


- **1b.**
The work is O(log n)
The span is O(log n)

- **2a.**
Assume that the currencies are $1, $3, and $4, and you need to make change for $6. The greedy algorithm would not be optimal since it would select $4, $1, then $1, when it is optimal to select $3 then $3. 

- **2b.**
With dynamic programming we would implement a bottom-up approach where we calculate the minimum coins for a value of 1 and build up to the final result for amount N. The algorithm would store the solutions to the problems in a memoization table.

W(n) = O(nk)
S(n) = O(nk)



- **3a.**






- **3b.**






- **3c.**



