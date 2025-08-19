---
layout: default
title: Real Numbers
nav_order: 1
description: ""
has_children: true
parent: Class 10 Modulus Maths
grand_parent: Home
tags: [MathJax, Mathematic]
---




## LCM and HCF of Two Positive Integers



We can effectively determine the **Least Common Multiple (L.C.M)** and **Highest Common Factor (H.C.F)** of two positive integers using the **prime factorization method**.



**Example:**

Let's find the L.C.M and H.C.F of 35 and 50.



**Solution:**

First, we'll find the prime factors for each number:

* $35 = 5 \times 7$

* $50 = 2^1 \times 5^2$



To calculate the **H.C.F**, we identify the common prime factors and take the lowest power of each. In this case, only 5 is common, and its lowest power is $5^1$.

H.C.F $= 5^1 = 5$



To calculate the **L.C.M**, we take the highest power of all prime factors present in either number.

L.C.M $= 2^1 \times 5^2 \times 7^1 = 2 \times 25 \times 7 = 350$



---



## General Method for HCF and LCM Using Prime Factorization



For two integers $a$ and $b$, if their prime factorizations are given as:

$a = p_1^{\alpha_1} \cdot p_2^{\alpha_2} \ldots p_k^{\alpha_k}$

$b = p_1^{\beta_1} \cdot p_2^{\beta_2} \ldots p_k^{\beta_k}$

where $p_1, p_2, \ldots, p_k$ are distinct prime numbers and $\alpha_i, \beta_i$ are non-negative integers representing their powers.



Then:

**H.C.F of $(a, b) = p_1^{\min(\alpha_1, \beta_1)} \cdot p_2^{\min(\alpha_2, \beta_2)} \ldots p_k^{\min(\alpha_k, \beta_k)}$** (take the minimum of the corresponding powers)



**L.C.M of $(a, b) = p_1^{\max(\alpha_1, \beta_1)} \cdot p_2^{\max(\alpha_2, \beta_2)} \ldots p_k^{\max(\alpha_k, \beta_k)}$** (take the maximum of the corresponding powers)



A fundamental relationship exists between the product of two numbers and their L.C.M and H.C.F:

$a \cdot b = \text{L.C.M of }(a, b) \times \text{H.C.F of }(a, b)$



**Example:**

Find the H.C.F of 315 and 462, and then use it to find their L.C.M.



**Solution:**

First, we'll find the prime factorization for each number:

* $315 = 3^2 \times 5^1 \times 7^1$

* $462 = 2^1 \times 3^1 \times 7^1 \times 11^1$



To find the **H.C.F of 315 and 462**, we identify the common prime factors (3 and 7) and use their lowest powers:

H.C.F $= 3^1 \times 7^1 = 3 \times 7 = 21$



Now, using the relationship $a \cdot b = \text{L.C.M} \times \text{H.C.F}$, we can find the L.C.M:

L.C.M $= \frac{315 \times 462}{\text{H.C.F}}$

L.C.M $= \frac{315 \times 462}{21} = 6930$



Got it. I'll combine the last two prompt outputs into a single, comprehensive response, maintaining the formatting, headings, Markdown tables, and the use of \frac for fractions.
