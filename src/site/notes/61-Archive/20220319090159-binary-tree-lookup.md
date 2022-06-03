---
{"dg-publish":true,"permalink":"/61-archive/20220319090159-binary-tree-lookup/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Binary Tree Lookup

To loop up something in a sorted binary tree

1. Compare the key to the value in the root
   1. if the two values are equal. report success
   2. If the key is less, search the left subtree
   3. If the key is greater, search the right subtree

> [!note]
> This is **_not_** a divide and conquer [[61-Archive/20220319084142-algorithm|Algorithm]] because
>
> - although there are two recursive calles,
> - only one is used at each level of the [[../66-Courses/66.09-comp-2011/20220316145907-Recursion.md|Recursion]]
