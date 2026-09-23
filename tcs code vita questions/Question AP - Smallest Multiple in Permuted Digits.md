# Question AP — Smallest Multiple in Permuted Digits

## Problem Description

Given two integers N and d, find the smallest number that is a multiple of d and can be formed by permuting **all digits of N**.

All digit occurrences of N must be used exactly once.

Leading zeroes are allowed while constructing the number, but they are removed from the returned representation.

If no permutation of the digits of N forms a multiple of d, return -1.

## Input

A line containing two space-separated integers N and d.

## Output

Return the smallest valid multiple, without leading zeroes.

If no valid permutation exists, return -1.

## Constraints

- 1 <= N <= 1000000000000
- 1 <= d <= 1000000

## Examples

### Example 1

Input
```
210 2
```

Output
```
12
```

### Example 2

Input
```
1707693158 853684
```

Output
```
513917768
```

### Example 3

Input
```
531 2
```

Output
```
-1
```

## Source

TCS CodeVita 2017. Source: https://willfulcoder.blogspot.com/2019/07/smallest-multiple-in-permuted-digits.html
