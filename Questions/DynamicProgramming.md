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
