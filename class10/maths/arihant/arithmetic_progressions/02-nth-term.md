---
layout: default
title: nth Term of an AP
nav_order: 2
parent: Arithmetic Progressions
mathjax: true
---

# TOPIC 02: nth Term of an AP

## Formula for the nth Term

The $n$th term of an AP is given by:

$$a_n = a + (n-1)d$$

Where:
- $a_n$ = $n$th term
- $a$ = first term
- $n$ = position of the term
- $d$ = common difference

## nth Term from the End of an AP

If an AP has $n$ terms, then the $m^{th}$ term from the end is:

$$a_m = l - (m-1)d$$

Where:
- $l$ = last term
- $m$ = position from the end
- $d$ = common difference

Alternatively:
$$a_m = a + (n - m)d$$

---

## Solved Examples

### Example 1: Find the 20th term of the AP: $7, 3, -1, -5, \ldots$

**Solution:**

Given AP is $7, 3, -1, -5, \ldots$

Here, $a = 7$ and $d = 3 - 7 = -4$

Since, $n$th term, $a_n = a + (n-1)d$

On putting $n = 20$, we get:

$a_{20} = a + (20-1)d = 7 + 19(-4) = 7 - 76 = -69$

Hence, 20th term of given sequence is $\mathbf{-69}$.

---

## Types of Problems Based on nth Term of an AP

### Type I: Finding $n$, when $n$th Term or Last Term of an AP are Given

In this type of problems, an AP with last term is given or AP containing $n$ terms is given (or $n$th term of an AP is given) and we have to find the value of $n$.

---

### Example 2: How many terms are there in the AP $3, 6, 9, 12, \ldots, 111$?

**Solution:**

Given AP is $3, 6, 9, 12, \ldots, 111$

Here, $a = 3$ and $d = 6 - 3 = 3$

Let there be $n$ terms in the given AP.

Then, $n$th term $= 111$

$\Rightarrow a + (n-1)d = 111$ $\quad [\because a_n = a + (n-1)d]$

$\Rightarrow 3 + (n-1) \times 3 = 111$

$\Rightarrow 3(1 + n - 1) = 111$

$\Rightarrow 3n = 111$

$\Rightarrow n = \frac{111}{3} = 37$

Hence, the given AP contains **37 terms**.

---

### Example 3: Which term of the AP $21, 18, 15, \ldots$ is $-81$? Also, is any term 0? Give reason.

*[CBSE 2024 Basic]*

**Solution:**

Given AP is $21, 18, 15, \ldots$

Here, $a = 21$ and $d = 18 - 21 = -3$

Let $n$th term of given AP be $-81$.

Then, $a_n = -81$

$\Rightarrow a + (n-1)d = -81$ $\quad [\because a_n = a + (n-1)d]$

On putting the values of $a$ and $d$, we get:

$21 + (n-1)(-3) = -81$

$\Rightarrow 21 - 3n + 3 = -81$

$\Rightarrow 24 - 3n = -81$

$\Rightarrow -3n = -81 - 24 = -105$

$\Rightarrow n = \frac{-105}{-3} = 35$

Hence, **35th term** of given AP is $-81$.

**Is any term 0?**

Now, we want to know if there is any $n$ for which $a_n = 0$.

If such $n$ exists, then:

$21 + (n-1)(-3) = 0$

$\Rightarrow 3(n-1) = 21$

$\Rightarrow n - 1 = 7$

$\Rightarrow n = 8$

So, **eighth term is 0**.

---

### Example 4: Check whether 200 is a term of the list of numbers $7, 11, 15, 19, \ldots$

**Solution:**

Given list of numbers: $7, 11, 15, 19, \ldots$

Here, $11 - 7 = 15 - 11 = 19 - 15 = 4$

So, it is an AP with first term $a = 7$ and common difference $d = 4$

Let 200 be the $n$th term of this AP.

We know that $a_n = a + (n-1)d$

$\therefore 200 = 7 + (n-1)(4)$

$\Rightarrow 193 = (n-1)(4)$

$\Rightarrow n - 1 = \frac{193}{4}$

$\Rightarrow n = \frac{197}{4} = 49\frac{1}{4}$

But the number of terms cannot be a fraction.

$\therefore$ **200 is not a term** of the given AP.

---

### Example 5: Which term of the AP $3, 15, 27, 39, \ldots$ will be 120 more than its 21st term?

*[CBSE 2019]*

**Solution:**

Given AP is $3, 15, 27, 39, \ldots$

Here, $a = 3$ and $d = 15 - 3 = 12$

∴ 21st term is given by:

$T_{21} = a + (21-1)d = a + 20d = 3 + 20 \times 12 = 243$

Required term $= 243 + 120 = 363$

Let it be $n$th term.

Then, $T_n = 363$

$\Rightarrow a + (n-1)d = 363$

$\Rightarrow 3 + (n-1) \times 12 = 363$

$\Rightarrow (n-1) \times 12 = 360$

$\Rightarrow n - 1 = 30$

$\Rightarrow n = 31$

Hence, **31st term** is the required term.

---

### Type II: Finding the AP or nth Term or Both, when Two Terms are Given

In this type of problems, two terms (or relation between two terms of an AP) are given and we have to find the AP and $n$th term of AP.

---

### Example 6: Determine the AP whose 3rd term is 5 and the 7th term is 9.

*[CBSE 2024 Standard]*

**Solution:**

We have:

$a_3 = a + (3-1)d = a + 2d = 5$ ... (i)

$a_7 = a + (7-1)d = a + 6d = 9$ ... (ii)

Subtracting (i) from (ii):

$4d = 4 \Rightarrow d = 1$

Substituting in (i): $a + 2(1) = 5 \Rightarrow a = 3$

Hence, the required AP is $\mathbf{3, 4, 5, 6, \ldots}$

---

### Example 7: If $p^{th}$  term of an AP is $q$ and $q$th term is $p$, then prove that its $n^{th}$ term is $(p + q - n)$.

*[CBSE 2023 Standard]*

**Solution:**

Given: $p$th term of AP $= q$ and $q$th term of AP $= p$

To prove: $n$th term of AP $= p + q - n$

Let $a$ be the first term and $d$ be the common difference of the AP.

Since $p$th term is $q$:

$a_p = q \Rightarrow a + (p-1)d = q$ ... (i)

Similarly, $q$th term is $p$:

$a_q = p \Rightarrow a + (q-1)d = p$ ... (ii)

Subtracting (ii) from (i):

$(p-1)d - (q-1)d = q - p$

$\Rightarrow (p - q)d = q - p = -(p - q)$

$\Rightarrow d = -1$

Substituting in (i): $a + (p-1)(-1) = q$

$\Rightarrow a = q + p - 1$

Now, $n$th term:

$a_n = a + (n-1)d = (q + p - 1) + (n-1)(-1)$

$= p + q - 1 - n + 1 = p + q - n$
Hence, **$n^{th}$  term = p + q - n** ✓
