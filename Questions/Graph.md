# Graph

## DFS/BFS

1. **Number of Provinces**  
   Given an undirected graph with `V` vertices. We say two vertices `u` and `v` belong to a single province if there is a path from `u` to `v` or `v` to `u`. Your task is to find the number of provinces.  
   [Solution](https://takeuforward.org/data-structure/number-of-provinces/)
3. **Rotten Oranges : Min time to rot all oranges**  
   You are given an `m x n` grid, where each cell has the following values :<br>
   2  -  represents a rotten orange<br>
   1  -  represents a Fresh orange<br>
   0  -  represents an Empty Cell<br>
   Every minute, if a Fresh Orange is adjacent to a Rotten Orange in any of the 4-directions ( upward, downwards, right, and left ), it becomes Rotten.  
   Return the minimum number of minutes required to turn all Fresh Oranges to Rotten Oranges. If it's not possible, return -1.  
   [Solution](https://takeuforward.org/data-structure/rotten-oranges-min-time-to-rot-all-oranges-bfs/)
5. **Flood Fill**  
   An image is represented by a 2-D array of integers, each integer representing the pixel value of the image. Given a starting coordinate `(sr, sc)` representing the starting pixel (row and column) of the flood fill, and a pixel value `newColor`, `Flood Fill` the image.  
   To perform a `Flood Fill`, start from the starting pixel, go to the pixels that are connected to it in any 4-directions and have the same colour as the starting pixel, plus any pixels connected 4-directionally to those pixels (also with the same colour as the starting pixel), and so on. Replace the colour of all of the aforementioned pixels with the `newColor`.  
   [Solution](https://takeuforward.org/graph/flood-fill-algorithm-graphs/)


## Topological Sort

1. **Implementation**
   * Use DFS with stack
   * Use BFS (Khans Algorithm)
2. **Cycle Detection in Directed Graph**  
   Given a Directed Graph with `V` vertices and `E` edges, check whether it contains any cycle or not. (Use BFS)  
   [Solution](https://takeuforward.org/data-structure/detect-a-cycle-in-directed-graph-topological-sort-kahns-algorithm-g-23)
3. **Course Schedule**  
   There are a total of `n` tasks labeled from 0 to n-1. Some tasks may have prerequisites tasks, for example, to do task `0` you have to first finish tasks `1`, which is specified as a pair: `[0, 1]`. Given the total number of `n` tasks and a list of prerequisite pairs of size `m`.  
   1. Find the order of tasks you should pick to finish all tasks. Note: There may be multiple correct orders, you need to return one of them. If it is impossible to finish all tasks, return an empty array.
   2. Return true if it is possible to finish all tasks else return false.
   [Solution](https://takeuforward.org/data-structure/course-schedule-i-and-ii-pre-requisite-tasks-topological-sort-g-24/)
4. **Find Eventual Safe States**  
   A directed graph of `V` vertices and `E` edges is given in the form of an adjacency list `adj`. Each node of the graph is labeled with a distinct integer in the range `0` to `V - 1`. A node is a terminal node if there are no outgoing edges. A node is a safe node if every possible path starting from that node leads to a terminal node. You have to return an array containing all the safe nodes of the graph. The answer should be sorted in ascending order.  
   [Solution](https://takeuforward.org/data-structure/find-eventual-safe-states-bfs-topological-sort-g-25/)
5. **Alien Dictionary**  
   Given a sorted dictionary of an alien language having `N` words which are formed using `k` starting alphabets of a standard dictionary. Find the order of characters in the alien language.  
   Note: Many orders may be possible for a particular test case, thus you may return any valid order.  
   [Solution](https://takeuforward.org/data-structure/alien-dictionary-topological-sort-g-26/)

## Single Source Shortest Path

1. **Shortest Path in Undirected Graph with Unit edges**  
   Given an Undirected Graph having unit weights, find the shortest path from the source node to all other nodes. If a vertex is unreachable from the source node, then return -1 for that vertex.
   _Tip_: You need not push distance into queue, it is enough to just push the node index.  
   [Solution](https://takeuforward.org/data-structure/shortest-path-in-undirected-graph-with-unit-distance-g-28/)
   
2. **Shortest Path in Directed Graph with Unit edges**  
   Given an Directed Graph having unit weights, find the shortest path from the source node to all other nodes. If a vertex is unreachable from the source node, then return -1 for that vertex.
   Solution: Same as in the case of undirected graph

3. **Shortest Path in Directed Acyclic Graph Topological Sort**  
   Given a DAG, find the shortest path from the source to all other nodes in this DAG. You will be given the weighted edges of the graph.  
   [Solution](https://takeuforward.org/data-structure/shortest-path-in-directed-acyclic-graph-topological-sort-g-27/)

4. **Shortest Distance in a Binary Maze**
   Given an `n * m` matrix where each element can either be 0 or 1. You need to find the shortest distance between a given source cell to a destination cell.
   The path can only be created out of a cell if its value is 1. If the path is not possible between the source cell and the destination cell, then return -1.  
   Note: You can move into an adjacent cell if that adjacent cell is filled with element 1. Two cells are adjacent if they share a side.
   In other words, you can move in one of four directions, Up, Down, Left, and Right.  
   _Hint_ : Similar to undirected graph with unit weights.  
   _Tip_: You need not push distance into queue, it is enough to just push the node row and col index.  
   [Solution](https://takeuforward.org/data-structure/g-36-shortest-distance-in-a-binary-maze/)

5. **Minimum Multiplications to Reach End**  
   Given `start`, `end`, and an array `arr` of `n` numbers. At each step, the `start` is multiplied by any number in the array and then a mod operation with 100000 is done to get the new start.
   Your task is to find the minimum steps in which the `end` can be achieved starting from the `start`. If it is not possible to reach the `end`, then return -1.  
   _Tip_: Use BFS. No need of visited array.  
   [Solution](https://takeuforward.org/graph/g-39-minimum-multiplications-to-reach-end/)

7. **Dijkstras Algorithm**  
   Implementation
   * Implement using priority queue  
     _Tip_: Can push multiple entries for a node but use visited array to process nodes only once.  
     [Solution](https://takeuforward.org/data-structure/dijkstras-algorithm-using-priority-queue-g-32/)
   * Implement using ordered set  
     _Tip_: Update an entry in set by first erasing it. To avoid processing a node multiple times, populate the set with all nodes to begin with.
     [Solution](https://takeuforward.org/data-structure/dijkstras-algorithm-using-set-g-33/)

8. **Path With Minimum Effort**  
   You are a hiker preparing for an upcoming hike. You are given heights, a 2D array of size `rows x columns`, where `heights[row][col]` represents the height of the cell (row, col). You are situated in the top-left cell, (0, 0), and you hope to travel to the bottom-right cell, (rows-1, columns-1) (i.e.,0-indexed). You can move up, down, left, or right, and you wish to find a route that requires the minimum effort.  
A route's effort is the maximum absolute difference in heights between two consecutive cells of the route.  
[Solution](https://takeuforward.org/data-structure/g-37-path-with-minimum-effort/)

9. **Number of Ways to Arrive at Destination**  
   You are in a city that consists of n intersections numbered from `0` to `n - 1` with bi-directional roads between some intersections. The inputs are generated such that you can reach any intersection from any other intersection and that there is at most one road between any two intersections. You are given an integer `n` and a 2D integer array `roads` where `roads[i] = [ui, vi, timei]` means that there is a road between intersections `ui` and `vi` that takes `timei` minutes to travel. You want to know in how many ways you can travel from intersection `0` to intersection `n - 1` in the shortest amount of time.  
Return the number of ways you can arrive at your destination in the shortest amount of time. Since the answer may be large, return it modulo 109 + 7.  
[Solution](https://takeuforward.org/data-structure/g-40-number-of-ways-to-arrive-at-destination/)

10. **Cheapest Flight With Atmost K Stops**
    There are `n` cities which are connected by `m` number of flights. You are given an array of flights where `flights[i] = [fromi, toi, pricei]` indicates that there is a flight from city `fromi` to the city `toi` with cost `pricei`. You have also given three integers `src`, `dst`, and `k`. You need to return the cheapest price from `src` to `dst` with at most `k` stops. If there is no such route, return -1.
    * Solve it using BFS with normal queue [Solution](https://takeuforward.org/data-structure/g-38-cheapest-flights-within-k-stops/)
    * Solve it using Dijkstras Algorithm with priority queue
      * Option 1: Always update `dist` and `stops` array [Solution](https://pastebin.com/5cEzXnPJ) [YouTube](https://www.youtube.com/watch?v=vWgoPTvQ3Rw)
      * Option 2: Update `dist` and `stops` array only when distance reduces

