# Algorithm-to-practice
每日算法练习打卡
第一天（2019.3.27）
01.Classical Binary Search
Description
Find any position of a target number in a sorted array. Return -1 if target does not exist.

Example
Example 1:

Input: nums = [1,2,2,4,5,5], target = 2
Output: 1 or 2

Example 2:
Input: nums = [1,2,2,4,5,5], target = 6
Output: -1
oj: https://www.lintcode.com/problem/classical-binary-search/description

提示：大家也许拿到这个题目觉得很简单，但不妨自己写写试试，也许没你想的那么容易呢？



第二天（2019.3.28）
02.Find Peak Element
Description
中文
English
你给出一个整数数组(size为n)，其具有以下特点：

相邻位置的数字是不同的
A[0] < A[1] 并且 A[n - 2] > A[n - 1]
假定P是峰值的位置则满足A[P] > A[P-1]且A[P] > A[P+1]，返回数组中任意一个峰值的位置。

Example
样例 1:
	输入:  [1, 2, 1, 3, 4, 5, 7, 6]
	输出:  1 or 6
	
	解释:
	返回峰顶元素的下标


样例 2:
	输入: [1,2,3,4,1]
	输出:  3

oj:https://www.lintcode.com/problem/find-peak-element/description
注意：这道题是和第一道题是有关系的，在这种特定的条件下，一定不要写出O(n)的解法，面试中也是，只要是搜索的题目，一维的是最优解O(1)或者O(logn)。
