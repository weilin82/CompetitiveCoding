# Tower Of Hanoi

The problem states that there are 3 pegs A, B and C. Initially there are n disks placed on peg A in increasing order of dimension (radius) that is the disk with smallest radius is at the top and the disk with the largest radius is at the bottom. Our task is to move all the disks from peg A (source) to peg C (destination) using peg B (auxiliary peg) and the following 2 rules:

1. We can move only one disk at a time.
2. A smaller disk must always be placed over a larger disk.


## Input Format :

A single integer denoting the number of disks.

## Output Format :

Display movement of each disk till our goal is achieved.


## Analysis

Let n be the ummber of disks.

If n = 1
        Move single disk from peg A to peg C and stop.
Else
        Move the top (n-1) disks from peg A to peg B using peg C as auxiliary.

Move remaining disks from peg A to peg C.

Move (n-1) disks from peg B to peg C using peg A as auxiliary.