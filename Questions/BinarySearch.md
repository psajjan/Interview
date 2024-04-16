# Basic
1. **Binary search implementation | Recursive | Iterative**
2. **Implement Lower bound and Upper bound of a given number**  
   Given a sorted array of N integers and an integer x, write a program to find the lower bound of x.
   Given a sorted array of N integers and an integer x, write a program to find the upper bound of x.
3. **Floor and Ceil in sorted array**  
   You’re given an sorted array arr of n integers and an integer x. Find the floor and ceiling of x in arr[0..n-1].  
   The floor of x is the largest element in the array which is smaller than or equal to x.  
   The ceiling of x is the smallest element in the array greater than or equal to x.
4. **Count occurances of a given number in a sorted array.**  
   You are given a sorted array containing N integers and a number X, you have to find the occurrences of X in the given array.
5. **First and Last Occurrences in Array**  
   Given a sorted array arr of n integers and a target value k. Write a program to find the indices of the first and the last occurrences of the target value. If the target is not found then return -1 as indices.

# Rotated Array
1. **Search element in rotated array - I** <br />
   Given an integer array arr of size N, sorted in ascending order (with distinct values) and a target value k. The array is rotated at some pivot point unknown to you. Find the index at which k is present and if k is not present return -1.  
   [Solution](https://takeuforward.org/data-structure/search-element-in-a-rotated-sorted-array)
2. **Search element in rotated array - II** <br />
   Given an integer array arr of size N, sorted in ascending order (may contain duplicate values) and a target value k. The array is rotated at some pivot point unknown to you. Return True if k is present and otherwise, return False.  
   [Solution](https://takeuforward.org/arrays/search-element-in-rotated-sorted-array-ii)
3. **Minimum in rotated sorted array**  
   Given an integer array arr of size N, sorted in ascending order (with distinct values). The array is rotated between 1 to N times which is unknown. Find the minimum element in the array.  
   [Solution](https://takeuforward.org/data-structure/minimum-in-rotated-sorted-array)
4. **Number of times array is rotated**  
   Given an integer array arr of size N, sorted in ascending order (with distinct values). The array is rotated between 1 to N times which is unknown. Find how many times the array has been rotated.  
   [Solution](https://takeuforward.org/arrays/find-out-how-many-times-the-array-has-been-rotated)

# Search element
1. **Search single element in sorted array**  
   Given an array of N integers. Every number in the array except one appears twice. Find the single number in the array.  
   [Solution](https://takeuforward.org/data-structure/search-single-element-in-a-sorted-array)
2. **Peak element in array**  
   Given an array of length N. Peak element is defined as the element greater than both of its neighbors. Formally, if ‘arr[i]’ is the peak element then ‘arr[i – 1]’ < ‘arr[i]’ and ‘arr[i + 1]’ < ‘arr[i]’. Find the index(0-based) of a peak element in the array. If there are multiple peak numbers, return the index of any peak number.  
   Note: For the first element, the previous element should be considered as negative infinity. For the last element, the next element should be considered as negative infinity.  
   [Solution]()

# Mathematical
1. **Finding Sqrt of a number**  
   You are given a positive integer n. Your task is to find and return its square root. If ‘n’ is not a perfect square, then return the floor value of ‘sqrt(n)’.  
   Note: The question explicitly states that if the given number, n, is not a perfect square, our objective is to find the maximum number, x, such that x squared is less than or equal to n (x*x <= n). In other words, we need to determine the floor value of the square root of n.  
   [Solution](https://takeuforward.org/binary-search/finding-sqrt-of-a-number-using-binary-search)
2. **Nth Root of a Number**  
   Given two numbers N and M, find the Nth root of M. The nth root of a number M is defined as a number X when raised to the power N equals M. If the ‘nth root is not an integer, return -1.  
   [Solution](https://takeuforward.org/data-structure/nth-root-of-a-number-using-binary-search)
3. **Find the Smallest Divisor Given a Threshold**  
   You are given an array of integers 'arr' and an integer i.e. a threshold value 'limit'. Your task is to find the smallest positive integer divisor, such that upon dividing all the elements of the given array by it, the sum of the division's result is less than or equal to the given threshold value.  
   [Solution](https://takeuforward.org/arrays/find-the-smallest-divisor-given-a-threshold)
4. **Median of Two Sorted Arrays of different sizes**  
   Given two sorted arrays arr1 and arr2 of size m and n respectively, return the median of the two sorted arrays. The median is defined as the middle value of a sorted list of numbers. In case the length of the list is even, the median is the average of the two middle elements.  
   [Solution](https://takeuforward.org/data-structure/median-of-two-sorted-arrays-of-different-sizes)
5. **K-th Element of two sorted arrays**  
   Given two sorted arrays of size m and n respectively, you are tasked with finding the element that would be at the kth position of the final sorted array.  
   [Solution](https://takeuforward.org/data-structure/k-th-element-of-two-sorted-arrays/)
6. **K-th Missing Positive Number**  
   You are given a strictly increasing array `vec` and a positive integer `k`. Find the `kth` positive integer missing from `vec`.  
   [Solution](https://takeuforward.org/arrays/kth-missing-positive-number)

# Find minimum (Indirect Binary Search)
1. **Allocate Minimum Number of Pages**  
   Given an array `arr` of integer numbers, `arr[i]` represents the number of pages in the `i-th` book. There are a `m` number of students, and the task is to allocate all the books to the students. Allocate books in such a way that:
   Each student gets at least one book.
   Each book should be allocated to only one student.
   Book allocation should be in a contiguous manner.
   You have to allocate the book to `m` students such that the maximum number of pages assigned to a student is minimum. If the allocation of books is not possible, return -1.  
   [Solution](https://takeuforward.org/data-structure/allocate-minimum-number-of-pages)
2. **Minimum days to make M bouquets**  
   You are given ‘N’ roses and you are also given an array ‘arr’  where ‘arr[i]’  denotes that the ‘ith’ rose will bloom on the ‘arr[i]th’ day. You can only pick already bloomed roses that are adjacent to make a bouquet. You are also told that you require exactly ‘k’ adjacent bloomed roses to make a single bouquet. Find the minimum number of days required to make at least ‘m’ bouquets each containing ‘k’ roses. Return -1 if it is not possible.  
   [Solution](https://takeuforward.org/arrays/minimum-days-to-make-m-bouquets)
3. **Capacity to Ship Packages within D Days**  
   You are the owner of a shipment company. You use conveyor belts to ship packages from one port to another. The packages must be shipped within `d` days. The weights of the packages are given in an array `arr` of weights. The packages are loaded on the conveyor belts every day in the same order as they appear in the array. The loaded weights must not exceed the maximum weight capacity of the ship. Find out the least-weight capacity so that you can ship all the packages within `d` days.  
   [Solution](https://takeuforward.org/arrays/capacity-to-ship-packages-within-d-days)
4. **Painter’s Partition Problem**  
   Given an array/list of length ‘N’, where the array/list represents the boards and each element of the given array/list represents the length of each board. Some ‘K’ numbers of painters are available to paint these boards. Consider that each unit of a board takes 1 unit of time to paint. You are supposed to return the area of the minimum time to get this job done of painting all the ‘N’ boards under the constraint that any painter will only paint the continuous sections of boards.  
   [Solution](https://takeuforward.org/arrays/painters-partition-problem)
5. **Minimise Maximum Distance between Gas Stations**  
   You are given a sorted array ‘arr’ of length ‘n’, which contains positive integer positions of ‘n’ gas stations on the X-axis. You are also given an integer ‘k’. You have to place ‘k’ new gas stations on the X-axis. You can place them anywhere on the non-negative side of the X-axis, even on non-integer positions. Let ‘dist’ be the maximum value of the distance between adjacent gas stations after adding k new gas stations. Find the minimum value of ‘dist’.  
   Note: Answers within 10^-6 of the actual answer will be accepted. For example, if the actual answer is 0.65421678124, it is okay to return 0.654216. Our answer will be accepted if that is the same as the actual answer up to the 6th decimal place.  
   [Solution](https://takeuforward.org/arrays/minimise-maximum-distance-between-gas-stations)
6. **Aggressive Cows**  
   You are given an array ‘arr’ of size ‘n’ which denotes the position of stalls. You are also given an integer ‘k’ which denotes the number of aggressive cows. You are given the task of assigning stalls to ‘k’ cows such that the minimum distance between any two of them is the maximum possible. Find the maximum possible minimum distance.  
   [Solution](https://takeuforward.org/data-structure/aggressive-cows-detailed-solution)
8. **Koko Eating Bananas**  
   A monkey is given `n` piles of bananas, whereas the `ith` pile has `a[i]` bananas. An integer `h` is also given, which denotes the time (in hours) for all the bananas to be eaten. Each hour, the monkey chooses a non-empty pile of bananas and eats `k` bananas. If the pile contains less than `k` bananas, then the monkey consumes all the bananas and won’t eat any more bananas in that hour. Find the minimum number of bananas `k` to eat per hour so that the monkey can eat all the bananas within `h` hours.  
   [Solution](https://takeuforward.org/binary-search/koko-eating-bananas)
9. **Split Array - Largest Sum**  
   Given an integer array `A` of size `N` and an integer `K`. Split the array `A` into `K` non-empty subarrays such that the largest sum of any subarray is minimized. Your task is to return the minimized largest sum of the split. A subarray is a contiguous part of the array.  
   [Solution](https://takeuforward.org/arrays/split-array-largest-sum)




















   
