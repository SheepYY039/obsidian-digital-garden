---
{"dg-publish":true,"permalink":"/66-courses/66-09-comp-2011/20220224135401-arithmetic-conversion-rules-in-c/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Arithmetic Conversion Rules

If all operands are int

- Compute using integer arithmetic

If one operand is double/ float

- convert the other operand to double/float
- compute using floating-point arithmetic
- return the result in double/float

## Integer Arithmetic

Arithmetic expressions involving **only integers** use integer arithmetic

> [!note]
> long --> int --> short --> char --> bool

## Floating-point Arithmetic

Arithmetic expressions involving **_at least one_ floating-point numbers** using floating-point arithmetic

## Division

For +, -, $\times$ operations, results should be what you expect

**Integer Division** and **Floating-point** division:

| Integer Division | Floating-point Division |
| ---------------- | ----------------------- |
| 10/2 = 5         | 10.0/2.0 = 5.0          |
| 9/2 = 4          | 9.0/2.0 = 4.5           |
| 4/8 = 0          | 4.0/8.0 = 0.5           |

## Priority Rules for the Usual Arithmetic Conversions for [Binary Operations](20220224143639%20Binary%20Operations%20in%20C++.md)

1. If **either** operand is of type _long double_, convert the other operand also to _long double_
2. if **either** operand is of type _double_, convert the other operand also to _double_
3. If **either** operand is of type _float_, convert the other operand also to _float_
4. Otherwise, the _integral promotions_ shall be performed on **both operands**
   1. Similar rules are used for integral promotion of the operands
   2. Compute using _[integer arithmetic](#Integer%20Arithmetic)_

## Links

[Object Types](20220223153547%20Object%20Types%20in%20C++.md)
