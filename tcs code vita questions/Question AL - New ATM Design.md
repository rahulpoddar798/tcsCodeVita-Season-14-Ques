# Question AL — New ATM Design

## Problem Description

Design an ATM for school students.

The ATM has a limit of N currency notes that it can dispense in one withdrawal. Available denominations are:

- 100
- 200
- 500
- 1000

The ATM should always dispense the **maximum possible number of currency notes** for the requested withdrawal amount.

If the transaction cannot be completed using the available notes and the maximum-note limit, return 0.

## Input

The first line contains N, the maximum number of notes that may be dispensed.

The second line contains the amount to withdraw. The amount is a multiple of 100.

The third line contains the number of available 100-rupee notes.

The fourth line contains the number of available 200-rupee notes.

The fifth line contains the number of available 500-rupee notes.

The sixth line contains the number of available 1000-rupee notes.

## Output

Return the maximum possible number of notes that can be dispensed.

Return 0 if the withdrawal cannot be completed.

## Constraints

- N < 100

## Examples

### Example 1

Input
```
10
1300
10
10
10
10
```

Output
```
10
```

### Example 2

Input
```
5
1700
1
2
2
2
```

Output
```
3
```

## Source

TCS CodeVita 2019. Source: https://willfulcoder.blogspot.com/2019/10/problem-description-automated.html
