---
{"dg-publish":true,"permalink":"/61-archive/20220415142132-transistor-operation-modes/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Transistor Operation Modes

All of the [transistors](20220225122049-transistor.md) have 3 modes of operations.

1. [OFF Mode](#OFF-Mode)
2. [Amplification Mode](#Amplification-Mode)
3. [Saturation Mode](#Saturation-Mode)

![](Pasted-image-20220415144102.png#inlL) $R_{B}$ is the resistor required on **Base (B)** to avoid a very high current.

## OFF Mode

![](../60-Meta-Attachments/Pasted-image-20220415144211.png)
The OFF mode <mark class="hltr-yellow">does not have any base current applied</mark> , meaning that $I_{B}=0$.

- Occurs when $V_{in}<0.7V$
- $I_{B}=I_{C}=0$

## Amplification Mode

![](../60-Meta-Attachments/Pasted-image-20220415144428.png)
![](../60-Meta-Attachments/Pasted-image-20220415144515.png)
$$I_{C}=\beta I_{B}$$
In the amplification mode, any changes in $I_{B}$ will cause impact $I_{C}$.
![](../60-Meta-Attachments/Pasted-image-20220415142611.png)

- Occurs when $0.7V<V_{in}<V_{sat}$
- The transistor is **partically on**
- $I_{B}$ is <mark class="hltr-yellow">small</mark>
- $I_{C}=\beta I_{B}$

## Saturation Mode

![](../60-Meta-Attachments/Pasted-image-20220415144548.png)
![](../60-Meta-Attachments/Pasted-image-20220415144600.png)

> [!note]
> Note that $V_{CE}$ is the 路費 from `C` to `E`

Any changes in $I_{B}$ **will not** cause changes in $I_{C}$ because $I_{C}$ has reached its **maximum**, so it is _approx. constant_.

- Occurs when $V_{in}>V_{sat}$
- Transistor is **fully on** (**_Saturated_**)
- $I_{B}$ is **large**
- $I_{C}$ is at its **maximum**

$$I_{B}=\frac{V_{in}-0.7}{R_{B}}$$

## Related

- The $V_{in}$-$V_{out}$ curve of a transistor can be found [here](20220415144754-transistor-saturation-voltage-in-out-curve.md)
