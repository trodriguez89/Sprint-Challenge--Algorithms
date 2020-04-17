#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) One while loop makes this O(n)


b) Two loops total, one nested loop indicates that the time complexity is O(n^2)


c) Recursive function, time complexity is O(n)

## Exercise II
My first thought was to go up level by level and keep dropping eggs until you find the level where eggs break, but this would not be minimizing the number of dropped eggs. My next thought would be to instead go in intervals of 10 floors, so starting at the 10th floor, 20th, 30th etc. If it breaks at the 30th floor then we could check from 21-29 to see exactly which floor it broke on. Perhaps this is similar to a binary search? Time complexity would be O(log n)
