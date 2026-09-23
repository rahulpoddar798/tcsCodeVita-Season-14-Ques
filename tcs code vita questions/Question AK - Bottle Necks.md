# Question AK — Bottle Necks

## Problem Description

There are N bottles. Bottle i has radius A[i]. When one bottle is enclosed inside another bottle, the inner bottle is no longer visible.

You may put bottle i inside bottle j only when all of these conditions hold:

1. Bottle i is not already enclosed in another bottle.
2. Bottle j does not currently enclose another bottle.
3. A[i] < A[j].

Perform any number of valid operations to minimize the number of visible bottles.

## Input

The first line contains N.

The second line contains N space-separated integers representing the bottle radii.

## Output

Return the minimum possible number of visible bottles.

## Constraints

- 1 <= N <= 100000
- 1 <= A[i] <= 10^18

## Example

Input
```
8
1 1 2 3 4 5 5 4
```

Output
```
2
```

## Source

TCS CodeVita 2019 Round 1, Zone 2. Source: https://discuss.codechef.com/t/any-one-have-codevita-2019-round-1-zone-2-questions/32376
