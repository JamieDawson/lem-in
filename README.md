Lem-in is an algorithms project from 42 Silicon Valley. 

The aim of this project is to find all the valid paths in a map which can contian up to 9000 connected nodes and send in ants.
There can be infinite amount of ants inside the start of the map and the end of the map.But all the rooms in between can only contain one ant at a time.

I implemented [Edmans Karp](https://en.wikipedia.org/wiki/Edmonds%E2%80%93Karp_algorithm) to find all the valid paths.

I then used another algorithm to take the valid paths from smallest to largest and and 
determine how many of them I should use to get all the ants to the end of the map as quickly as possible.

