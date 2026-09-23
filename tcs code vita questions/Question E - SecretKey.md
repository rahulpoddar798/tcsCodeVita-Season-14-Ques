# Question E — SecretKey

## Problem Description

You are given an N x M grid of English letters. A secret key is a word of length T.

The first character may start at any cell. Every next character must be reached by moving exactly one cell up, down, left, or right. Diagonal moves are not allowed, and no cell may be visited more than once.

For each time position t, a clue specifies a rectangular sub-grid in which the character at time t cannot be located.

Print the key if exactly one valid key exists. Otherwise print Not enough clues. If a clue excludes the entire grid for a time position, also print Not enough clues.

## Constraints

1 <= N, M <= 25
1 <= T <= 25
1 <= I <= 30

The grid contains English letters in any case.

## Input

The first line contains N M.
The next N lines contain M space-separated letters.
The next line contains T.
The next line contains I.
Each clue consists of an integer t followed by x1 y1 x2 y2 describing the excluded rectangle.

## Output

Print the uniquely determined secret key, or Not enough clues.

## Example 1

Input

4 4
A b c D
e F g h
i J k l
m n o P
4
8
1
1 1 1 2
1
1 1 4 1
1
2 1 4 4
1
2 4 4 4
2
1 1 4 3
3
1 1 4 3
3
3 1 4 4
4
1 1 4 3

Output

cDhl

## Example 2

Input

3 3
v a i
s h n
a v i
3
2
1
1 1 2 2
3
2 1 3 3

Output

Not enough clues

## Example 3

Input

3 3
a d j
a c e
n c y
3
2
1
1 1 2 2
3
1 1 3 3

Output

Not enough clues
