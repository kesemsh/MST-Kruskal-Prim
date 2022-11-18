# MST Kruskal Prim
This project was created during Algorithms course in The Academic College of Tel Aviv, Yaffo, 2022.

The aim of the project is to implement a number of solutions to the problem of finding a minimal spreading tree (MST), And to explore And analyze the differences between those solutions.

# Algorithms Implemented
The MST's were calculated by two main algorithms:
1. A kruskal algorithm where sorting is implemented by a quick-sort algorithm and Disjoint Sets (Forest).
  Addition: The user can enter one arc to be removed from the graph.
  If the arc belonged to the MST found with kruskal, It will find a new MST without it.
2. A prim algorithm when the priority queue is implemented by a binary stack.
