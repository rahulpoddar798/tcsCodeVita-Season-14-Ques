# Question W — Counting Rock Samples

## Problem Description

You are given the sizes of S rock samples and R query ranges. For every inclusive range [L, R], count the samples whose sizes satisfy L <= size <= R.

## Input

S R
sample1 sample2 ... sampleS
L1 R1
L2 R2
...
LR RR

## Output

For every range, print the number of samples inside it.

## Constraints

10 <= S <= 10000
1 <= R <= 1000000
1 <= sampleSize <= 1000

## Example

Input
10 2
345 604 321 433 704 470 808 718 517 811
300 350
400 700

Output
2
4
