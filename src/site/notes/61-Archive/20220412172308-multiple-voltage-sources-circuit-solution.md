---
{"dg-publish":true,"permalink":"/61-archive/20220412172308-multiple-voltage-sources-circuit-solution/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Multiple Voltage Sources Circuit Solution

![Pasted image 20220412172323](Pasted-image-20220412172323.png)

This problem can be solved using both methods ([KCL Calculations](20220412170527-kcl-calculations.md) and [KVL Calculations](20220412170607-kvl-calculations.md).

## Using [KVL](62-Encyclopedic/20220221122800-kirchhoffs-voltage-law.md)

Solving using [KVL Calculations](20220412170607-kvl-calculations.md)

### Both Loops Clockwise

![Pasted image 20220412172731](Pasted-image-20220412172731.png)

1. Decide the loops to use 1. For this circuit, there are 3 loops existing
2. Decide the [current direction](20220408110703-current-flow.md) for each [loop](20220411113941-loops.md)
3. Write the equation for each loop using [KVL](62-Encyclopedic/20220221122800-kirchhoffs-voltage-law.md) **in terms of _Loop Currents_** 1. Loop 1: $2I_{1}+1(I_{1}-I_{2})-6=0$ 2. Loop 2: $10+2I_{2}+1(I_{2}-I_{1})=0$
4. Solve the equations to find the _loop currents_ $I_{1}$ and $I_{2}$
5. Using $I_{1}$ and $I_{2}$ to find [voltage value](20220318120826-voltage.md) $V_{x}$

Loop 1 Simplified --> $3I_{1}-I_{2}=6$
Loop 2 Simplified --> $I_{1}-3I_{2}=10$

Then $I_{1}=1A$ and $I_{2}=-3A$ can be found. Then $V_{x}=1(I_{1}-I_{2})=4V$

### Setting Opposing Loop Directions

![Pasted image 20220412173214](Pasted-image-20220412173214.png)

1. Define the Loop Directions
2. Use [KVL](62-Encyclopedic/20220221122800-kirchhoffs-voltage-law.md) to write [Voltage](20220318120826-voltage.md) equation in each [loop](20220411113941-loops.md) in terms of loop currents $I_{1}$ and $I_{2}$
   1. Loop 1 -> $2I_{1}+1(I_{1}+I_{2})=6$
   2. Loop 2 -> $1(I_{1}+I_{2})+2I_{2}=10$
3. Simplify the equation
   1. Loop 1 Simplified -> $3I_{1}+I_{2}=6$
   2. Loop 2 Simplified -> $I_{1}+3I_{2}=10$
4. Solve the simutaneous equation
   1. $6=3(10-3I_{2})+I_{2}=30-8I_{2}$
   2. $8I_{2}=24$ -> $I_{2}=3$
   3. $3I_{1}+3=6$ -> $I_{1}=1$
5. Find $V_{x}$
   1. $V_{x}=1(I_{1}+I_{2})=4V$

## Using [KCL](62-Encyclopedic/20220221115900-kirchhoffs-current-law.md)

![Pasted image 20220412174154](Pasted-image-20220412174154.png)
Solving using [KCL Calculations](20220412170527-kcl-calculations.md)

1. Write the equation for node `X` using [KCL](62-Encyclopedic/20220221115900-kirchhoffs-current-law.md)
   1. $I_{A}=I_{B}+I_{C}$
   2. $\frac{6-V_{x}}{2}=\frac{V_{x}}{1}+ \frac{V_{x}-10}{2}$ [Ohm's Law](20220408120857-ohm's-law.md)
2. Solve the equation
   1. $6-V_{x}=2V_{x}+V_{x}-10$
   2. $4V_{x}=16$
   3. $V_{x}=4V$
