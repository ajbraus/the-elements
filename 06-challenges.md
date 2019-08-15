# Low Complexity Technical Interview Questions

## Challenge 1 - Find Unique Integer

Given an array of all duplicate integers with 1 unique integer, write a function that finds the unique integer element.

Slow linear search solution
1. Instantiate variable u
1. Iterate through each of the elements
1. Check if u equals any number
1. If el equals u, return and move onto next el
1. If no el is found that equals u, u is the solution

Faster Linear search solution
1. Instantiate variable u
1. Iterate through each of the elements
1. Check if each element is equal to u
1. If el === u then set u equal to null
1. If el !== u then move on
1. Return u after loop ends. U is our

Histogram solution
1. Make a dictionary
1. Loop over array
1. Check if element is a key in the dictionary
1. If not, make a key and increment value
1. If so, increment value +=1
1. Loop over the dictionary and check which is the minimum <2

Very Fast Binary search solution
1. Sort array if unsorted
1. Array will be odd
1. Split it in half
1. Check if right or left of half element is equal to middle element
1. If neither are equal, middle element is the solution
1. If equal on the left, take the right and do it again

[1,1,2,2,3,3,4,4,5,6,6]
[1,1,2,2,3,x,4,4,5,6,6]
[4,4,5,6,6]
[4,4,x,6,6] done


Challenge 2 - Given an array of all unique numbers except for one duplicate, write a function that finds the duplicate. (example: [2, 1, 3, 4, 5, 3] => 3)


Challenge 3 - Given an array a of numbers and a target value t, write a function that finds two elements that sum to t. (example, a[i] + a[j] => t)


Challenge 4 - Given two arrays, determine if both arrays contain exactly the same elements.


Challenge 5 - Given a sorted array of numbers, find the index of the first and last occurrence of a given number. If the given number is not found in the array, report that as well.
