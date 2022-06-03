---
{"dg-publish":true,"permalink":"/61-archive/20220319085339-backtracking-algorithms/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Backtracking Algorithms

> [[61-Archive/20220319085339-backtracking-algorithms#Backtracking-Algorithms|!word]]
> Backtracking algorithms are based on a depth-first recursive search.
>
> A backtracking algorithm
>
> - Tests to see if a solution has been found, and if so, returns it; otherwise,
> - For each choice that can be made at this point,
>   - Make that choice
>   - Recur
>   - if the [[../66-Courses/66.09-comp-2011/20220316145907-Recursion.md|Recursion]] returns a solution, return it
> - If no choice remain, return failure

## Example Backtracking Algorithm

### To Colour a Map with No More Than Four Colours

1. colour(Country `n`)
   1. If all countries have been coloured (n>number of countries) return success; otherwise,
   2. For each colour `c` of four colours
   3. If country `n` is not adjacent to a country that has been coloured `c`
   4. Colour country `n` with colour `c`
   5. recursively colour country `n+1`
   6. If successful, return success
   7. Return Failure (if loop exists)
