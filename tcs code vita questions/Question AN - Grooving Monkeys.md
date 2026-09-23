# Question AN — Grooving Monkeys

## Problem Description

N monkeys stand in a circular formation. Every second, each monkey moves to a new position according to a fixed permutation.

For a permutation `monkeys`, the value `monkeys[i]` specifies the new position of the monkey currently standing at position i.

The same permutation is applied every second.

Determine the first positive number of seconds after which every monkey returns to its original position.

## Input

The first line contains T, the number of test cases.

For each test case:

- The first line contains N.
- The second line contains N integers representing the permutation.

## Output

For each test case, print the first positive time at which all monkeys are again in their initial positions.

## Constraints

- 1 <= T <= 10
- 1 <= N <= 10000

## Example

Input
```
1
6
3 6 5 4 1 2
```

Output
```
6
```

## Source

TCS CodeVita 2019. Source: https://willfulcoder.blogspot.com/2019/10/
