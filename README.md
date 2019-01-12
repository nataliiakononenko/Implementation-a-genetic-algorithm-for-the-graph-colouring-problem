# Implementation-a-genetic-algorithm-for-the-graph-colouring-problem


For testing of the application, graph with six vertices and nine edges is used. 
Nodes don’t have a consistent number of edges: a node can have from 2 to 4 edges. 
In the program colours are represented simply by numbers: “0”, “1” and “2”.

•	“Vertex” class represents nodes. It contains an index and colour. 
•	“Edge” represents edges between nodes. Each edge has a start and an end indexes that indicates which two cities it connects. 
•	“Graph” class connects all the vertices and edges, and creates an entity that represents an overall structure. A very important attribute of “Graph” is fitness which represents the number of edges that are not satisfied in a given graph.
