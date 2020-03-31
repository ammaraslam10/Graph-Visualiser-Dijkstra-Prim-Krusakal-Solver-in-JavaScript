# Graph-Visualiser-Dijkstra-Prim-Krusakal-Solver-in-JavaScript
A simple code written in JS that allows for the creation of directed and undirected nodes in a graph (with weights), Dijkstra's algorithm for shortest path and Kruskal or Prim to remove cycles can then be applied to the Graph. It uses the ProcessingJs library to draw the nodes and the GUI elements.

Usage:
- Click "Add Nodes" to add random nodes that will spawn in random locations. All nodes have a unique number written on them.
- Clicking on a node selects it (clicking outside will deselect it), Once a node is selected, another node can be selected to make an edge between the two. A dot on the edge will represent an edge. To make it directed, an edge from A to B and then B to A needs to be added.
- At top, the source and the destination nodes can be selected (by doing +1 till your node comes), If you dont want to keep +1'ing and type the source and destination directly (not sure why you'd want that), text fields at the bottom are present.
- Similarly, when an edge is selected, you can +1 the weight, like before, you'd need to change both A to B and B to A in the case of a directed graph.
- Finally, clicking on the buttons that label the algorithms will run them, for Prim and Kruskal, the graph is connverted automatically to a directed graph (the reverse direction is given the same weight) and the algorithm is run.
- You can input the weights through the table as well, all inputs are automatically updated in the GUI once the update button at the bottom is clicked.
- Infinity will be a fixed value, you can give make it anything you like but make sure you do that before making your nodes.

I'm using an adjacency matrix and copying the 2d arrays a lot so it is by no means efficient :)
