# InterviewChecklist
 Java
 - Comparable vs Comparator
 - Hash
  - https://www.coursera.org/learn/data-structures/lecture/2yY2h/chaining-scheme
 - static
 - exception
 - Thread
 - Generics


Algo
 - LinkedList
  - 	Linked List Cycle
  - 	Remove Nth Node From End of List
  - 	Merge Two Sorted Lists
  -  Intersection of Two Linked Lists
  - 	Remove Duplicates from Sorted List
  - 	Palindrome Linked List
  -  Insertion Sort in LL
  -  Remove duplicates from an unsorted linked list w/o using additional buffer
  
 - String 
  - Determine if a string has all unique characters (CTCI)
  - Remove the duplicate characters in a string without using additional buffer (CTCI)
  - Check if 2 strings are anagram (CTCI)
  - Check if a string is a rotation of another string (CTCI)
  - Longest palindromic substring
  - new String vs Literal String - http://stackoverflow.com/questions/14757978/new-string-vs-literal-string-performance
  - String builder - Read from CTCI
  - StringBuffer vs String Builder
 
 - DP
  - Best Time to Buy and Sell Stock
  - House Robber
  - Climbing Stairs
  - Unique Paths
  - Edit Distance- http://www.programcreek.com/2013/12/edit-distance-in-java/
  - Knapsack Problem
  - Paint Fence
  
 - Binary Search
  - Can be used for monotonically increasing / decreasing function. Ex : sqrt(x)
  - Square root : https://www.interviewbit.com/problems/square-root-of-integer/
  - First and last occurance of a number : https://www.youtube.com/watch?v=OE7wUUpJw6I
  - No of rotation of sorted array: https://www.youtube.com/watch?v=4qjprDkJrjY

 - Sorting - https://xmruibi.gitbooks.io/interview-preparation-notes/content/Algorithm/Sort/
  - QuickSort
  - MergeSort (Do for LinkedList also)
  - Why is HeapSort unstable?
  - Arrange numbers such that they form the largest number : https://xmruibi.gitbooks.io/interview-preparation-notes/content/Algorithm/Sort/LargestNumber.html
  - Sort Color : https://xmruibi.gitbooks.io/interview-preparation-notes/content/Algorithm/Sort/SortColorI.html
 
 - Tree
   - Inorder Traversal (Recursively/iteratively)
   - Preorder Traversal (Recursively/iteratively)
   - PostOrder Traversal (Recursively/iteratively)
   - Level Order Traversal (Recursively/iteratively)
   - Invert a tree
   - Min depth
   - Max depth
   - Sum of Left Leaf
   - Serialize and Deserialize
   - Validate BST
   - Lowest Commom Ancestor http://www.geeksforgeeks.org/lowest-common-ancestor-binary-tree-set-1/
   - Insert node in a BST
   - Delete node in a BST  (Leetcode Solution-Revise)
   - Find all root-to-leaf paths where each path's sum equals the given sum- Leetcode
   
 - Graph
  - Graph reprsentation - (Pros and Cons)
  - BFS
  - DFS 
   - check cyclic/acyclic
   - Topological sort
   - Connected components in a graph
   - Bipartite graph
  - Travelling Salesman Problem :x:
  
 - Heap
  - Implement Max Heap - http://algorithms.tutorialhorizon.com/binary-min-max-heap/
  - Design Twitter - 10 most recent tweets
  - Find kth smallest/largest element
  - Top K Frequent Elements
  
 - Misc
  - Trie :+1:
  - PowerSet- http://javabypatel.blogspot.in/2015/10/all-subsets-of-set-powerset.html
  - 3sum- http://www.programcreek.com/2012/12/leetcode-3sum/
  - 2sum with BST
  - Continuous sequence with the largest sum- http://www.geeksforgeeks.org/largest-sum-contiguous-subarray/
  - Overlapping Sets- http://www.geeksforgeeks.org/interval-tree/
  - Integer Multiplication - Karatsuba Algorithm
  - Power - http://www.geeksforgeeks.org/calculate-square-of-a-number-without-using-and-pow/
  - Maximum number of edges in a directed acyclic graph - https://www.careercup.com/question?id=6314916858298368
  - LRU Cache
  - LFU Cache
  - Remove Duplicates from Sorted Array

Design
 - All CTCI problems
 - https://github.com/checkcheckzz/system-design-interview

System/Networking
 - Peer to Peer Architecture (Netflix)
 - TCP vs UDP (Application)
 - How TCP handles reliable delivery
 - What happens after an URL is typeed into a browser
 - IPv4 vs IPv6
 - Routing Protocol
 - Difference between a thread and a process
 - Difference between Semaphore, Mutex and Spin lock
 - Virtual Memory
 - Measure time spent in context switching

Links To Practice
 - https://www.niceideas.ch/roller2/badtrash/entry/hard_software_engineering_interview_questions
 - http://www.businessinsider.com/15-mind-bending-interview-questions-that-every-google-engineer-can-answer-2012-1?op=1

To know Basics:
 - Print nested arrays: Arrays.deepToString(a)
 - char [] s= str.tocharArray()
 - digits [i]= nums.charAt(i)-'a'
 - Arrays.equals(array1, array2)
 - Arrays.sort(array1)
 - Avoid overflow in finding midpoint by changing mid = (start + end)/2 to mid = start + (end - start)/2
 - Avoid overflow in multiplication by converting it to division. Ex: y > x*x can be checked as y/x>x

