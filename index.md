---
title: "First Blog"
permalink: /
layout: default
---

# My blog article


The recent computer skills I was learned is some `basic logic` in computer science.
It include 6 kind of logic:
*OR
*AND
*NOT
*NAND
*NOR
*XOR
![summary](https://facweb.cse.msu.edu/cbowen/cse320/circuit2/slides/Slide28.PNG)

## [OR, AND and NOT expression](https://facweb.cse.msu.edu/cbowen/cse320/circuit1/video/circuitsM.mp4)
### OR
The first one an *OR* gate. The output is one if either input is one.We notate OR in an expression using the **plus sign**, as in F(A,B) = A + B. The truth table for OR is:
|       A     |       B     |   F(A,B)    |
| ----------- | ----------- | ----------- |
|  0       |     0     |   0    |
|  0       |     1     |   1    |
|  1       |     0     |   1    |
|  1       |     1     |   1    |


### AND
Here's an *AND* gate. For an AND gate the output is one only if both inputs are one. We notate AND in an expression as if it were **multiplication**, as in F(A,B) = AB. The truth table for AND is:


|       A     |       B     |   F(A,B)    |
| ----------- | ----------- | ----------- |
|  0       |     0     |   0    |
|  0       |     1     |   0    |
|  1       |     0     |   0    |
|  1       |     1     |   1    |
### Not
Finally, It have the inverter (*NOT*). The NOT in an expression using an **apostrophe**, as in F(A) = A'. The truth table for NOT is:

|       A     |   F(A)    |
| ----------- |  ---------- |
|  0       |   1    |
|  1       |   0    |
 expressions are: NOT, then AND, then OR.

## [NAND，NOR and XOR](https://facweb.cse.msu.edu/cbowen/cse320/circuit2/video/nandM.mp4)
NAND and NOR are variations on the AND and OR gate, with the distinction that the output is inverted. A NAND gate is the **same** thing as an AND gate followed by a NOT gate.

### NOR
The truth table for a *NOR* gate is:

|       A     |       B     |   F(A,B)    |
| ----------- | ----------- | ----------- |
|  0       |     0     |   1    |
|  0       |     1     |   0    |
|  1       |     0     |   0    |
|  1       |     1     |   0    |
Algebraically, OR is represented as addition using a plus sign and NOT using an apostrophe. This makes the algebraic expression for a NOR gate:
F(A, B) = (A + B)'

### NAND
In the same way, **inverting** the output of an AND gate makes a NAND gate. The truth table for a *NAND* gate is:

|       A     |       B     |   F(A,B)    |
| ----------- | ----------- | ----------- |
|  0       |     0     |   1    |
|  0       |     1     |   1    |
|  1       |     0     |   1    |
|  1       |     1     |   0    |
Algebraically, OR is represented as multiplication followed by NOT with an apostrophe. This makes the algebraic expression for a NAND gate:
F(A, B) = (AB)'

### Xor
Finally, the special kind of logic gate called an exclusive-or or *XOR*. The output of an XOR gate is true if the two inputs **differ**.S
The truth table for an XOR gate is:

|       A     |       B     |   F(A,B)    |
| ----------- | ----------- | ----------- |
|  0       |     0     |   0    |
|  0       |     1     |   1    |
|  1       |     0     |   1    |
|  1       |     1     |   0    |
An algebraic expression for an XOR gate is:
F(A, B) = AB' + A'B

- [x] Summary all skills I've learned
- [x] List them with easy expression
- [ ] wait for checking

