---
{"dg-publish":true,"permalink":"/61-archive/20220319085809-divide-and-conquer-algorithms/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Divide and Conquer Algorithms

> [[61-Archive/20220319085809-divide-and-conquer-algorithms#Divide-and-Conquer-algorithms|!word]]
> A divide and conquer problem algorithm consists of two parts
>
> 1. Divide the problem into smaller subproblems of the same type, and solve these subproblems recursively
> 2. Combine the solutions to the subproblems into a solution to the original problem
>
> Traditionally, an algorithm is only called divide and conquer if it contains two of more recursive calls.

## Example of Divide and Conquer Algorithms

### Quicksort

- Partition the [[../66-Courses/66.09-comp-2011/20220304151152-Array-in-C++.md|Array]] into two parts, and quicksort each of the parts
- No additional word is required to combine the two parts

### Mergesort

- Cut the [[../66-Courses/66.09-comp-2011/20220304151152-Array-in-C++.md|Array]] in half, and mergesort each half
- Combine the two sorted arrays into a single sorted [[../66-Courses/66.09-comp-2011/20220304151152-Array-in-C++.md|Array]] by merging them
