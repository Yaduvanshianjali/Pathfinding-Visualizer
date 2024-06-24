A pathfinding visualizer made in Python and Pygame. This project aims to provide a fun and interactive way to learn about popular pathfinding algorithms such as Dijkstra's, A* ,Bfs,Dfs and Greedy Bfs.
supported Algorithms
The following pathfinding algorithms are currently supported in this visualizer:

Depth First Search (DFS): A traversal-based algorithm that goes as far as possible along each branch before backtracking. Not commonly used for pathfinding.
Breadth First Search (BFS): A traversal-based algorithm that explores all neighbors of a node before moving on to the next level. Guaranteed to find the shortest path in unweighted graphs.
Greedy Best First Search: A heuristic search algorithm that prioritizes visiting nodes closest to the goal. Not guaranteed to find the shortest path, but often faster.
A* Search: A heuristic search algorithm that combines the strengths of BFS and greedy best first search. Efficient for many types of graphs.
Dijkstra's Search: A shortest path algorithm that uses a priority queue to prioritize visiting nodes with the smallest known cost. Guaranteed to find the shortest path in weighted graphs.
Each algorithm uses a different approach to finding the shortest path between two points on a graph. Choose the one that best fits your use case and watch it in action.
