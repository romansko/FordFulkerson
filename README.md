# FordFulkerson

The Ford-Fulkerson algorithm is used to compute the maximum flow in a flow network.
It works by finding augmenting paths from the source to the sink and increasing the flow along these paths until no more augmenting paths can be found.

This Javascript interactive demo, demonstrates two methods:

1. **Edmonds-Karp algorithm**. The Edmonds-Karp algorithm is a specific implementation of the Ford-Fulkerson method that uses Breadth-First Search (BFS) to find the shortest augmenting path in terms of the number of edges.
2. **Capacity Scaling algorithm**. The Capacity Scaling algorithm is another variant of the Ford-Fulkerson method that improves efficiency by focusing on paths with large capacities first.

Both the Edmonds-Karp and Capacity Scaling algorithms are designed to improve the efficiency of finding the maximum flow in a network by optimizing the search for augmenting paths.

<br/>

## Interactive Demo

The interactive demo was written in plain `JavaScript`. No external packages are reuqired.

[https://romansko.github.io/FordFulkerson](https://romansko.github.io/FordFulkerson)

<br/>

## Instructions:

* To create a Vertex, **click** anywhere whithin the left canvas.
* To create an Edge, **click** on a vertex and **drag** to another certex while not releasing the mouse.
* **Clicking** on a Vertex will open vertex menu.
* **Source** color is teal, **Sink** color is grey.
* **Clicking** on an Edge will open edge menu.
* To Zoom in/out **scroll** with mouse wheel within the canvas.
* `Random Graph` button will generate a random graph.
* `Clear all` button will delete everything.
* `Clear algorithm` button will reset algorithm, keeping the graph.
* `Maximum Capapcity` button box will set graph's edges maximum capacity.
* `Algorithm select` box will set Edmonds-Karp or Capacity-Scaling algorithm.
* `Play Algorithm` will animate the algorithm.
* The `Speed selector` will set the binking speed. (Will update for each augmenting path).
* `Save current graph` will save the current graph. 
* `Restore saved graph` will restore the last saved graph.

