# Lab 02: Asymptotic Analysis and Algorithm Running Times
Jonah Dean
Work with your Project 1 team to complete the exercises found in `exercises.pdf`. Put your solutions and explanations below. When you are finished, commit and push your repo.

# Part 1:

## Problem 1.1
<!-- Your solution for Problem 1.1 goes here --> 
Looking at each summand, we have 3n^2, which turns into On^2 by dropping constants, 15n turns into O(n) by dropping constants, and 100 turns into O(1) by dropping constants. Using the max sum rule we have 3n^2 + 15n + 100 is O(n^2). Since 3n^2 grows faster than O(n) and 1 an n grows larger.

## Problem 1.2
<!-- Your solution for Problem 1.2 goes here -->
Looking at each summand, we have 4*2^n, which turns into O(2^n) by dropping constants 8n^5 turns into n^5 by dropping constants. Using the sum is max rule, we conclude that 4x2^n + 8n^5 is O(2^n), because O(2^n) eventually grow faster than n^5.


# Part 2:

## Algorithm A
<!-- Your solution for Algorithm A goes here -->
1. T(n) = 2n^2 + n + 2
2. 0(n^2)

## Algorithm B
<!-- Your solution for Algorithm B goes here -->
1. T(n) = 4(log2​n) + 7
2. O(logn)
# Part 3:



## Reflection
<!-- Your reflection goes here -->
1. I think that the sum/max rule feels the least intuitive to me because I understand that you take the largest-growing term. However, it can sometimes be confusing to see why the smaller terms can basically be ignored when determining the Big-O bound.
2. I found the algorithm for B to be the most challenging because it was hard for me to recognise what should be included inside the log and what should be outside it. I was able to figure it out after going back through the notes and looking at how the log works.
3. The only thing I can think of is if we got a few minutes during lab or in class to discuss with each other for our groups on what we need to do for the projects would be cool but not absolutly necessary.
