---
{"dg-publish":true,"permalink":"/61-archive/20220413104633-power-is-most-efficient-when-r-equals-r/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Power is Most Efficient When R Equals R

![](/60-Meta-Attachments/Pasted image 20220413104649.png)

> Given the above circuit, how to maximize the deliverable [power](20220223192844-power.md)?

> [!note]
>
> - $R_{s}$ in the graph is just the [battery](20220221170305-battery.md)'s internal [resistance](20220408115601-resistance.md) $r$.
> - $R_{L}$ is the bulb's [resistance](20220408115601-resistance.md) $R$
> - $V_{s}$ is the [battery](20220221170305-battery.md)'s emf $\varepsilon$

It is know that the total [current](20220408104411-current.md) through the circuit is

$$
\begin{align*}
V&=\varepsilon -Ir\\
IR&=\varepsilon-Ir \\
\varepsilon&=I(R+r)\\
I&=\frac{\varepsilon}{R+r}
\end{align*}
$$

We know that (from [power](20220223192844-power.md))
$$P=I^{2}R$$

1. [Power](20220223192844-power.md) consumed by $r$ is 1. $P(r)=r(\frac{\varepsilon}{r+R})^{2}$
2. [Power](20220223192844-power.md) consumed by $R$ is 1. $P(R)=R(\frac{\varepsilon}{R+r})^{2}$

The general formula is $P(x)=x(\frac{\varepsilon}{R+r})^{2}$

Then, to maximize $P_{R}$, we take the derivative of $P_{R}$ with respect to $R$

$$
\begin{align*}
P_{R}&=\frac{\varepsilon^{2}}{(R+r)^{2}}R \\
\frac{dP_{R}}{dR}&=\varepsilon^{2}\frac{(R+r)^{2}-R(2r+2R)}{(R+r)^{4}}=0
\end{align*}
$$

$$
\begin{align*}
\frac{dP_{R}}{dR}&=0\\
(R+r)^{2}-R(2R+2r)&=\\
r^{2}-R^{2}&=0\\
r&=R
\end{align*}
$$

> [!summary]
>
> - maximum deliverable power occurs when $R=r$
> - maximum $P_{R}=\frac{\varepsilon}{4r}$ > ![](../60-Meta-Attachments/Pasted-image-20220413113950.png)

---

$$\text{efficiency}=\frac{\text{useful power out}}{\text{total power in}}$$
$$\text{efficiency}=\frac{P_{R}}{P_{r}+P_{R}}=\frac{I^{2}R}{I^{2}R+I^{2}r}=\frac{R}{R+r}=\frac{1}{1+\frac{r}{R}}$$
![](../60-Meta-Attachments/Pasted-image-20220413114548.png)

---
