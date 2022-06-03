---
{"dg-publish":true,"permalink":"/61-archive/20220412170607-kvl-calculations/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# KVL Calculations

1. Define the Loops
2. Write Down Loop Equations using [KVL](62-Encyclopedic/20220221122800-kirchhoffs-voltage-law.md)
3. Write all `V` terms in terms of [Current](20220408104411-current.md) and [Resistance](20220408115601-resistance.md)
4. All [Current](20220408104411-current.md) and [Resistance](20220408115601-resistance.md) can be solved, and thus the [voltages](20220318120826-voltage.md)

> [!example] > ![Pasted image 20220412171133.png](Pasted-image-20220412171133.png) > ![Pasted image 20220412171351.png](Pasted-image-20220412171351.png)

> [!note]
>
> 1. Note that all resistors within a loop has the same current unless the resistor is shared between multiple loops.
>    1. If Shared, and [current flow](20220408110703-current-flow.md) in opposite directions, substract $I$ from each other $R(I_{1}-I_{2})$ and $R(I_{2}-I_{1})$
>    2. Else, add them together $R(I_{1}+I_{2})$
> 2. After finding all Currents, remember to find the voltage
> 3. To find the voltage, start from a [battery](20220221170305-battery.md), minus all the voltages dissapated along the way from resistors, until you reach the node that you want to find
