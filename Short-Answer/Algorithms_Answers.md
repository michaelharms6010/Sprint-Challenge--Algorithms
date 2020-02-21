#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(1) - this is constant, will only run once


b) O(n log n) 
for n=1 it runs 0 times, for n=5 it runs 15, for n=20, it runs 100. There is a curve but it's not exponential, so I'm p sure it's O(n log n)


c) O(n) - the function runs ~n times.

## Exercise II

Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

Drop an egg midway up

if it doesn't break, go halfway between the midpoint you just dropped form and the top of the building. Repeat process from this new midpoint.

if it breaks, go halfway between the point you just dropped from and the bottom of the building. repeat this process form this new endpoint.

this is like binary search, and has a time complexity of O(log n)
