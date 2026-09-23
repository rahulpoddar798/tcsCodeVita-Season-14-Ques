# Question Z — Elections

## Problem Description

A queue of voters is represented by a string containing A, B, and -.

A supporters move only left. B supporters move only right. Neutral voters are influenced by whichever candidate reaches them first. If both candidates reach a neutral voter at exactly the same time, that voter remains neutral.

Determine the election result after all possible influences occur.

## Input

N
S

## Output

A if A receives more votes, B if B receives more votes, or Coalition government if they receive the same number of votes.

## Example

Input
14
-AB-AB---A-

Output
A
