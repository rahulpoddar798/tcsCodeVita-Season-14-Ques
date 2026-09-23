# Question AR — Continuous Niven Numbers

## Problem Description

In base b, an integer is a Niven number if it is divisible by the sum of its digits when represented in base b.

For example, in base 10, 18 is a Niven number because 18 is divisible by 1 + 8 = 9.

Given a base b and an integer T, find the smallest number L such that:

- L, L+1, ..., L+T-1 are all Niven numbers in base b.
- L-1 is not a Niven number.
- L+T is not a Niven number.

Numbers less than b are considered trivially Niven and are ignored.

## Input

Two space-separated integers b and T.

## Output

Return the smallest such L.

## Constraints

- 2 <= b <= 10
- 1 < T < 7

## Examples

### Example 1

Input
```
10 4
```

Output
```
510
```

### Example 2

Input
```
5 5
```

Output
```
44
```

## Source

TCS CodeVita 2017. Source: https://willfulcoder.blogspot.com/2019/07/
