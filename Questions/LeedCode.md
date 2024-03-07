# LeetCode Questions

## Shiran Afergan Playlist

1. **Pairs of songs with total durations divisible by 60 [LC: 1010]**  
  You are given a list of songs where the ith song has a duration of `time[i]` seconds.  
  Return the number of pairs of songs for which their total duration in seconds is divisible by 60.  
  Formally, we want the number of indices `i`, `j` such that `i < j` with `(time[i] + time[j]) % 60 == 0`.
2. **Accounts merge**  
   Given a list of accounts where each element `accounts[i]` is a list of strings, where the first element `accounts[i][0]` is a name, and the rest of the elements are emails representing emails of the account. Now, we would like to merge these accounts. Two accounts definitely belong to the same person if there is some common email to both accounts. Note that even if two accounts have the same name, they may belong to different people as people could have the same name. A person can have any number of accounts initially, but all of their accounts definitely have the same name. After merging the accounts, return the accounts in the following format: the first element of each account is the name, and the rest of the elements are emails in sorted order. The accounts themselves can be returned in any order.
