# Question AE — Railway Station

## Problem Description

You are given N trains. For every train, arrival time a and stoppage duration b are given. The train occupies a platform from a until a + b.

If one train departs exactly when another arrives, they cannot use the same platform.

Return the minimum number of platforms required.

## Input

N
a1 b1
a2 b2
...
aN bN

## Output

Return the minimum number of platforms required.

## Constraints

1 <= N <= 100000
0 <= arrival <= 86400
0 < stoppage <= 86400

## Example

Input
3
10 2
5 10
13 5

Output
2
