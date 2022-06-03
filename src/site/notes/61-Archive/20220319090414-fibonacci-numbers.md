---
{"dg-publish":true,"permalink":"/61-archive/20220319090414-fibonacci-numbers/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Fibonacci Numbers

## 1 [[61-Archive/20220319084142-algorithm|Algorithm]]

### 1.1 Find the `n`th Fibonacci Number

- If `n` is 0 or 1, return 1; otherwise,
- Compute `fibonacci(n-1)` and `fibonacci(n-2)`
- Return the sum of these two numbers

#### 1.1.1 Algorithm Complexity

This is an expensive [[61-Archive/20220319084142-algorithm|Algorithm]]

- It requires `O(fibonacci(n))` time
- This is equivalent to exponential time — $O(2^n)$

### 1.2 Better Fibonacci [[61-Archive/20220319084142-algorithm|Algorithm]]

- To find the $n^{th}$ [[61-Archive/20220319090414-fibonacci-numbers|Fibonacci number]]
  - If `n` is 0 or 1, return one; otherwise,
  - Compute, or _loop up in a table_, `fibonacci(n-1)` and `fibonacci(n-2)`
  - Find the sum of these two numbers
  - Store the result in a table and return it
- Since finding the $n^{th}$ Fibonacci number involves finding all smaller [[61-Archive/20220319090414-fibonacci-numbers|Fibonacci numbers]], the second recursive call has little work to do
- The table may be preserved and used again later
