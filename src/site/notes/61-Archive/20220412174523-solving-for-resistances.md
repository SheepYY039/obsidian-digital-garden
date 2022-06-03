---
{"dg-publish":true,"permalink":"/61-archive/20220412174523-solving-for-resistances/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Solving for Resistances

The unknown [resistances](20220408115601-resistance.md) within a complex circuit can be found using a combination of [KVL](62-Encyclopedic/20220221122800-kirchhoffs-voltage-law.md), [KCL](62-Encyclopedic/20220221115900-kirchhoffs-current-law.md), and [Ohm's Law](20220408120857-ohm's-law.md).

> [!warning]
> In this (a complex) circuit, the [series](20220411105450-resistor-in-series.md)-[parallel](20220408133318-resistors-in-parallel.md) techniques **_cannot_** be used.
>
> - Because all the [resistors](20220221120700-resistor.md) are **not** in _clear_ series or parallel configurations that **can be reduced**.
> - Instead, [KVL](62-Encyclopedic/20220221122800-kirchhoffs-voltage-law.md) should be used to find the **total [Current](20220408104411-current.md)** $I$.
> - [Ohm's Law](20220408120857-ohm's-law.md) can be applied to determine **total [resistance](20220408115601-resistance.md)** $R_{eq}=\frac{V}{I}$

## Example

![Pasted image 20220412174640](Pasted-image-20220412174640.png)

Solve for $R_{eq}$

1. Apply [KVL](62-Encyclopedic/20220221122800-kirchhoffs-voltage-law.md) to solve for loop currents $I_{1}$, $I_{2}$, and $I_{3}$
2. Then we have $R_{eq}=\frac{V}{I}$ ([Ohm's Law](20220408120857-ohm's-law.md))
3. We can also find the [Voltage](20220318120826-voltage.md) values at each [node](20220411113840-node.md) relative to GND.
   1. $V_{A}=V$ (Power Source)
   2. $V_{B}=0$ (GND)
   3. $V_{C}=I_{3}R_{4}$
   4. $V_{D}=(I_{1}-I_{3})R_{2}$

![Pasted image 20220412175403](Pasted-image-20220412175403.png)
