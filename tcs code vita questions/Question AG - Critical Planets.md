# Question AG — Critical Planets

## Problem Description

You are given an undirected graph of N planets connected by M paths.

A path is critical if removing it disconnects two previously connected parts of the system. Both endpoints of every critical path are called critical planets.

Return all critical planets in ascending order. If there are none, print -1.

## Input

M N
u1 v1
u2 v2
...
uM vM

## Output

Print every critical planet in ascending order, one per line, or -1 if there are none.

## Constraints

M <= 10000
N <= 7000

## Example

Input
7 6
0 2
0 1
1 2
2 3
4 5
3 4
3 5

Output
2
3
