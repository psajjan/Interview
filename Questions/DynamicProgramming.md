# Dynamic Programming

# 1D Problems

1. **Number of Ways to Climb N Steps**  
   There are `N` steps in a staircase. Initially, you are at the `0th` stair, and you need to reach the `Nth` stair. Each time, you can climb either one step or two steps. You are supposed to return the number of distinct ways you can climb from the 0th step to the Nth step.
   
2. **Frog Jump**  
   There is a frog on the `1st` step of an `N` stairs long staircase. The frog want to reach the last `Nth` stair. `Height[i]` is the height of the ith stair. If the frog jumps from `ith` stair to the `jth` stair, the energy lost in the jump is given by the absolute value of (`Height[i] - Height[j]`). If the frog is on the ith stair, he can jump either on the `(i+1)th` stair or `(i+2)th` stair. Your task is to find the minimum total energy used by the frog to reach from `1st` stair to `Nth` stair.

3. **Frog Jump with K Distance**  
   Same as problem **Frog Jump** but in this problem when the frog is on the `ith` step, it can make a jump to any of `(i+1)`, `(i+2)`, ..., `(i+K)` stair. 
