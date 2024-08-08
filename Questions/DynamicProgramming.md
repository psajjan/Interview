# Dynamic Programming

# 1D Problems

1. **Number of Ways to Climb N Steps**  
   There are `N` steps in a staircase. Initially, you are at the `0th` stair, and you need to reach the `Nth` stair. Each time, you can climb either one step or two steps. You are supposed to return the number of distinct ways you can climb from the 0th step to the Nth step.
   
2. **Frog Jump**  
   There is a frog on the `1st` step of an `N` stairs long staircase. The frog want to reach the last `Nth` stair. `Height[i]` is the height of the ith stair. If the frog jumps from `ith` stair to the `jth` stair, the energy lost in the jump is given by the absolute value of (`Height[i] - Height[j]`). If the frog is on the ith stair, he can jump either on the `(i+1)th` stair or `(i+2)th` stair. Your task is to find the minimum total energy used by the frog to reach from `1st` stair to `Nth` stair.

3. **Frog Jump with K Distance**  
   Same as problem **Frog Jump** but in this problem when the frog is on the `ith` step, it can make a jump to any of `(i+1)`, `(i+2)`, ..., `(i+K)` stair.

4. **Maximum sum of non-adjacent elements (House Robber - I)**  
   You are given an array/list of `N` integers. You are supposed to return the maximum sum of the subsequence with the constraint that no two elements are adjacent in the given array/list.  
_Note_:  
A subsequence of an array/list is obtained by deleting some number of elements (can be zero) from the array/list, leaving the remaining elements in their original order.

5. **House Robber - II**  
   A robber plans to rob houses along a street. Each house has a certain amount of money hidden. All houses along this street are arranged in a circle. That means the first house is the neighbour of the last one. The condition is that the robber cannot rob two houses that are adjacant to each other.  
   You are given an array of non-negative integers `ARR` representing the amount of money of each house. Your task is to return the maximum amount of money that can be robbed.  
   _Note_:  
   It is possible to rob the same amount of money by looting two different sets of houses. Just print the maximum possible robbed amount, irrespective of sets of houses robbed.

## 2D Problems

1. **Ninja's Training**  
   Ninja is planing this `N` days-long training schedule. Each day, he can perform any one of these three activities. (Running, Fighting Practice or Learning New Moves). Each activity has some merit points on each day. As Ninja has to improve all his skills, he can’t do the same activity in two consecutive days. Can you help Ninja find out the maximum merit points Ninja can earn? You are given a `2D` array `POINTS` of size `N*3` with the points corresponding to each day and activity. Your task is to calculate the maximum number of merit points that Ninja can earn.

2. **Unique Paths in a Grid**  
   You are present at point `A` which is the top-left cell of an `M X N` matrix, your destination is point `B`, which is the bottom-right cell of the same matrix. Your task is to find the total number of unique paths from point `A` to point `B`.In other words, you will be given the dimensions of the matrix as integers `M` and `N`, your task is to find the total number of unique paths from the cell `MATRIX[0][0]` to `MATRIX[M - 1][N - 1]`. To traverse in the matrix, you can either move Right or Down at each step. 

3. **Unique Paths in a Grid - II**  
   Given a `N x M` maze with obstacles, count and return the number of unique paths to reach the right-bottom cell from the top-left cell. A cell in the given maze has a value `-1` if it is a blockage, else 0. From a given cell, you can either move Right or Down. Since the answer can be large, print it modulo 10^9 + 7.

4. **Minimum Path Sum in Grid**  
   You are given a `N x M` grid. Each cell in the grid has some cost associated with it. Find a path from top left `(0,0)`to the bottom right `(N-1, M-1)` which minimizes the sum of the cost of all the cells along the path. You need to tell the minimum sum of that path. You can only move down or right at any point in time.

5. **Triangle**  
   You are given a triangular array/list. Your task is to return the minimum sum path to reach from the top to the bottom row. The triangle array will have `N` rows and the `ith` row, where `0 <= i < N` will have `i + 1` elements. You can move only to the adjacent number of row below each step. For example, if you are at index `j` in row `i`, then you can move to `j` or `j + 1` index in row `i + 1` in each step.

6. **Maximum Path Sum in a Matrix**  
   You have been given an `N x M` matrix filled with integer numbers, find the maximum sum that can be obtained from a path starting from any cell in the first row to any cell in the last row. From a cell in a row, you can move to another cell directly below that row, or diagonally below left or right.

## 3D Problems

1. **Chocolate Pickup**  
   Ninja has a grid of size `R x C`. Each cell of the grid contains some chocolates. Ninja has two friends Alice and Bob, and he wants to collect as many chocolates as possible with the help of his friends. Initially, Alice is in the top-left position `(0, 0)`, and Bob is in the top-right place `(0, C - 1)` in the grid. Each of them can move from their current cell to the cells just below them. When anyone passes from any cell, he will pick all chocolates in it, and then the number of chocolates in that cell will become zero. If both stay in the same cell, only one of them will pick the chocolates in it. If Alice or Bob is at `(i, j)` then they can move to `(i + 1, j), (i + 1, j - 1) or (i + 1, j + 1)`. They will always stay inside the grid. Your task is to find the maximum number of chocolates Ninja can collect with the help of his friends by following the above rules.

## DP on Subsequences

1. **Subset Sum Equal To Target**
2. **Subset Partition With Equal Sum**
3. **Subset Partition With Minimum Absolute Sum Diff**
4. **Unbounded Kapsack**
5. **Rod Cutting Problem**
6. 

## DP on Strings

## Partition DP
