# Question I — Sorting Boxes

## Problem Description

You are given N boxes arranged in a row. Each box has a unique weight.

The boxes must be rearranged into increasing order of weight. You may swap any two boxes. The cost of swapping boxes with weights A and B is A x B.

The final arrangement must also satisfy the position constraint involving the heaviest box as specified by the input.

Return the minimum total swapping cost.

## Input

N K
W1 W2 ... WN

## Output

Return the minimum total swapping cost.

## Constraints

N <= 50
Wi <= 1000
All weights are distinct.

## Example

Input

5 2
20 50 30 80 70

Output

3600
