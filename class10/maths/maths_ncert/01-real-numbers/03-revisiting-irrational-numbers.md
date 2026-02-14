---
layout: default
title: 1.3 Revisiting Irrational Numbers
nav_order: 3
parent: Chapter 1 - Real Numbers
grand_parent: Class 10 Maths
mathjax: true
---

# 1.3 Revisiting Irrational Numbers

In Class IX, you were introduced to irrational numbers and many of their properties.
You studied about their existence and how the rationals and the irrationals together
made up the real numbers. You even studied how to locate irrationals on the number
line. However, we did not prove that they were irrationals.

In this section, we will prove that $\sqrt{2}$, $\sqrt{3}$, $\sqrt{5}$ and, in general, $\sqrt{p}$ is irrational, where
$p$ is a prime.

Recall: a number $s$ is called irrational if it cannot be written in the form $\frac{p}{q}$,
where $p$ and $q$ are integers and $q \ne 0$.

Some examples of irrational numbers (that you may already be familiar with) are:

- $\sqrt{2}$
- $0.10110111011110\ldots$
- $\sqrt{3}$

Before we prove that $\sqrt{2}$ is irrational, we need the following theorem, whose proof is based on the
Fundamental Theorem of Arithmetic.

### Theorem 1.2

Let $p$ be a prime number. If $p$ divides $a^2$, then $p$ divides $a$, where $a$ is a positive integer.

**Proof:** Let the prime factorisation of $a$ be

$$
a = p_1 p_2 \dots p_n,
$$

where $p_1, p_2, \dots, p_n$ are primes (not necessarily distinct).

Then,

$$
a^2 = (p_1 p_2 \dots p_n)(p_1 p_2 \dots p_n) = p_1^2 p_2^2 \dots p_n^2.
$$

We are given that $p \mid a^2$. By the Fundamental Theorem of Arithmetic (uniqueness of prime factorisation),
$p$ must be one of the prime factors of $a^2$, i.e. one of $p_1, p_2, \dots, p_n$.
Hence $p \mid a$.

We are now ready to give a proof that $\sqrt{2}$ is irrational. The proof is based on a technique called
**proof by contradiction**. (This technique is discussed in some detail in Appendix 1 of the book.)

### Theorem 1.3

$\sqrt{2}$ is irrational.

**Proof (by contradiction):** Assume, to the contrary, that $\sqrt{2}$ is rational.
Then there exist integers $r$ and $s$ ($s \ne 0$) such that

$$
\sqrt{2} = \frac{r}{s}.
$$

If $r$ and $s$ have a common factor other than 1, divide both by the common factor to get

$$
\sqrt{2} = \frac{a}{b},
$$

where $a$ and $b$ are coprime.

*(Not from the examination point of view.)*

Squaring,

$$
2 = \frac{a^2}{b^2} \quad \Rightarrow \quad 2b^2 = a^2.
$$

So $2 \mid a^2$, hence $2 \mid a$ by Theorem 1.2. Therefore, $a = 2c$ for some integer $c$.
Substituting:

$$
2b^2 = (2c)^2 = 4c^2 \quad \Rightarrow \quad b^2 = 2c^2.
$$

So $2 \mid b^2$, hence $2 \mid b$ (again by Theorem 1.2 with $p=2$). Thus, both $a$ and $b$
are divisible by 2, contradicting that $a$ and $b$ are coprime. Hence $\sqrt{2}$ is irrational.

### Example 5

Prove that $\sqrt{3}$ is irrational.

**Solution:** Assume, to the contrary, that $\sqrt{3}$ is rational. Then for some coprime integers $a$ and $b$
($b \ne 0$),

$$
\sqrt{3} = \frac{a}{b}.
$$

Squaring:

$$
3 = \frac{a^2}{b^2} \quad \Rightarrow \quad 3b^2 = a^2.
$$

So $3 \mid a^2$, hence $3 \mid a$ by Theorem 1.2. Let $a=3c$ for some integer $c$. Substituting:

$$
3b^2 = 9c^2 \quad \Rightarrow \quad b^2 = 3c^2.
$$

So $3 \mid b^2$, hence $3 \mid b$. Thus, $a$ and $b$ are both divisible by 3, contradicting that they are coprime.
Therefore, $\sqrt{3}$ is irrational.

### Some useful facts (Class IX recall)

- The sum or difference of a rational and an irrational number is irrational.
- The product and quotient of a non-zero rational and an irrational number is irrational.

### Example 6

Show that $\sqrt{5} - \sqrt{3}$ is irrational.

{: .note }
> **Note:** If you’re comparing against PDF-extracted text, radicals (like $\sqrt{\;}$) and some symbols may be dropped or garbled during extraction. The math here follows the intended NCERT notation.

**Solution:** Assume, to the contrary, that $\sqrt{5} - \sqrt{3}$ is rational.
Then for some coprime integers $a$ and $b$ ($b \ne 0$),

$$
\sqrt{5} - \sqrt{3} = \frac{a}{b}.
$$

So,

$$
\sqrt{5} = \sqrt{3} + \frac{a}{b}.
$$

Squaring both sides:

$$
5 = 3 + \frac{a^2}{b^2} + \frac{2a}{b}\sqrt{3}.
$$

Rearranging,

$$
2 - \frac{a^2}{b^2} = \frac{2a}{b}\sqrt{3}
\quad \Rightarrow \quad
\sqrt{3} = \left(2 - \frac{a^2}{b^2}\right)\frac{b}{2a}.
$$

The right-hand side is rational (ratio of integers), so $\sqrt{3}$ would be rational, contradicting Example 5.
Hence $\sqrt{5} - \sqrt{3}$ is irrational.

### Example 7

Show that $\sqrt{3}\,\sqrt{2}$ is irrational.

**Solution:** Assume, to the contrary, that $\sqrt{3}\,\sqrt{2}$ is rational. Then we can find coprime integers
$a$ and $b$ ($b \ne 0$) such that

$$
\sqrt{3}\,\sqrt{2} = \frac{a}{b}.
$$

Since $\sqrt{3}$ is irrational and $a,b$ are integers, this implies

$$
\sqrt{2} = \frac{a}{\sqrt{3}\,b},
$$

so $\sqrt{2}$ would be rational, which contradicts Theorem 1.3.
Hence $\sqrt{3}\,\sqrt{2}$ is irrational.

## Source
- [NCERT PDF (Real Numbers)](../content/jemh101-real-numbers.pdf)

