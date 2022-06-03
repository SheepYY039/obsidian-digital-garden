---
{"dg-publish":true,"permalink":"/61-archive/20220319091355-greedy-algorithms/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Greedy Algorithms

> [[61-Archive/20220319091355-greedy-algorithms#Greedy-Algorithms|!word]]
> A greedy algorithm works in phases, at each phase
>
> - You take the best you can get right now, without regard for future consequences
> - you hope that by choosing a _local_ optimum at each step, you will end up at a _global_ optimum

## Example of [[61-Archive/20220319091355-greedy-algorithms|Greedy Algorithms]]

### Counting Money

- Suppose you want to count out a certain amount of money, using the fewest possible bills and coins
- A greedy algorithm would do this would be:
  At each step, take the largest possible bill or coin that does not overshoot
  - Example: To make $6.39, you can choose:
  - a $5 bill
  - a $ 1 bill, to make $6
  - a 25¢ coin, to make $6.25
  - A 10¢ coin, to make $6.35
  - four 1¢ coins, to make $6.39
- For US money, the greedy algorithm always gives the optimum solution

## Failure of the [[61-Archive/20220319091355-greedy-algorithms|Greedy Algorithm]]

- In some (fictional) monetary system, “krons” come in _1_ kron, _7_ kron, and _10_ kron coins
- Using a greedy algorithm to count out 15 krons, you would get
  - A 10 kron piece
  - Five 1 kron pieces, for a total of 15 krons
  - This requires six coins
- A better solution would be to use two 7 kron pieces and one 1 kron piece
  - This only requires three coins
- The greedy algorithm results in a solution, but not in an optimal solution
