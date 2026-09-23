# Question H — Football League

## Problem Description

You are given the names of N football teams and the results of M matches.

For every team, maintain Points, Goals For, Goals Against, and Goal Difference.

Scoring:
- A win gives 2 points.
- A draw gives 1 point to each team.
- A loss gives 0 points.

Rank teams using:
1. Higher points.
2. If tied, higher goal difference.
3. If still tied, higher goals scored.
4. If still tied, team names in case-insensitive alphabetical order.

A pair of teams can play at most twice, and a team cannot play against itself. If the input violates these rules, print Invalid Input.

## Input

The first line contains N.
The second line contains N team names.
The third line contains M.
Each of the next M lines contains T1 T2 S1 S2.

## Output

Print team names in ranking order, one per line, or Invalid Input when the match rules are violated.

## Constraints

1 <= N <= 10000
Goal counts are non-negative.

## Example

Input

5
Spain England France Italy Germany
3
Spain England 3 0
England France 1 1
Spain France 0 2

Output

France
Spain
England
Germany
Italy
