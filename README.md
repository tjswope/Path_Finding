<h1>Path Finding</h1>

Path Finding, or search, is an integral part of AI. It helps in problem solving across a wide variety of domains where a solution isn’t immediately clear. You will implement several graph search algorithms with the goal of solving bi-directional and tri-directional search.


<h3>Breadth First Search</h3>
The Breadth First Search (BFS) algorithm is used to search a graph data structure for a node that meets a set of criteria. It starts at the root of the graph and visits all nodes at the current depth level before moving on to the nodes at the next depth level. When running BFS on the default maze, your algorithm should check 2112 nodes, and construct a path of length 47.
<br><br>
<img src='images/bfs.png' width='400'>

<h3>Depth First Search</h3>
Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.
<br><br>
<img src='images/depth.png' width='400'>

<h3>Greedy Search</h3>
Greedy best-first search is an informed search algorithm where the evaluation function is strictly equal to the heuristic function, disregarding the edge weights in a weighted graph because only the heuristic value is considered. When running greedy on the default maze, your algorithm should check 59 nodes, and construct a path of length 47.
<br><br>
<img src='images/greedy.png' width='400'>

<h3>Dijkstra Search</h3>
Dijkstra's algorithm was conceived by computer scientist Edsger W. Dijkstra in 1956 and published three years later. The difference between Dijkstra and BFS is that with BFS we have a simple FIFO queue, and the next node to visit is the first node that was added in the queue. But, using Dijkstra, we need to pull the node with the lowest cost so far. When all edges have the same length, the two algorithms will look identical. When running Dijkstra's on the default maze, your algorithm should check 2112 nodes, and construct a path of length 47.
<br><br>
<img src='images/bfs.png' width='400'>


<h3>A-Star Search</h3>
A* Search is an informed best-first search algorithm that efficiently determines the lowest cost path between any two nodes in a directed weighted graph with non-negative edge weights. This algorithm is a variant of Dijkstra’s algorithm. A slight difference arises from the fact that an evaluation function is used to determine which node to explore next. When running a-star on the default maze, your algorithm should check 288 nodes, and construct a path of length 47.
<br><br>
<img src='images/astar.png' width='400'>

<h3>Recursive A-Star Search</h3>
A* Search is an informed best-first search algorithm that efficiently determines the lowest cost path between any two nodes in a directed weighted graph with non-negative edge weights. Write this function using recursion. When running recursive a-star on the default maze, your algorithm should check 288 nodes, and construct a path of length 47.
<br><br>
<img src='images/astar.png' width='400'>

<h3>Bidirectional A-Star Search </h3>
Based on the A* algorithm, bidirectional search finds a shortest path from a starting point to an ending point. It runs two simultaneous searches: one forward from the start, and one backward from the end, stopping when the two meet in the middle.  When running recursive a-star on the default maze, your algorithm should check 170 nodes, and construct a path of length 47.
<br><br>
<img src='images/astar.png' width='400'>
