# Question G — Digit Pairs

## Problem Description

Given N three-digit numbers, calculate the bit score of each number and determine the number of valid pairs.

For each three-digit number:
1. Find the largest digit and multiply it by 11.
2. Find the smallest digit and multiply it by 7.
3. Add the results.
4. If the result has three digits, ignore the most significant digit.

Two bit scores can form a pair when:
1. They occur at positions that are both odd or both even.
2. Their most significant digits are the same.
3. For any particular most-significant digit, at most two pairs can be formed.

Return the total number of valid pairs.

## Constraints

2 <= N <= 500

Each input number is a three-digit number.

## Input

The first line contains N.
The second line contains N space-separated three-digit integers.

## Output

Print the total number of valid pairs.

## Example 1

Input

8
234 567 321 345 123 110 767 111

Output

3

## Example 2

Input

20
666 231 186 752 821 390 596 316 565 945 794 213 759 846 116 896 263 898 318 972

Output

7
