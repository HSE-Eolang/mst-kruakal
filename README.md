## Minimum spanning Tree using Kruskal's algorithm 
A minimum spanning tree (MST) or minimum weight spanning tree for a weighted, connected,
undirected graph is a spanning tree with a weight less than or equal to the weight of
every other spanning tree.
The weight of a spanning tree is the sum of weights given to each edge of the spanning tree.
A minimum spanning tree has (V – 1) edges where V is the number of vertices in the given graph.

### To find the MST using the Kruskal's algorithm:

1. Sort all the edges in non-decreasing order of their weight.
2. (Union-Find algorithm) Pick the smallest edge. Check if it forms a cycle with the spanning tree formed so far.    If cycle is not formed, include this edge. Else, discard it.
3. Repeat step no. 2 until there are (V-1) edges in the spanning tree.

#  Example (MST):
                  10
              0--------1
              |  \     |
             6|   5\   |15
              |      \ |
              2--------3

