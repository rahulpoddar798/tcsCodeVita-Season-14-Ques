# Question AO — Book Fair

## Problem Description

There are N stalls in a book fair. Each stall offers a coupon with a given value.

At every stall you can either:

- Collect its coupon, after which you must skip the next K stalls.
- Skip the current stall and move to the next stall.

Determine the maximum total coupon value that can be collected.

## Input

The first line contains N and K.

The next N lines contain one positive integer each, representing the coupon value at that stall.

## Output

Return the maximum possible sum of collected coupon values.

## Constraints

- N < 50
- Each coupon value < 1000

## Example 1

Input
```
10 2
4
5
8
7
5
4
3
4
6
5
```

Output
```
19
```

## Example 2

Input
```
10 2
50
70
40
50
90
70
60
40
70
50
```

Output
```
230
```

## Source

TCS CodeVita 2017. Source: https://willfulcoder.blogspot.com/2019/07/book-fair-code-vita-2017.html
