# LeetCode高频知识点
花花酱的讲解，YouTube 博主：Huifeng Guan
## 排序类（Sort）
入门题目：
* Leetcode 148. Sort List
* Leetcode 56. Merge Intervals
* Leetcode 27. Remove elements

进阶题目：
* Leetcode 179. Largest Number
* Leetcode 75. Sort Colors
* Leetcode 215. Kth Largest Element （可以用堆的解法替代）
* Leetcode 4. Median of Two Sorted Arrays

后两题是与快速排序非常相似的快速选择（Quick Select）算法，面试中很常考

## 链表类（Linked List）
基础题目：
* Leetcode 206. Reverse Linked List
* Leetcode 876. Middle of the Linked List

进阶题目:
* Leetcode 160. Intersection of Two Linked Lists
* Leetcode 141. Linked List Cycle (Linked List Cycle II)
* Leetcode 92. Reverse Linked List II
* Leetcode 328. Odd Even Linked List

## 堆（Heap or Priority Queue）、栈（Stack）、队列（Queue）、哈希表类（Hashmap、Hashset）
Queue题目：
* Leetcode 225. Implement Stack using Queues
* Leetcode 346. Moving Average from Data Stream
* Leetcode 281. Zigzag Iterator
* Leetcode 1429. First Unique Number
* Leetcode 54. Spiral Matrix
* Leetcode 362. Design Hit Counter

Stack题目：
* Leetcode 155. Min Stack (follow up Leetcode 716 Max Stack)
* Leetcode 232. Implement Queue using Stacks
* Leetcode 150. Evaluate Reverse Polish Notation
* Leetcode 224. Basic Calculator II (I, II, III, IV)
* Leetcode 20. Valid Parentheses
* Leetcode 1472. Design Browser History
* Leetcode 1209. Remove All Adjacent Duplicates in String II
* Leetcode 1249. Minimum Remove to Make Valid Parentheses
* Leetcode 735. Asteroid Collision

Hashmap/ Hashset题目：
* Leetcode 1. Two Sum
* Leetcode 146. LRU Cache
* Leetcode 128. Longest Consecutive Sequence
* Leetcode 73. Set Matrix Zeroes
* Leetcode 380. Insert Delete GetRandom O(1)
* Leetcode 49. Group Anagrams
* Leetcode 350. Intersection of Two Arrays II
* Leetcode 299. Bulls and Cows
* Leetcode 348 Design Tic-Tac-Toe

Heap／Priority Queue题目：
* Leetcode 973. K Closest Points
* Leetcode 347. Top k Largest Elements
* Leetcode 23. Merge K Sorted Lists
* Leetcode 264. Ugly Number II
* Leetcode 1086. High Five
* Leetcode 88. Merge Sorted Arrays
* Leetcode 692. Top K Frequent Words
* Leetcode 378. Kth Smallest Element in a Sorted Matrix
* Leetcode 295. Find Median from Data Stream （标准解法是双heap，但是SortedDict会非常容易）
* Leetcode 767. Reorganize String
* Leetcode 1438. Longest Continuous Subarray With Absolute Diff Less Than or Equal to Limit (这个题用单调双端队列、TreeMap、双heap都可以)
* Leetcode 895. Maximum Frequency Stack

## 二分法（Binary Search）
显式二分法：
* Leetcode 34. Find First and Last Position of Element in Sorted Array
* Leetcode 33. Search in Rotated Sorted Array
* Leetcode 1095. Find in Mountain Array
* Leetcode 162. Find Peak Element
* Leetcode 278. First Bad Version
* Leetcode 74. Search a 2D Matrix
* Leetcode 240. Search a 2D Matrix II

隐式二分法：
* Leetcode 69. Sqrt(x)
* Leetcode 540. Single Element in a Sorted Array
* Leetcode 644. Maximum Average Subarray II
* Leetcode 528. Random Pick with Weight
* Leetcode 1300. Sum of Mutated Array Closest to Target
* Leetcode 1060. Missing Element in Sorted Array
* Leetcode 1062. Longest Repeating Substring
* Leetcode 1891. Cutting Ribbons
* Leetcode 410. Split Array Largest Sum (与1891类似)

## 双指针（2 Pointer）
背向双指针：(基本上全是回文串的题)
* Leetcode 409. Longest Palindrome
* Leetcode 125. Valid Palindrome (I、II)
* Leetcode 5. Longest Palindromic Substring
* Leetcode 647. Palindromic Substrings

相向双指针：(以two sum为基础的一系列题)
* Leetcode 1. Two Sum (这里使用的是先排序的双指针算法，不同于hashmap做法)
* Leetcode 167. Two Sum II - Input array is sorted
* Leetcode 15. 3Sum
* Leetcode 16. 3Sum Closest
* Leetcode 18. 4Sum
* Leetcode 454. 4Sum II
* Leetcode 277. Find the Celebrity
* Leetcode 11. Container With Most Water
* Leetcode 186 Reverse Words in a String II

同向双指针：（个人觉得最难的一类题，可以参考下TimothyL：Leetcode 同向双指针/滑动窗口类代码模板 https://zhuanlan.zhihu.com/p/390570255）
* Leetcode 283. Move Zeroes
* Leetcode 26. Remove Duplicate Numbers in Array
* Leetcode 395. Longest Substring with At Least K Repeating Characters
* Leetcode 340. Longest Substring with At Most K Distinct Characters
* Leetcode 424. Longest Repeating Character Replacement
* Leetcode 76. Minimum Window Substring
* Leetcode 3. Longest Substring Without Repeating Characters
* Leetcode 1004 Max Consecutive Ones III
* Leetcode 1658 Minimum Operations to Reduce X to Zero

## 宽度优先搜索（BFS）：面试中最常考的
常见的BFS用来解决什么问题？
* 简单图（有向无向皆可）的最短路径长度，注意是长度而不是具体的路径
* 拓扑排序
* 遍历一个图（或者树）

基于树的BFS：不需要专门一个set来记录访问过的节点
* Leetcode 102 Binary Tree Level Order Traversal
* Leetcode 103 Binary Tree Zigzag Level Order Traversal
* Leetcode 297 Serialize and Deserialize Binary Tree （很好的BFS和双指针结合的题）
* Leetcode 314 Binary Tree Vertical Order Traversal

基于图的BFS：（一般需要一个set来记录访问过的节点）
* Leetcode 200. Number of Islands
* Leetcode 133. Clone Graph
* Leetcode 127. Word Ladder
* Leetcode 490. The Maze
* Leetcode 323. Connected Component in Undirected Graph
* Leetcode 130. Surrounded Regions
* Leetcode 752. Open the Lock
* Leetcode 815. Bus Routes
* Leetcode 1091. Shortest Path in Binary Matrix
* Leetcode 542. 01 Matrix
* Leetcode 1293. Shortest Path in a Grid with Obstacles Elimination
* Leetcode 417. Pacific Atlantic Water Flow

拓扑排序：
* Leetcode 207 Course Schedule （I, II）
* Leetcode 444 Sequence Reconstruction
* Leetcode 269 Alien Dictionary
* Leetcode 310 Minimum Height Trees
* Leetcode 366 Find Leaves of Binary Tree

## 深度优先搜索（DFS）：面试中最常考的
常见的DFS用来解决什么问题？
* 图中（有向无向皆可）的符合某种特征（比如最长）的路径以及长度
* 排列组合
* 遍历一个图（或者树）
* 找出图或者树中符合题目要求的全部方案

基于树的DFS：需要记住递归写前序中序后序遍历二叉树的模板
* Leetcode 543 Diameter of Binary Tree (分治)
* Leetcode 124 Binary Tree Maximum Path Sum (分治)
* Leetcode 226 Invert Binary Tree (分治)
* Leetcode 101 Symmetric Tree (回溯 or 分治)
* Leetcode 951 Flip Equivalent Binary Trees (分治)
* Leetcode 236 Lowest Common Ancestor of a Binary Tree (相似题：235、1650) (回溯 or 分治)
* Leetcode 105 Construct Binary Tree from Preorder and Inorder Traversal (分治)
* Leetcode 104 Maximum Depth of Binary Tree (回溯 or 分治)
* Leetcode 987 Vertical Order Traversal of a Binary Tree
* Leetcode 1485 Clone Binary Tree With Random Pointer
* Leetcode 572 Subtree of Another Tree (分治)
* Leetcode 863 All Nodes Distance K in Binary Tree
* Leetcode 1110 Delete Nodes And Return Forest (分治)

二叉搜索树（BST）：
* Leetcode 230 Kth Smallest element in a BST
* Leetcode 98 Validate Binary Search Tree
* Leetcode 270 Cloest Binary Search Tree Value
* Leetcode 235 Lowest Common Ancestor of a Binary Search Tree
* Leetcode 669 Trim a Binary Search Tree (分治)
* Leetcode 700 Search in a Binary Search Tree
* Leetcode 108 Convert Sorted Array to Binary Search Tree (分治)
* Leetcode 333 Largest BST Subtree (与98类似) (分治)
* Leetcode 285 Inorder Successor in BST (I, II)

基于图的DFS: 
* Leetcode 341 Flatten Nested List Iterator (339 364)
* Leetcode 394 Decode String
* Leetcode 51 N-Queens (I II基本相同)
* Leetcode 291 Word Pattern II (I为简单的Hashmap题)
* Leetcode 126 Word Ladder II （I为BFS题目）
* Leetcode 93 Restore IP Addresses
* Leetcode 22 Generate Parentheses
* Leetcode 856 Score of Parentheses
* Leetcode 301 Remove Invalid Parentheses
* Leetcode 37 Sodoku Solver
* Leetcode 212 Word Search II （I, II）
* Leetcode 1087 Brace Expansion
* Leetcode 399 Evaluate Division
* Leetcode 1274 Number of Ships in a Rectangle
* Leetcode 1376 Time Needed to Inform All Employees
* Leetcode 694 Number of Distinct Islands
* Leetcode 131 Palindrome Partitioning

基于排列组合的DFS: 其实与图类DFS方法一致，但是排列组合的特征更明显
* Leetcode 17 Letter Combinations of a Phone Number
* Leetcode 39 Combination Sum（I, II, III相似， IV为动态规划题目）
* Leetcode 78 Subsets （I, II 重点在于如何去重）
* Leetcode 46 Permutation (I, II 重点在于如何去重)
* Leetcode 77 Combinations (I, II 重点在于如何去重)
* Leetcode 698 Partition to K Equal Sum Subsets
* Leetcode 526 Beautiful Arrangement (similar to 46)

记忆化搜索（DFS + Memoization Search）：算是用递归的方式实现动态规划，递归每次返回时同时记录下已访问过的节点特征，避免重复访问同一个节点，可以有效的把指数级别的DFS时间复杂度降为多项式级别; 注意这一类的DFS必须在最后有返回值（分治法），不可以用回溯法; for循环的dp题目都可以用记忆化搜索的方式写，但是不是所有的记忆化搜索题目都可以用for循环的dp方式写。
* Leetcode 139 Word Break II
* Leetcode 72 Edit Distance
* Leetcode 377 Combination Sum IV
* Leetcode 1235 Maximum Profit in Job Scheduling
* Leetcode 1335 Minimum Difficulty of a Job Schedule
* Leetcode 1216 Valid Palindrome III
* Leetcode 97 Interleaving String
* Leetcode 472 Concatenated Words
* Leetcode 403 Frog Jump
* Leetcode 329 Longest Increasing Path in a Matrix

## 前缀和（Prefix Sum）
基础知识：前缀和本质上是在一个list当中，用O（N）的时间提前算好从第0个数字到第i个数字之和，在后续使用中可以在O（1）时间内计算出第i到第j个数字之和，一般很少单独作为一道题出现，而是很多题目中的用到的一个小技巧
* Leetcode 53 Maximum Subarray
* Leetcode 1423 Maximum Points You Can Obtain from Cards
* Leetcode 1031 Maximum Sum of Two Non-Overlapping Subarrays
* Leetcode 523 Continuous Subarray Sum
* Leetcode 304 Range Sum Query 2D - Immutable

# Leetcode中频
## 并查集（Union Find）：把两个或者多个集合合并为一个集合
基础知识：如果数据不是实时变化，本类问题可以用BFS或者DFS的方式遍历，如果数据实时变化（data stream）则并查集每次的时间复杂度可以视为O（1）；需要牢记合并与查找两个操作的模板
* Leetcode 721 Accounts Merge
* Leetcode 547 Number of Provinces
* Leetcode 737 Sentence Similarity II
* Leetcode 305 Number of Islands II

## 字典树（Trie）
基础知识：多数情况下可以通过用一个set来记录所有单词的prefix来替代，时间复杂度不变，但空间复杂度略高
* Leetcode 208 Implement Trie (Prefix Tree)
* Leetcode 211 Design Add and Search Words Data Structure
* Leetcode 1268 Search Suggestions System
* Leetcode 212 Word Search II
* Leetcode 1166 Design File System

## 单调栈与单调队列（Monotone Stack／Queue）
基础知识：单调栈一般用于解决数组中找出每个数字的第一个大于／小于该数字的位置或者数字；单调队列只见过一道题需要使用；不论单调栈还是单调队列，单调的意思是保留在栈或者队列中的数字是单调递增或者单调递减的
* Leetcode 85 Maximum Rectangle
* Leetcode 84 Largest Rectangle in Histogram
* Leetcode 907 Sum of Subarray Minimums (与84类似)
* Leetcode 739 Daily Temperatures
* Leetcode 901 Online Stock Span
* Leetcode 503 Next Greater Element II
* Leetcode 239 Sliding Window Maximum （唯一的单调队列题）

## 扫描线算法（Sweep Line）
基础知识：一个很巧妙的解决时间安排冲突的算法，本身比较容易些也很容易理解
* Leetcode 253 Meeting Room II（Meeting Room I也可以使用）
* Leetcode 1094 Car Pooling
* Leetcode 218 The Skyline Problem
* Leetcode 759 Employee Free Time

## TreeMap
基础知识：基于红黑树（平衡二叉搜索树）的一种树状 hashmap，增删查改、找求大最小均为logN复杂度，Python当中可以使用SortedDict替代；SortedDict继承了普通的dict全部的方法，除此之外还可以peekitem(k)来找key里面第k大的元素，popitem(k)来删除掉第k大的元素，弥补了Python自带的heapq没法logN时间复杂度内删除某个元素的缺陷；最近又在刷一些hard题目时候突然发现TreeMap简直是个神技，很多用别的数据结构写起来非常麻烦的题目，TreeMap解决起来易如反掌。
* Leetcode 729 My Calendar I
* Leetcode 981 Time Based Key-Value Store
* Leetcode 846 Hand of Straights
* Leetcode 218 The Skyline Problem
* Leetcode 480. Sliding Window Median (这个题用TreeMap超级方便)
* Leetcode 318 Count of Smaller Numbers After Self (这个题线段树、二分索引树、TreeMap都可以)
