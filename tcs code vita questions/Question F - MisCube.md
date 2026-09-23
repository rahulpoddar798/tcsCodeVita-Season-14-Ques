# Question F — MisCube

## Problem Description

A Rubik's Cube has six faces: Top, Front, Down, Back, Left, and Right. Each face is a 2 x 2 square, giving 24 indexed facelet positions.

The cube uses six colours represented by lowercase letters, but the arrangement is not necessarily the standard solved arrangement. A single corner piece has been twisted, and the cube may also have been shuffled by a small number of valid cube moves.

Determine the three colours belonging to the twisted corner and print them in alphabetical order.

## Constraints

a <= character used to represent colour <= z
0 < moves required to solve the cube < 5

## Input

A single line containing 24 space-separated characters representing the colours present at the indexed positions of the cube.

## Cube Indexing

Top: 1 2 on the first row, 3 4 on the second row.
Front: 5 6 on the first row, 7 8 on the second row.
Down: 9 10, 11 12, 13 14, 15 16 from top to bottom.
Left: 17 18 on the first row, 19 20 on the second row.
Right: 21 22 on the first row, 23 24 on the second row.

## Output

Print the three letters representing the colours of the twisted corner in alphabetical order.

## Example 1

Input

y y r y b r r r w w w w o o o o b y b b g g g g

Output

bry

## Example 2

Input

b y y y r g r r g g w w o o w b r b b w o o y g

Output

bry
