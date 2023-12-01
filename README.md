# Shortest Time Using Dijkstra's Algorithm

This repository contains code that efficiently calculates the shortest distance between every pair of nodes in a graph. It starts at a designated start node and ends at a target end node.

<h2>How It Works:</h2>

The code uses a breadth-first search approach to traverse the graph and calculate distances. Here's a breakdown of the process:
It initializes an empty dictionary called path, which stores the shortest distances. Initially, all distances are set to 0.
The code iteratively explores the graph using a queue data structure. It starts with the designated start node and adds it to the queue.
The while loop continues to process nodes in the queue until there are no more nodes left in the queue, or until there is only one node left before removal.
During this traversal, the code calculates the shortest distance between nodes and updates the path dictionary accordingly.
The adj_node dictionary keeps track of adjacent nodes that were not previously visited but can now be explored through these calculated paths.

<h2>Usage:</h2>

To find the shortest distance between each pair of nodes in your graph, you can use the provided function. Here's how to use it:

```python
# Initialize dictionaries for path and adjacent nodes
path = {}
adj_node = {}

# Call the function to calculate shortest distances
shortest_distance_finder(graph, start_node, end_node, path, adj_node)
```
This code facilitates efficient exploration of a graph to discover and determine the shortest paths between nodes.
