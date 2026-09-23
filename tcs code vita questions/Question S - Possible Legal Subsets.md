# Question S — Possible Legal Subsets

## Problem Description

You are given N unique strings. Form all possible subsets while preserving their original relative order.

Rank the subsets as follows:
1. The empty subset has rank 1.
2. Subsets with fewer elements receive higher rank.
3. Among subsets of equal size, use the original input order to determine ranking.

Given rank R, return the subset having that rank.

## Input

N
R
s1,s2,...,sN

## Output

Return the subset corresponding to rank R.

## Constraints

1 <= N <= 100
1 <= R <= 10^18
All strings are unique.

## Example

Input
2
4
a,b

Output
a,b
