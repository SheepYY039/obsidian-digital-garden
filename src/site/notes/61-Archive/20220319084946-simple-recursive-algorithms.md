---
{"dg-publish":true,"permalink":"/61-archive/20220319084946-simple-recursive-algorithms/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Simple Recursive Algorithms

> [[61-Archive/20220319084946-simple-recursive-algorithms#Simple-recursive-algorithms|!word]]
> A simple recursive algorithm
>
> - Solves the base cases directly
> - Recurs with a simpler subproblem
> - Does some extra work to convert the solution to the simple subproblem into a solution to the given problem

## Example Recursive Algorithms

### Count the Number of Elements in a List

1. If the list is empty, return 0; otherwise
2. Step past the first element, and count the remaining elements in the list
3. Add one to the result

### Test if a Value Occurs in a List

1. If the list is empty, return false; otherwise,
2. If the first thing in the list is the given value, return true; otherwise,
3. Step past the first element, and test whether the value occurs in the remainder of the list
