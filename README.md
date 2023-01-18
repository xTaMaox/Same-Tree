# Same-Tree

Given the roots of two binary trees p and q, write a function to check if they are the same or not.

Two binary trees are considered the same if they are structurally identical, and the nodes have the same value.

 

Example 1:

![ex1](https://user-images.githubusercontent.com/88260025/213246611-ff3c8623-3164-43b6-9fc6-4a5506334893.jpg)

Input: p = [1,2,3], q = [1,2,3]
Output: true

Example 2:

![ex2](https://user-images.githubusercontent.com/88260025/213246689-accf34da-5e98-4733-b52f-6695a0866133.jpg)

Input: p = [1,2], q = [1,null,2]
Output: false

Example 3:

![ex3](https://user-images.githubusercontent.com/88260025/213246789-b20ce41e-cadd-4247-8366-6b4b5f21da6d.jpg)

Input: p = [1,2,1], q = [1,1,2]
Output: false
 

Constraints:

The number of nodes in both trees is in the range [0, 100].
-104 <= Node.val <= 104
