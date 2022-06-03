---
{"dg-publish":true,"permalink":"/61-archive/20220311122736-dark-and-bright-sensing-circuit/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Dark and Bright Sensing Circuit

[[61-Archive/20220225122049-transistor#NPN-Transistors-as-Switches|Using-NPN-as-switches]] can be used to form a **Dark** or a **Bright** sensing circuit

- The placement of the [[61-Archive/20220311121856-photo-resistor|LDR]] in the circuit makes it either dark or light sensing

## Dark Sensing Circuit

> [[19700101080000-Light-Emitting-Diode|!abstract]] is ON when **dark surface** is detected

For a **dark sensing circuit**
![[<Pasted-image-20220420190601.png#center|The-LDR-is-placed-near-the-Emittor-(E]]%7C300>)

- On a dark surface,
  - There are no light falling on the [[61-Archive/20220311121856-photo-resistor|LDR]].
  - So the [[61-Archive/20220311121856-photo-resistor|LDR]] is **with high [[61-Archive/20220408115601-resistance|resistance]]** ($10M\ohm$).
  - [[61-Archive/20220225122049-transistor|transistor]] receives enough **base [[61-Archive/20220318120826-voltage|voltage]]** to be [[61-Archive/20220415142132-transistor-operation-modes#Saturation-Mode|ON]]
  - Thus [[61-Archive/20220408104411-current|current]] flows through the [[61-Archive/20220225122049-transistor|transistor]]
  - [[19700101080000-Light-Emitting-Diode|LED]] is **_ON_**
- On a _bright surface_,
  - High-level light fall on the [[61-Archive/20220311121856-photo-resistor|LDR]]
  - [[61-Archive/20220311121856-photo-resistor|LDR]] with low [[61-Archive/20220408115601-resistance|resistance]] ($100\ohm$)
  - [[61-Archive/20220225122049-transistor|Transistor]] is [[61-Archive/20220415142132-transistor-operation-modes#OFF-Mode|OFF]] -> No [[61-Archive/20220408104411-current|Current]] flows through
  - thus [[19700101080000-Light-Emitting-Diode|LED]] is **_OFF_**

> [!tip]
>
> - The [[61-Archive/20220408115601-resistance|resistance]] when **unilluminated** (dark [[61-Archive/20220408115601-resistance|resistance]]) is very high at about $10M\ohm$ -> [[61-Archive/20220415142132-transistor-operation-modes#Saturation-Mode|20220415142132-Transistor-Operation-Modes#Saturation-Mode]]
> - The [[61-Archive/20220408115601-resistance|resistance]] fall to about $100\ohm$ when **fully illuminated** (bright [[61-Archive/20220408115601-resistance|resistance]]) -> [[61-Archive/20220415142132-transistor-operation-modes#OFF-Mode|20220415142132-Transistor-Operation-Modes#OFF-Mode]]

## Bright Sensing Circuit

> [[19700101080000-Light-Emitting-Diode|!abstract]] is ON when **bright surface** is detected

For a **bright sensing circuit**

![[Pasted-image-20220420190810.png#center|The-LDR-is-placed-near-the-collector-C]]

- On a dark surface,
  - There are no light falling on the [[61-Archive/20220311121856-photo-resistor|LDR]].
  - So the [[61-Archive/20220311121856-photo-resistor|LDR]] is **with high [[61-Archive/20220408115601-resistance|resistance]]** ($10M\ohm$).
  - [[61-Archive/20220225122049-transistor|Transistor]] is [[61-Archive/20220415142132-transistor-operation-modes#OFF-Mode|OFF]] -> No [[61-Archive/20220408104411-current|Current]] flows through
  - thus [[19700101080000-Light-Emitting-Diode|LED]] is **_OFF_**
- On a _bright surface_,
  - High-level light fall on the [[61-Archive/20220311121856-photo-resistor|LDR]]
  - [[61-Archive/20220311121856-photo-resistor|LDR]] with low [[61-Archive/20220408115601-resistance|resistance]] ($100\ohm$)
  - [[61-Archive/20220225122049-transistor|Transistor]] receives enough base [[61-Archive/20220318120826-voltage|voltage]] to be on [[61-Archive/20220415142132-transistor-operation-modes#Amplification-Mode|ON]]
  - Thus [[61-Archive/20220408104411-current|current]] flows through the [[61-Archive/20220225122049-transistor|transistor]]
  - [[19700101080000-Light-Emitting-Diode|LED]] is **_ON_**
