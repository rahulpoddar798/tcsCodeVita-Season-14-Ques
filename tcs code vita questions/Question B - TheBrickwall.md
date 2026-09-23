# Question B — TheBrickwall

## Problem Description

A plumber needs to install pipelines on a brick wall. To do this, some bricks must be broken to fit the pipes.

There are two types of bricks in the wall:
- Red Bricks (R): Hard to break.
- Green Bricks (G): Easy to break.

The plumber will only break Green Bricks. The wall is represented as an N x N grid, with each brick type and its length specified. For example, 3R means a Red Brick of length 3 unit bricks. The wall also contains a Source (S) where the pipe starts and a Destination (D) where it ends.

Pipes can be laid horizontally or vertically by moving from the current brick to an adjacent Green Brick. Red Bricks cannot be used. Find the minimum number of Green Bricks that must be broken to connect S to D.

## Constraints

3 <= N <= 25

## Input

The first line contains N, the size of the wall (N x N).
The next N lines describe the wall layout using the brick notation.

## Output

Print a single integer: the least number of Green Bricks that need to be broken.

## Example 1

Input

4
3R1D
1R1R1R1G
2G1G1G
2S2R

Output

4

## Example 2

Input

5
3G1R1G
1G1R1G2R
1S1R1G1R1D
2R1G1R1G
5G

Output

7

## Source

TCS CodeVita Season 14 — Mock Question B.
