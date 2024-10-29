# graph-analysis

Given an undirected graph, a graph coloring problem is to find an assignment of labels (traditionally referred to as colors) to the vertices (nodes) of a graph such that no two adjacent vertices are of the same color, while using the smallest number of colors possible.

<p align="center">
  <img width="400" height="300" src="https://github.com/shazzad-hasan/graph-analysis/blob/main/images/graph-coloring.png" />
</p>

The project involves processing a set of graph data files, named GraphR1-2024.txt to GraphR5-2024.txt. Each file specifies a graph by listing the vertices of each edge, separated by a space, on each line. The goals of this project are to:

- Construct a graph data structure in Python
- Create DIMACS SAT instances from the graphs
- Use an SAT solver to calculate the chromatic number, clique number, and independence number
- Check if the graph admits an acyclic 2-colouring and acyclic 3-colouring
