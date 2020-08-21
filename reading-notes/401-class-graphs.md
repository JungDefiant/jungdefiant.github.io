# Graphs

This data structure is made up of vertices or 'nodes' that are connected to other nodes through edges. Each node has one or more neighbors and the number of neighbors they are connected to is known is its degree.

## Undirected vs Directed Graphs
In an undirected graph, none of the nodes are restricted to a specific direction. A node can traverse to any of its neighbors. Meanwhile, a directed graph is composed of nodes that must point to another specific node and the graph moves in a specific direction.

## Connected vs Complete vs Disconnected Graphs
In a complete graph, all of the nodes are connected to each other. In a connected graph, each node is connected to at least one other node. In a disconnected graph, some nodes do not have edges. 

## Acyclic vs Cyclic
In a directed graph's cycle, the graph can be traversed and end up looping around itself. An acyclic graph is a directed graph that does not cycle on itself and a cyclic graph is a directed graph that **does** cycle on itself.
