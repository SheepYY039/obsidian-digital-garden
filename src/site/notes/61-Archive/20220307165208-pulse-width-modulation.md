---
{"dg-publish":true,"permalink":"/61-archive/20220307165208-pulse-width-modulation/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Pulse Width Modulation

> [!word] Pulse Width Modulation
> The change in **width** of a [[20220307163549-Pulse-Voltage|pulse]] to fit our [[61-Archive/20220318120826-voltage|voltage]] requirements.

## Controlling PWM

The [[61-Archive/20220420142646-average-voltage|average voltage]] is controlled by varying the [[61-Archive/20220420142326-duty-cycle|Duty Cycle]] of a **positive pulse** ($V_{L}=0$).

1. Since the pulse if always positive, and we limit the pulse to only 2 values (`HIGH=5V` and `LOW=0V` ), so the average value can be calculated using $V_{ave}=\frac{H}{H+L}V_{H}$
2. 系一定時間之內，如果 `x%` 係 `high`（`x%` Duty Cycle）， then averge voltage 就是 maximum voltage 的 `x%`

![[Pasted-image-20220420153233.png|Pasted image 20220420153233]]

## Related

- [[61-Archive/20220420153603-applications-of-pwm|Applications of PWM]]
