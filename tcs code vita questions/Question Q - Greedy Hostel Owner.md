# Question Q — Greedy Hostel Owner

## Problem Description

A hostel has N room electricity meters and one central meter. Each room meter is a six-character encrypted reading using letters A through J.

The normal mapping is A=0, B=1, C=2, D=3, E=4, F=5, G=6, H=7, I=8, J=9.

For the higher letters, special adjacent-character rules alter the represented value for patterns such as JA, IB, HC, GD, and FE.

Decode every room meter and calculate the total room consumption.

The owner is GREEDY when the total room consumption is greater than the central-meter reading. If greedy, output the difference roomConsumption - centralReading. Otherwise output INNOCENT.

## Input

N
meter1 meter2 ... meterN
centralReading

## Output

GREEDY followed by the difference, or INNOCENT.

## Example

Input
3
JAABHF JAACJA JAACDA
500

Output
GREEDY
105
