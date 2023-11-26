# Graph-ADT-and-Algorithms

## ADT Implementation

Design and implement an `abstract data type directed graph` and a function for reading a directed graph from a text file. The vertices will be specified as integers from 0 to n-1, where n is the number of vertices. Edges may be specified by the two endpoints (by the source and target). Additionally, create a map that associates to an edge an integer value (a cost).

Required operations:
- get the number of vertices;
- parse (iterate) the set of vertices;
- given two vertices, find out whether there is an edge from the first one to the second one;
- get the in degree and the out degree of a specified vertex;
- parse (iterate) the set of outbound and inbound edges of a specified vertex;
- retrieve or modify the information (the integer) attached to a specified edge;
- add and remove an edge, add and remove a vertex; 
- make an exact copy of the graph, so that the original can be then modified independently of its copy;
- read the graph from a text file (as an external function); 
- write the graph from a text file (as an external function); 
- create a random graph with specified number of vertices and of edges (as an external function).

## Breadth First Traversal

Write a program that finds the `connected components` of an undirected graph using a `breadth-first traversal` of the graph.

## Floyd Warshall

Write a program that, given a graph with costs that has no negative cost cycles and two vertices, finds a `lowest cost walk` between the given vertices. The program shall use the `Floyd-Warshall algorithm`.

## Directed Acyclic Graph

Write a program that, given a graph with costs, does the following:
- verify if the corresponding graph is a `DAG` and performs a `topological sorting` of the activities using the algorithm based on `predecessor counters`;
- if it is a DAG, finds a `highest cost path` between two given vertices, in O(m+n).

## Vertex Cover

Given an undirected graph, find a `vertex cover` covering of edges by vertices with no more than twice the optimal number of vertices in O(n+m) time.
