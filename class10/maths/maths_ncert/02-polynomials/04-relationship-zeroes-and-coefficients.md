---
layout: default
title: 2.3 Relationship between Zeroes and Coefficients of a Polynomial
nav_order: 4
parent: Chapter 2 - Polynomials
grand_parent: Class 10 Maths
mathjax: true
---

## 2.3 Relationship between Zeroes and Coefficients of a Polynomial

You have already seen that zero of a linear polynomial $ax+b$ is $-\dfrac{b}{a}$. We will now try to answer the question raised in Section 2.1 regarding the relationship between zeroes and coefficients of a quadratic polynomial.

For this, let us take a quadratic polynomial, say $p(x)=2x^2-8x+6$. In Class IX, you have learnt how to factorise quadratic polynomials by splitting the middle term. So, here we need to split the middle term $-8x$ as a sum of two terms, whose product is $6\times 2x^2 = 12x^2$. So, we write:

$$
2x^2-8x+6 = 2x^2-6x-2x+6 = 2x(x-3)-2(x-3)
= (2x-2)(x-3) = 2(x-1)(x-3).
$$

So, the value of $p(x)=2x^2-8x+6$ is zero when $x-1=0$ or $x-3=0$, i.e., when $x=1$ or $x=3$. So, the zeroes of $2x^2-8x+6$ are $1$ and $3$. Observe that:

$$
\text{Sum of its zeroes} = 1+3 = 4 = -\frac{-8}{2}.
$$

$$
\text{Product of its zeroes} = 1\times 3 = 3 = \frac{6}{2}.
$$

Let us take one more quadratic polynomial, say, $p(x)=3x^2+5x-2$. By the method of splitting the middle term,

$$
3x^2+5x-2 = 3x^2+6x-x-2 = 3x(x+2)-1(x+2) = (3x-1)(x+2).
$$

Hence, the value of $3x^2+5x-2$ is zero when either $3x-1=0$ or $x+2=0$, i.e., when $x=\dfrac{1}{3}$ or $x=-2$. So, the zeroes of $3x^2+5x-2$ are $\dfrac{1}{3}$ and $-2$. Observe that:

$$
\text{Sum of its zeroes} = \frac{1}{3}+(-2) = -\frac{5}{3}.
$$

$$
\text{Product of its zeroes} = \frac{1}{3}\times (-2) = -\frac{2}{3}.
$$

In general, if $\alpha$ and $\beta$ are the zeroes of the quadratic polynomial $p(x)=ax^2+bx+c$, $a\ne 0$, then you know that $x-\alpha$ and $x-\beta$ are the factors of $p(x)$. Therefore,

$$
ax^2+bx+c = k(x-\alpha)(x-\beta),\ \text{where $k$ is a constant}
$$

$$
= k\left[x^2-(\alpha+\beta)x+\alpha\beta\right]
= kx^2-k(\alpha+\beta)x+k\alpha\beta.
$$

Comparing the coefficients of $x^2$, $x$ and constant terms on both the sides, we get $a=k$, $b=-k(\alpha+\beta)$ and $c=k\alpha\beta$.

This gives:

$$
\alpha+\beta=-\frac{b}{a},\qquad \alpha\beta=\frac{c}{a}.
$$

Let us consider some examples.

### Example 2

Find the zeroes of the quadratic polynomial $x^2+7x+10$, and verify the relationship between the zeroes and the coefficients.

### Solution

We have:

$$
x^2+7x+10 = (x+2)(x+5).
$$

So, the value of $x^2+7x+10$ is zero when $x+2=0$ or $x+5=0$, i.e., when $x=-2$ or $x=-5$. Therefore, the zeroes of $x^2+7x+10$ are $-2$ and $-5$.

### Example 3

Find the zeroes of the polynomial $x^2-3$ and verify the relationship between the zeroes and the coefficients.

### Solution

Recall the identity $a^2-b^2=(a-b)(a+b)$. Using it, we can write:

$$
x^2-3 = (x-\sqrt{3})(x+\sqrt{3}).
$$

So, the value of $x^2-3$ is zero when $x=\sqrt{3}$ or $x=-\sqrt{3}$. Therefore, the zeroes of $x^2-3$ are $\sqrt{3}$ and $-\sqrt{3}$.

### Example 4

Find a quadratic polynomial, the sum and product of whose zeroes are $-3$ and $2$, respectively.

### Solution

Let the quadratic polynomial be $ax^2+bx+c$, and its zeroes be $\alpha$ and $\beta$. We have $\alpha+\beta=-3=-\dfrac{b}{a}$ and $\alpha\beta=2=\dfrac{c}{a}$. If $a=1$, then $b=3$ and $c=2$. So, one quadratic polynomial which fits the given conditions is $x^2+3x+2$.

You can check that any other quadratic polynomial that fits these conditions will be of the form $k(x^2+3x+2)$, where $k$ is real.

Let us now look at cubic polynomials. Do you think a similar relation holds between the zeroes of a cubic polynomial and its coefficients?

Let us consider $p(x)=2x^3-5x^2-14x+8$. You can check that $p(x)=0$ for $x=4$, $-2$, $\dfrac{1}{2}$. Since $p(x)$ can have at most three zeroes, these are the zeroes of $2x^3-5x^2-14x+8$. Now,

$$
\text{sum of the zeroes} = 4+(-2)+\frac{1}{2}=\frac{5}{2}=-\frac{-5}{2},
$$

$$
\text{product of the zeroes} = 4\times(-2)\times\frac{1}{2}=-4=-\frac{8}{2}.
$$

However, there is one more relationship here. Consider the sum of the products of the zeroes taken two at a time:

$$
\{4\times(-2)\} + \left\{(-2)\times\frac{1}{2}\right\} + \left\{\frac{1}{2}\times 4\right\}
= -8-1+2=-7=\frac{-14}{2}.
$$

In general, it can be proved that if $\alpha$, $\beta$, $\gamma$ are the zeroes of the cubic polynomial $ax^3+bx^2+cx+d$, then

$$
\alpha+\beta+\gamma=-\frac{b}{a},
$$

$$
\alpha\beta+\beta\gamma+\gamma\alpha=\frac{c}{a},
$$

$$
\alpha\beta\gamma=-\frac{d}{a}.
$$

Let us consider an example.

### Example 5* (Not from the examination point of view)

Verify that $3$, $-1$, $-\dfrac{1}{3}$ are the zeroes of the cubic polynomial $p(x)=3x^3-5x^2-11x-3$, and then verify the relationship between the zeroes and the coefficients.

