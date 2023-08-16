# Algorithms
design and analysis of algorithms

**Lab 1:**
1.	Write a program to find* GCD *of two numbers using differential Algorithms	
2.	Write a program to implement *string matching* using Brute force
3.	Write a program to implement *Merge Sort*
4.	Write a program to implement *Quick Sort*	
5.	Write a program to obtain minimum cost spanning tree using *Prim’s Algorithm*
6.	Write a program to obtain minimum cost spanning tree using *Kruskal’s Algorithm*	

**Lab 2:**
7.	Write a program to obtain shortest path using *Djikstra’s algorithm*
8.	Write a program to obtain shortest path using *Floyds algorithms	*
9.	Write a program to compute *Transitive closure* using *Warshall’s Algorithm	*
10.	Write a program to implement *Topological sorting*
11.	Write a program to implement *Subset Sum problem *using Backtracking
12.	Write a program to implement *N Queens problem* using Backtracking

Explainations:

1. **Dijkstra's Algorithm:**
   - **Explanation:** Dijkstra's algorithm is used to find the shortest path from a single source vertex to all other vertices in a weighted graph.
   - **Time Complexity:** O(V^2) for the basic implementation with an adjacency matrix. With a priority queue, it can be reduced to O(V + E * log(V)), where V is the number of vertices and E is the number of edges.

2. **Floyd's Algorithm:**
   - **Explanation:** Floyd's algorithm finds the shortest paths between all pairs of vertices in a weighted graph.
   - **Time Complexity:** O(V^3), where V is the number of vertices. This is due to the triple nested loop that iterates through all vertices for finding shortest paths.

3. **Warshall's Algorithm:**
   - **Explanation:** Warshall's algorithm computes the transitive closure of a directed graph, determining if there's a path between any two vertices.
   - **Time Complexity:** O(V^3), where V is the number of vertices. Similar to Floyd's algorithm, the triple nested loop contributes to the time complexity.

4. **Topological Sorting:**
   - **Explanation:** Topological sorting is used to linearly order the vertices of a directed acyclic graph (DAG) based on their dependencies.
   - **Time Complexity:** O(V + E), where V is the number of vertices and E is the number of edges. This is because each vertex and edge is processed once.

5. **Subset Sum Problem using Backtracking:**
   - **Explanation:** This algorithm solves the subset sum problem, finding whether there exists a subset of given integers that adds up to a target sum.
   - **Time Complexity:** Exponential, worst case O(2^N), where N is the number of elements in the input set. Backtracking explores all possible combinations.

6. **N Queens Problem using Backtracking:**
   - **Explanation:** The N Queens problem aims to place N queens on an N×N chessboard in such a way that no two queens threaten each other.
   - **Time Complexity:** Exponential, worst case O(N!), where N is the number of queens. Backtracking explores all possible configurations.
