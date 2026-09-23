# Question D — MahaKumbh2K25

## Problem Description

You are given a railway network whose station connections can change over time.

The initial network is described by N lines. Each line contains a source station followed by all stations directly connected to it. Connections are bidirectional.

Queries can be of three types:
1. source_station to destination_station — determine whether travel is possible.
2. station1 connects station2 — add a bidirectional connection.
3. station1 disconnects station2 — remove a bidirectional connection.

Some stations may be restricted for trains starting from particular source stations. A train starting at a source station cannot pass through stations listed in its restriction line.

## Constraints

2 <= N, Q, R <= 14

## Input

The first line contains N.
The next N lines describe bidirectional station connections.
The next line contains Q.
The following Q lines contain travel, connect, or disconnect queries.
The next line contains R.
The following R lines contain a source station followed by restricted stations.

## Output

For every travel query, print yes if a valid route exists, otherwise print no.

## Example 1

Input

3
prayagraj varanasi chitrakoot
chitrakoot ayodhya lucknow vindhyachal
sarnath ayodhya chitrakoot kushinagar jaunpur
5
prayagraj to jaunpur
prayagraj connects kushinagar
prayagraj to jaunpur
prayagraj disconnects kushinagar
prayagraj to sarnath
2
chitrakoot jaunpur varanasi
prayagraj ayodhya

Output

yes
yes
yes

## Example 2

Input

3
prayagraj varanasi chitrakoot
chitrakoot ayodhya lucknow vindhyachal
sarnath ayodhya kushinagar jaunpur
5
prayagraj to jaunpur
prayagraj connects kushinagar
prayagraj to jaunpur
prayagraj disconnects kushinagar
prayagraj to sarnath
2
chitrakoot jaunpur varanasi
prayagraj ayodhya

Output

no
yes
no
