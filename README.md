# Efficient Graph Algorithms

For a given amount of nodes and a max capacity, a random generator creates a strongly connected, max planar, directed graph, which contains the backward edge to every existing edge.

The following algorithms can be applied to the created graph:
* Ford-Fulkerson (DFS)
* Edmonds-Karp (BFS)
* Dinic
* Preflow-Push

The test environment is parameterized with a sequence of triples (number of instances, node count, max capacity). For each triple, as many instances with this number of nodes and this max capacity are generated as the first value in the triple indicates. Each algorithm is applied to each instance.
