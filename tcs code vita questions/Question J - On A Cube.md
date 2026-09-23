# Question J — On A Cube

## Problem Description

A solid cube has dimensions 10 x 10 x 10. A beetle starts at a point on the surface and must visit a sequence of honey spots in the given order. The bottom face is inaccessible.

For two consecutive points:
- If both points lie on the same face, the beetle travels along an arc subtending 60 degrees at the centre of the corresponding circle.
- If they lie on different faces, the beetle takes the shortest path along the cube's surface without using the bottom face.

Round each individual segment distance to two decimal places, then return the sum.

## Input

The first line contains N. The following input gives the N points using three-dimensional coordinates.

## Output

Print the total distance with exactly two decimal places.

## Constraints

2 <= N <= 10
Coordinates satisfy 0 <= x,y,z <= 10.
No point lies on the bottom face or on an edge of the cube.

## Example 1

Input

3
1,1,10,2,1,10,0,5,9

Output

6.05

## Example 2

Input

3
1,1,10,2,1,10,0,1,9

Output

4.05
