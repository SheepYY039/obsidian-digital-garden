---
{"dg-publish":true,"permalink":"/61-archive/20220319092032-branch-and-bound-algorithms/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Branch and Bound Algorithms

- Branch and bound algorithms are generally used for [[61-Archive/20220319091521-optimization-problems|optimization problems]]

> [[61-Archive/20220319092032-branch-and-bound-algorithms#Branch-and-Bound-algorithms|!word]]
>
> - As the algorithm progresses, a tree of subproblems is formed
> - The original problem is considered the “root problem”
> - A method is used to construct an upper and lower bound for a given problem
> - At each node, apply the bounding methods
>   - If the bounds match, it is deemed a feasible solution to that particular subproblem
>   - If bounds do not match, partition the problem represented by that node, and make the two subproblems into children nodes
> - Continue, using the best known feasible solution to trim sections of the tree, until all nodes have been solved or trimmed
