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
4. **Alien Dictionary**  
   Given a sorted dictionary of an alien language having `N` words which are formed using `k` starting alphabets of a standard dictionary. Find the order of characters in the alien language.  
   Note: Many orders may be possible for a particular test case, thus you may return any valid order.  
   [Solution](https://takeuforward.org/data-structure/alien-dictionary-topological-sort-g-26/)
