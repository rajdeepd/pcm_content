---
layout: default
title: MSET - Sequence and Series -> One Pager
nav_order: 12
description: ""
has_children: true
parent: Index MSET
grand_parent: Home
tags: [MathJax, Mathematic]
mathjax: true
---

# Arithmetic Progression (A.P.) — Summary

---

### 🔹 Definition
An **Arithmetic Progression (A.P.)** is a sequence of numbers where the difference between consecutive terms is constant.

If the first term is $a$ and the common difference is $d$,  
then the general form is:  
$a, \ a+d, \ a+2d, \ a+3d, \ ...$

---

### 🔹 Key Formulas
- $n^{th}$ term: $T_n = a + (n - 1)d$
- Common difference: $d = T_n - T_{n-1}$
- Last term: $l = a + (n - 1)d$
- Sum of $n$ terms: $S_n = \frac{n}{2}(2a + (n - 1)d) = \frac{n}{2}(a + l)$

---

### 🔹 Arithmetic Mean (A.M.)
If $x$ is inserted between $a$ and $b$ such that $a, x, b$ are in A.P.,  
then $x = \frac{a + b}{2}$.

If $n$ A.M.s are inserted between $a$ and $b$,  
$d = \frac{b - a}{n + 1}$ and the sequence becomes  
$a, a+d, a+2d, ..., b$.

---

### 🔹 Basic Properties
- $a, b, c$ are in A.P. if and only if $2b = a + c$
- Adding, subtracting, multiplying or dividing each term by the same constant gives another A.P.
- For odd number of terms: take $a$ as middle term, e.g. $a - 2d, a - d, a, a + d, a + 2d$
- For even number of terms: take $a - d, a + d$ as middle terms

---

### 🧩 **Worked Examples**

**Example 1:**  
8th term = 23, 102nd term = 305. Find the A.P.  
We know $T_n = a + (n - 1)d$.  
From $T_8 = 23$: $a + 7d = 23$  
From $T_{102} = 305$: $a + 101d = 305$  
Subtract: $94d = 282 \Rightarrow d = 3$.  
Then $a = 23 - 21 = 2$.  
✅ Series: 2, 5, 8, 11, ...

---

**Example 2:**  
If $a, b, c$ are the $p^{th}, q^{th}, r^{th}$ terms of an A.P., show that  
$a(q - r) + b(r - p) + c(p - q) = 0$.

Let first term = $A$, common difference = $D$.  
$a = A + (p - 1)D$, $b = A + (q - 1)D$, $c = A + (r - 1)D$.  
Multiply each by $(q - r), (r - p), (p - q)$ and add.  
All $A$ and $D$ terms cancel.  
✅ Hence, the sum = 0.

---

**Example 3:**  
Which term of $19, 18\frac{1}{5}, 17\frac{2}{5}, ...$ is the first negative?  
Here $a = 19$, $d = -\frac{4}{5}$.  
We need $a + (n - 1)d < 0$.  
$19 - \frac{4(n - 1)}{5} < 0 \Rightarrow n > 24.75$.  
✅ So, 25th term is the first negative.

---

**Example 4:**  
Find the sum of the series $101 + 99 + 97 + ... + 47$.  
$a = 101$, $l = 47$, $d = -2$.  
Find $n$: $47 = 101 + (n - 1)(-2) \Rightarrow n = 28$.  
$S_n = \frac{n}{2}(a + l) = 14(148) = 2072$.  
✅ Sum = 2072.

---

**Example 5:**  
The sums of $n$ terms of two A.P.s are in ratio $(2n + 1):(2n - 1)$.  
Find ratio of their 10th terms.  

Let A.P.s be $a, a+d,...$ and $A, A+D,...$  
$\frac{S_1}{S_2} = \frac{2n + 1}{2n - 1}$  
$\Rightarrow \frac{2a + (n - 1)d}{2A + (n - 1)D} = \frac{2n + 1}{2n - 1}$.  
For 10th term, put $n = 19$:  
$\frac{a + 9d}{A + 9D} = \frac{39}{37}$.  
✅ Ratio = 39 : 37.

---

**Example 6:**  
Sum of $n$ terms of $3, 5.5, 8, ...$ equals $2n^{th}$ term of $16.5, 28.5, 40.5, ...$  
Find $n$.  
For 1st A.P.: $a = 3$, $d = 2.5$  
$S_n = \frac{n}{2}[6 + (n - 1)2.5]$  
For 2nd A.P.: $a = 16.5$, $d = 12$  
$T_{2n} = 16.5 + (2n - 1)12$  
Equating: $S_n = T_{2n}$ gives $5n^2 - 89n - 18 = 0$.  
✅ $n = 18$.

---

**Example 7:**  
If $\frac{a_1 + a_2 + ... + a_p}{a_1 + a_2 + ... + a_q} = \frac{p^2}{q^2}$,  
find $\frac{a_6}{a_{21}}$.  
$\frac{S_p}{S_q} = \frac{p^2}{q^2} \Rightarrow \frac{2a_1 + (p - 1)d}{2a_1 + (q - 1)d} = \frac{p}{q}$.  
Simplify: $d = 2a_1$.  
Then $\frac{a_6}{a_{21}} = \frac{a_1 + 5d}{a_1 + 20d} = \frac{11}{41}$.  
✅ Ratio = 11 : 41.

---

**Example 8:**  
If an A.P. has $(2n + 1)$ terms, find $\frac{\text{Sum of odd terms}}{\text{Sum of even terms}}$.  
Odd terms: $(n + 1)$ terms, sum = $(n + 1)(a + nd)$  
Even terms: $n$ terms, sum = $n(a + nd)$  
✅ Ratio = $\frac{n + 1}{n}$.

---

**Example 9:**  
If sum of roots of $ax^2 + bx + c = 0$ equals sum of squares of their reciprocals,  
show $ab^2, ca^2, bc^2$ are in A.P.  

Let roots = $\alpha, \beta$.  
$\alpha + \beta = -\frac{b}{a}$, $\alpha\beta = \frac{c}{a}$.  
Given $\alpha + \beta = \frac{1}{\alpha^2} + \frac{1}{\beta^2}$.  
Simplify: $-bc^2 = ab^2 - 2ca^2 \Rightarrow 2ca^2 = ab^2 + bc^2$.  
✅ Hence $ab^2, ca^2, bc^2$ are in A.P.

---

**Example 10:**  
If $\frac{a^{n+1} + b^{n+1}}{a^n + b^n}$ is A.M. of $a,b$, find $n$.  
$\frac{a+b}{2} = \frac{a^{n+1} + b^{n+1}}{a^n + b^n}$  
Simplify: $(a^n + b^n)(a + b) = 2(a^{n+1} + b^{n+1})$  
$\Rightarrow a^n(a - b) = b^n(a - b)$.  
Since $a \neq b$, $a^n = b^n \Rightarrow n = 0$.  
✅ $n = 0$.

---

**Example 11:**  
If $\log_{10} 2, \log_{10}(2^x - 1), \log_{10}(2^x + 3)$ are consecutive A.P. terms, find $x$.  
$\log(2^x - 1) - \log 2 = \log(2^x + 3) - \log(2^x - 1)$  
Simplify: $\frac{2^x - 1}{2} = \frac{2^x + 3}{2^x - 1}$  
$\Rightarrow 2^{2x} - 5 \cdot 2^x - 5 = 0 \Rightarrow 2^x = 5$.  
✅ $x = \log_2 5$.
