# Question AI — Farming Figures

## Problem Description

You are given N sticks of varying lengths.

Determine the maximum number of sticks that can be selected and arranged to form a polygon with positive area.

A valid polygon must have at least 3 sides. You may choose any subset of the given sticks and arrange the chosen sticks in any order.

If no polygon can be formed, return 0.

## Input

The first line contains N.

The second line contains N space-separated positive integers representing stick lengths.

## Output

Return the maximum possible number of sides of a polygon that can be formed.

Return 0 if no polygon can be formed.

## Constraints

- 1 <= N <= 100
- Each stick length is less than 100

## Examples

### Example 1

Input
```
3
1 1 1
```

Output
```
3
```

### Example 2

Input
```
4
1 2 3 6
```

Output
```
0
```

## Source

TCS CodeVita 2018 — original Coding Arena question. Source archive: https://www.scribd.com/document/420582066/TCS-Codevita-2018-Question-paper
