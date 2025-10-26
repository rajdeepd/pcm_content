---
layout: default
title: MSET - Sequence and Series
nav_order: 11
description: ""
has_children: true
parent: Index MSET
grand_parent: Home
tags: [MathJax, Mathematic]
mathjax: true
---
# Sequence and Series

## ARITHMETIC PROGRESSION (A.P.)

---

### KEY FACTS

1. A sequence is a set of numbers specified in a definite order by some assigned rule or law.  

Ex. 2, 7, 12, 17... (Each succeeding term is obtained by adding 5 to the preceding term)  
1, 2, 4, 8, 16... (Each succeeding term is obtained by multiplying the preceding term by 2)

A finite sequence is that which ends or has a last term.  
Ex. 5, 9, 13, 17, 21.  

An infinite sequence is one which has no last term.  
Ex. 3, 6, 12, 24, 48...  

In general, **$a_n$** or **$T_n$** denotes the $n^{th}$ term of a sequence.

---

2. An expression consisting of the terms of a sequence alternating with the symbol '+' is called a **series**.  

Ex. The sequence $\frac{2}{3}, \frac{4}{5}, \frac{6}{7}, ...$ expressed as a series is  
$\frac{2}{3} + \frac{4}{5} + \frac{6}{7} + ...$

---

3. **Arithmetic Progression (A.P.):**  
A sequence is called an arithmetic progression if its terms continually increase or decrease by the same number.  
The fixed number by which they increase or decrease is called the **common difference**.

Three quantities $a, b, c$ will be in A.P. if $b - a = c - b$, i.e., $2b = a + c$.

---

### (a) $n^{th}$ Term of an A.P.

The $n^{th}$ term of an A.P. $a, a+d, a+2d, a+3d, ...$ is

$T_n = a + (n - 1)d$

where $T_n$ denotes $n^{th}$ term, $a$ the first term, $n$ the number of terms and $d$ the common difference.  

Also, common difference $d = T_n - T_{n-1}$.

**Example:**  
The 9th term of the A.P. 2, 5, 8, ... is  
$T_9 = 2 + (9 - 1) \times 3 = 2 + 24 = 26$  

Note: Here $a = 2, d = 3$.

---

### (b) Sum of $n$ Terms of an A.P.

Let the A.P. be $a, a+d, a+2d, ...$ Let $l$ be the last term and $S_n$ the required sum. Then,

$S_n = \frac{n}{2}(a + l) = \frac{n}{2}(2a + (n - 1)d)$

where $n$ is the number of terms, $a$ is the first term and $d$ is the common difference.  

Also, $n^{th}$ term $=$ (Sum of $n$ terms) $-$ (Sum of $(n - 1)$ terms),  
i.e., $T_n = S_n - S_{n-1}$.

**Example:**  
The sum of 20 terms of the A.P. 1, 3, 5, 7, 9... is  

$S_{20} = \frac{20}{2}(2 \times 1 + (20 - 1) \times 2)$  
$= 10 \times 40 = 400$

---

### (c) Arithmetic Mean

The arithmetic mean between two numbers is the number which when placed between them forms an arithmetic progression with them.  
Thus, if $x$ is the arithmetic mean of two given numbers $a$ and $b$, then $a, x, b$ form an A.P.

$\therefore \ x - a = b - x \Rightarrow x = \frac{a + b}{2}$

**Examples:**

(a) The arithmetic mean between -4 and 6 is $\frac{6 + (-4)}{2} = 1$.

(b) Find 4 arithmetic means between 3 and 23.

Let $A_1, A_2, A_3, A_4$ be the four arithmetic means between 3 and 23.  
Then, 3, $A_1, A_2, A_3, A_4, 23$ form an A.P.  

Here, $a = 3$, $T_6 = 23$, $n = 6$.

$T_6 = a + (n - 1)d$  
$\Rightarrow 23 = 3 + 5d$  
$\Rightarrow 5d = 20 \Rightarrow d = 4$

$\therefore A_1 = 3 + 4 = 7, A_2 = 11, A_3 = 15, A_4 = 19$

---

### (d) Some Useful Facts about an A.P.

I. If each term of a given A.P. is increased, decreased, multiplied or divided by the same number, the resulting progression is also an A.P.  

II. If $a, b, c$ are in A.P., then $\frac{a - b}{b - c} = 1$.

---

### (e) Special Term Patterns

If we have to find an odd number of terms in an A.P. whose sum is given, it is convenient to take $a$ as the middle term and $d$ as the common difference.  
Thus, three terms may be taken as $a - d, a, a + d$ and five terms as $a - 2d, a - d, a, a + d, a + 2d$.  

If we have to find an even number of terms, we take $a - d, a + d$ as the middle terms and $2d$ as the common difference.  
Then, four terms are taken as $a - 3d, a - d, a + d, a + 3d$.

---

## SOLVED EXAMPLES

---

**Example 1:**  
The 8th term of a series in A.P. is 23 and the 102nd term is 305. Find the series.

Let $a$ be the first term and $d$ the common difference.

$T_8 = a + (8 - 1)d = 23$  
$T_{102} = a + (102 - 1)d = 305$  

Subtracting: $94d = 282 \Rightarrow d = 3$  

Substituting $d = 3$ in (i): $23 = a + 21 \Rightarrow a = 2$  

$\therefore a = 2, d = 3 \Rightarrow$ Series is $2, 5, 8, 11, ...$

---

**Example 2:**  
If $a, b, c$ be respectively the $p^{th}$, $q^{th}$ and $r^{th}$ terms of an A.P., prove that  
$a(q - r) + b(r - p) + c(p - q) = 0$.

Let $A$ be the first term and $D$ the common difference.

$T_p = A + (p - 1)D = a$  
$T_q = A + (q - 1)D = b$  
$T_r = A + (r - 1)D = c$

Now, multiply:  
(i) × $(q - r)$ + (ii) × $(r - p)$ + (iii) × $(p - q)$  

$A[(q - r) + (r - p) + (p - q)] + D[(p - 1)(q - r) + (q - 1)(r - p) + (r - 1)(p - q)] = a(q - r) + b(r - p) + c(p - q)$  

Simplifying gives $0 = a(q - r) + b(r - p) + c(p - q)$.

---

**Example 3:**  
Which term of the progression $19, 18\frac{1}{5}, 17\frac{2}{5}, ...$ is the first negative term?

Here $a = 19$, $d = 18\frac{1}{5} - 19 = -\frac{4}{5}$  

Let $T_n < 0$.  
$19 + (n - 1)(-\frac{4}{5}) < 0$  
$19 - \frac{4n}{5} + \frac{4}{5} < 0$  
$\frac{99}{5} - \frac{4n}{5} < 0$  
$\Rightarrow n > \frac{99}{4} = 24\frac{3}{4}$  
$\therefore n = 25$

---

**Example 4:**  
Find the sum of the series $101 + 99 + 97 + ... + 47$.

$a = 101, \ l = 47, \ d = -2$  

$47 = 101 + (n - 1)(-2)$  
$\Rightarrow 2n = 103 - 47 = 56 \Rightarrow n = 28$  

$S_{28} = \frac{28}{2}(101 + 47) = 14 \times 148 = 2072$

---

(Continue same format for remaining examples if needed.)

**Example 5:**  
The sums of $n$ terms of two arithmetic series are in the ratio $2n + 1 : 2n - 1$.  
Find the ratio of their 10th terms.

Let the two arithmetic series be $a, a + d, a + 2d, ...$ and $A, A + D, A + 2D, ...$

Given that,  
$\frac{\frac{n}{2}[2a + (n - 1)d]}{\frac{n}{2}[2A + (n - 1)D]} = \frac{2n + 1}{2n - 1}$  

$\Rightarrow \frac{2a + (n - 1)d}{2A + (n - 1)D} = \frac{2n + 1}{2n - 1}$

Ratio of the 10th terms of these series,  
$\frac{t_{10}}{T_{10}} = \frac{a + 9d}{A + 9D} = \frac{2a + 18d}{2A + 18D}$

Putting $n = 19$ in the given ratio,  
$\frac{t_{10}}{T_{10}} = \frac{2a + 18d}{2A + 18D} = \frac{2(19) + 1}{2(19) - 1} = \frac{39}{37}$

---

**Example 6:**  
The sum of the first $n$ terms of the A.P. $3, 5\frac{1}{2}, 8, ...$ is equal to the $2n^{th}$ term of the A.P. $16\frac{1}{2}, 28\frac{1}{2}, 40\frac{1}{2}, ...$  
Calculate the value of $n$.

For the A.P. $3, 5\frac{1}{2}, 8, ...$,  
$a = 3, \ d = 2\frac{1}{2} = \frac{5}{2}$  

$S_n = \frac{n}{2}[2a + (n - 1)d] = \frac{n}{2}[6 + (n - 1)\frac{5}{2}]$

For the second A.P. $16\frac{1}{2}, 28\frac{1}{2}, 40\frac{1}{2}, ...$,  
$a = 16\frac{1}{2} = \frac{33}{2}, \ d = 12$

$T_{2n} = a + (2n - 1)d = \frac{33}{2} + (2n - 1) \times 12$

Given $S_n = T_{2n}$,  
$\frac{n}{2}[6 + (n - 1)\frac{5}{2}] = \frac{33}{2} + (2n - 1)12$

Simplifying,  
$\frac{5n^2}{4} - \frac{89n}{4} - \frac{9}{2} = 0$  
$\Rightarrow 5n^2 - 89n - 18 = 0$  
$\Rightarrow (n - 18)(5n + 1) = 0$  
$\therefore n = 18$ (since $n > 0$)

---

**Example 7:**  
Let $a_1, a_2, a_3, ...$ be the terms of an A.P. If  
$\frac{a_1 + a_2 + ... + a_p}{a_1 + a_2 + ... + a_q} = \frac{p^2}{q^2} \ (p \neq q)$,  
then find $\frac{a_6}{a_{21}}$.  (AIEEE 2006)

Let $d$ be the common difference.

$\frac{S_p}{S_q} = \frac{\frac{p}{2}[2a_1 + (p - 1)d]}{\frac{q}{2}[2a_1 + (q - 1)d]} = \frac{p^2}{q^2}$  
$\Rightarrow \frac{2a_1 + (p - 1)d}{2a_1 + (q - 1)d} = \frac{p}{q}$

Simplifying,  
$d(p - q) = 2a_1(p - q) \Rightarrow d = 2a_1$

Now,  
$\frac{a_6}{a_{21}} = \frac{a_1 + 5d}{a_1 + 20d} = \frac{a_1 + 10a_1}{a_1 + 40a_1} = \frac{11a_1}{41a_1} = \frac{11}{41}$

---

**Example 8:**  
If the number of terms of an A.P. is $(2n + 1)$, find the ratio of the sum of the odd terms to the sum of the even terms.  (NDA/NA 2008)

Let the A.P. be  
$a, a + d, a + 2d, ..., a + (2n - 1)d, a + 2nd$

**Odd terms:** $a, a + 2d, a + 4d, ..., a + 2nd$ → $(n + 1)$ terms  
Sum of odd terms,  
$S_{odd} = \frac{n + 1}{2}[a + (a + 2nd)] = (n + 1)(a + nd)$

**Even terms:** $a + d, a + 3d, ..., a + (2n - 1)d$ → $n$ terms  
Sum of even terms,  
$S_{even} = \frac{n}{2}[(a + d) + (a + (2n - 1)d)] = n(a + nd)$

Hence,  
$\frac{S_{odd}}{S_{even}} = \frac{(n + 1)(a + nd)}{n(a + nd)} = \frac{n + 1}{n}$

---

**Example 9:**  
If the sum of the roots of the quadratic equation $ax^2 + bx + c = 0$  
is equal to the sum of the squares of their reciprocals,  
then show that $ab^2, ca^2, bc^2$ are in A.P.  (DCE)

Let the roots be $\alpha, \beta$.  
Then, $\alpha + \beta = -\frac{b}{a}$, $\alpha\beta = \frac{c}{a}$  

Given, $\alpha + \beta = \frac{1}{\alpha^2} + \frac{1}{\beta^2}$  

$\Rightarrow \alpha + \beta = \frac{\alpha^2 + \beta^2}{\alpha^2\beta^2} = \frac{(\alpha + \beta)^2 - 2\alpha\beta}{(\alpha\beta)^2}$  

Substitute:  
$-\frac{b}{a} = \frac{(-\frac{b}{a})^2 - 2\frac{c}{a}}{(\frac{c}{a})^2}$  

Simplifying,  
$-bc^2 = ab^2 - 2ca^2 \Rightarrow 2ca^2 = ab^2 + bc^2$  

Hence, $ab^2, ca^2, bc^2$ are in A.P.

---

**Example 10:**  
Find the value of $n$, if $\frac{a^{n+1} + b^{n+1}}{a^n + b^n}$ is the arithmetic mean between $a$ and $b$.  (WBJEE 2009)

Arithmetic mean between $a$ and $b$ is $\frac{a + b}{2}$

Given, $\frac{a + b}{2} = \frac{a^{n+1} + b^{n+1}}{a^n + b^n}$  

$\Rightarrow (a^n + b^n)(a + b) = 2(a^{n+1} + b^{n+1})$  
$\Rightarrow a^{n+1} + b^{n+1} = a^n b + b^n a$  
$\Rightarrow a^n(a - b) = b^n(a - b)$  

Since $a \neq b$,  
$a^n = b^n \Rightarrow \left(\frac{a}{b}\right)^n = 1 \Rightarrow n = 0$

---

**Example 11:**  
If $\log_{10} 2$, $\log_{10}(2^x - 1)$ and $\log_{10}(2^x + 3)$ are three consecutive terms of an A.P., find the value of $x$.  (AMU 2012)

Given,  
$\log_{10}(2^x - 1) - \log_{10} 2 = \log_{10}(2^x + 3) - \log_{10}(2^x - 1)$  

$\Rightarrow \log_{10}\left(\frac{2^x - 1}{2}\right) = \log_{10}\left(\frac{2^x + 3}{2^x - 1}\right)$  

$\Rightarrow \frac{2^x - 1}{2} = \frac{2^x + 3}{2^x - 1}$  

Simplifying,  
$2^{2x} - 2^{x+1} + 1 = 2^{x+1} + 6$  
$\Rightarrow 2^{2x} - 5 \cdot 2^x - 5 = 0$  
$\Rightarrow 2^x = 5$  
$\therefore x = \log_2 5$

**Ex. 12**
If $a_1, a_2, a_3, \ldots, a_n$ be an A.P. of non-zero terms, then find the sum:  
$\dfrac{1}{a_1 a_2} + \dfrac{1}{a_2 a_3} + \ldots + \dfrac{1}{a_{n-1} a_n}$  
*(AMU 2009)*

**Solution:**  
Let $a_2 - a_1 = a_3 - a_2 = \ldots = a_n - a_{n-1} = d$ (common difference).

$
\begin{aligned}
\frac{1}{a_1 a_2} + \frac{1}{a_2 a_3} + \ldots + \frac{1}{a_{n-1} a_n}
&= \frac{1}{d}\left[\frac{d}{a_1 a_2} + \frac{d}{a_2 a_3} + \ldots + \frac{d}{a_{n-1} a_n}\right] \\
&= \frac{1}{d}\left[\frac{a_2 - a_1}{a_1 a_2} + \frac{a_3 - a_2}{a_2 a_3} + \ldots + \frac{a_n - a_{n-1}}{a_{n-1} a_n}\right] \\
&= \frac{1}{d}\left[\frac{1}{a_1} - \frac{1}{a_2} + \frac{1}{a_2} - \frac{1}{a_3} + \ldots + \frac{1}{a_{n-1}} - \frac{1}{a_n}\right] \\
&= \frac{1}{d}\left[\frac{1}{a_1} - \frac{1}{a_n}\right]
= \frac{1}{d}\left[\frac{a_n - a_1}{a_1 a_n}\right]
= \frac{1}{d}\left[\frac{a_1 + (n - 1)d - a_1}{a_1 a_n}\right]
\end{aligned}
$

$\boxed{\frac{n - 1}{a_1 a_n}}$

---

**Ex. 13**. 
If the sides of a right-angled triangle form an A.P., find the sines of the acute angles.  
*(VITEE 2008)*

**Solution:**  
Let right-angled $\triangle ABC$ be right at $C$.  
Then sides are: $AB = c$, $BC = a$, $AC = b$.

Given: sides in A.P. $\Rightarrow a, b, c$ in A.P.$\\$
Let $a = x - d$, $b = x$, $c = x + d$ ($d > 0$ since $c$ is the largest side).

By Pythagoras theorem: $c^2 = a^2 + b^2$  
$
(x + d)^2 = (x - d)^2 + x^2
\Rightarrow x^2 + 2xd + d^2 = x^2 - 2xd + d^2 + x^2
\Rightarrow 4xd = x^2 \Rightarrow d = \frac{x}{4}
$

Hence,  
$a = x - \frac{x}{4} = \frac{3x}{4}$, $b = x$, $c = x + \frac{x}{4} = \frac{5x}{4}$

Now $C$ is the right angle, so $A$ and $B$ are acute.$\\$
$\sin A = \frac{a}{c} = \frac{\frac{3x}{4}}{\frac{5x}{4}} = \frac{3}{5}$, $\sin B = \frac{b}{c} = \frac{x}{\frac{5x}{4}} = \frac{4}{5}$

$\boxed{\sin A = \frac{3}{5},\; \sin B = \frac{4}{5}}$

---

## Ex. 14
$a_1, a_2, a_3, a_4, a_5$ are the first five terms of an A.P. such that  
$a_1 + a_3 + a_5 = -12$ and $a_1 \cdot a_2 \cdot a_3 = 8$.  
Find the first term and common difference.

**Solution:**  
Let  
$a_1 = a_3 - 2d$, $a_2 = a_3 - d$, $a_3 = a_3$, $a_4 = a_3 + d$, $a_5 = a_3 + 2d$

Given:  
$a_1 + a_3 + a_5 = -12$  
$\Rightarrow a_3 - 2d + a_3 + a_3 + 2d = -12$  
$\Rightarrow 3a_3 = -12 \Rightarrow a_3 = -4$

Also given: $a_1 \cdot a_2 \cdot a_3 = 8$

$
(a_3 - 2d)(a_3 - d)a_3 = 8
\Rightarrow (-4 - 2d)(-4 - d)(-4) = 8
\Rightarrow (-4 - 2d)(-4 - d) = -2
\Rightarrow (2 + d)(4 + d) = 1
\Rightarrow d^2 + 6d + 9 = 0
\Rightarrow d = -3
$

Then  
$a_1 = a_3 - 2d = -4 - 2(-3) = 2$

$\boxed{a_1 = 2, \; d = -3}$
