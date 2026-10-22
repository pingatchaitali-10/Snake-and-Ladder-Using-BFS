# Snake-and-Ladder-Using-BFS
Implementation of the Snake and Ladder game using Breadth-First Search (BFS) in Python. The board is represented as a graph, and BFS is used to find the minimum number of dice throws required to reach the final position while considering snakes and ladders. DS Case Study – SPPU Second Year Computer Engineering.

# Snake and Ladder using BFS

## Aim
To implement the Snake and Ladder game using
Breadth-First Search (BFS) to find the minimum
number of dice throws required to reach square 100.

## Description
The Snake and Ladder board is represented as a graph.
Each square represents a vertex, and possible dice
moves represent edges.

BFS explores the board level by level to find the
minimum number of dice throws needed to reach the
destination. Snakes move the player backward, while
ladders move the player forward.

## Data Structures Used
- Graph
- Queue
- Dictionary
- Set

## Algorithm
1. Start from square 1.
2. Insert the starting square into the BFS queue.
3. Explore all possible dice rolls from 1 to 6.
4. Apply a snake or ladder if the player lands on one.
5. Mark each new position as visited.
6. Continue BFS until square 100 is reached.
7. Display the minimum dice throws and the path.

## Time Complexity
O(V + E), where V is the number of squares
and E is the number of possible moves.

## Space Complexity
O(V), for the queue, visited set, and parent map.

## Conclusion
The project demonstrates how BFS finds the
shortest path in an unweighted graph and determines
the minimum number of dice throws needed to
complete the Snake and Ladder game.
