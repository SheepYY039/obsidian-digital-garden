---
{"dg-publish":true,"permalink":"/61-archive/20220319092154-brute-force-algorithms/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Brute Force Algorithms

> [!word] Brute force algorithm
>
> - A brute force algorithm simply tries all possibilities until a satisfactory solution is found

## Uses of [[61-Archive/20220319092154-brute-force-algorithms#Brute-Force-algorithms|Brute Force algorithms]]

- Such an algorithm can be:

### Optimizing

Find the best solution.

This may require finding all solutions, or if a value for the best solution is known, it may stop when any best solution is found

- Example: Finding the best path for a travelling salesman

### Satisfying

Stop as soon as a solution is found that is good enough

- Example: Finding a travelling salesman path that is within 10% of optimal

## Improving [[61-Archive/20220319092154-brute-force-algorithms|Brute Force algorithms]]

- Often, brute force algorithms require exponential time
- Various heuristics and optimizations can be used
  - **Heuristic**: A “rule of thumb” that helps you decide which possibilities to look at first
  - **Optimization**: In this case, a way to eliminate certain possibilities without fully exploring them
