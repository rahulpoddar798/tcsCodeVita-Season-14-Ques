# Question C — TwoScouts

## Problem Description

Two scouts start from two different towns in an undirected road network. Both must reach a common destination town.

Each scout must follow a simple path, meaning no town is visited more than once. The two paths may not share any town except the common destination.

Find the minimum number of towns visited by the two scouts according to the problem's counting rule. If no valid pair of paths exists, print Impossible.

## Constraints

3 <= N <= 15

## Input

The first line contains N and M, the number of towns and roads.
The next M lines contain two integers a and b describing an undirected road.
The following line contains the two starting towns.
The last line contains the destination town.

## Output

Print the minimum number of towns required by the two paths, or Impossible if no valid pair exists.

## Example 1

Input

14 16
1 2
2 3
3 4
4 5
5 6
6 7
1 8
8 9
9 10
10 7
1 11
11 12
11 13
13 14
14 7
10 11
1 12
7

Output

8

## Example 2

Input

8 9
1 2
2 3
3 4
4 9
5 9
3 6
6 5
1 8
8 6
1 2
5

Output

7

## Note

The published statement contains a counting inconsistency between its wording and Example 1; the example counts the towns before the common destination, while the destination itself is shared.
