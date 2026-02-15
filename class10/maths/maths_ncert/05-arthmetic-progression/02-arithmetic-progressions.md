---
layout: default
title: 5.2 Arithmetic Progressions
nav_order: 2
parent: Chapter 5 - Arithmetic Progressions
grand_parent: Class 10 Maths
mathjax: true
---

## 5.2 Arithmetic Progressions

Consider the following lists of numbers :

- (i) 1, 2, 3, 4, . . .
- (ii) 100, 70, 40, 10, . . .
- (iii) – 3, –2, –1, 0, . . .
- (iv) 3, 3, 3, 3, . . .
- (v) –1.0, –1.5, –2.0, –2.5, . . .

Each of the numbers in the list is called a **term**.

Given a term, can you write the next term in each of the lists above? If so, how will you write it? Perhaps by following a pattern or rule. Let us observe and write the rule.

- In (i), each term is 1 more than the term preceding it.
- In (ii), each term is 30 less than the term preceding it.
- In (iii), each term is obtained by adding 1 to the term preceding it.
- In (iv), all the terms in the list are 3, i.e., each term is obtained by adding (or subtracting) 0 to the term preceding it.
- In (v), each term is obtained by adding – 0.5 to (i.e., subtracting 0.5 from) the term preceding it.

In all the lists above, we see that successive terms are obtained by adding a fixed number to the preceding terms. Such list of numbers is said to form an **Arithmetic Progression (AP)**.

So, an **arithmetic progression** is a list of numbers in which each term is obtained by adding a fixed number to the preceding term except the first term.

This fixed number is called the **common difference** of the AP. Remember that it can be positive, negative or zero.

Let us denote the first term of an AP by $a_1$, second term by $a_2$, . . ., $n$th term by $a_n$ and the common difference by $d$. Then the AP becomes $a_1$, $a_2$, $a_3$, . . ., $a_n$.  
So, $a_2 – a_1 = a_3 – a_2 = \ldots = a_n – a_{n–1} = d$.

Some more examples of AP are:

- **(a)** The heights (in cm) of some students of a school standing in a queue in the morning assembly are 147, 148, 149, . . ., 157.
- **(b)** The minimum temperatures (in degree celsius) recorded for a week in the month of January in a city, arranged in ascending order are  
  – 3.1, – 3.0, – 2.9, – 2.8, – 2.7, – 2.6, – 2.5
- **(c)** The balance money (in ₹) after paying 5% of the total loan of ₹ 1000 every month is 950, 900, 850, 800, . . ., 50.
- **(d)** The cash prizes (in ₹) given by a school to the toppers of Classes I to XII are, respectively, 200, 250, 300, 350, . . ., 750.
- **(e)** The total savings (in ₹) after every month for 10 months when ₹ 50 are saved each month are 50, 100, 150, 200, 250, 300, 350, 400, 450, 500.

It is left as an exercise for you to explain why each of the lists above is an AP.

You can see that  
$$a,\; a + d,\; a + 2d,\; a + 3d,\; \ldots$$  
represents an arithmetic progression where $a$ is the first term and $d$ the common difference. This is called the **general form of an AP**.

Note that in examples (a) to (e) above, there are only a finite number of terms. Such an AP is called a **finite AP**. Also note that each of these Arithmetic Progressions (APs) has a last term. The APs in examples (i) to (v) in this section, are not finite APs and so they are called **infinite Arithmetic Progressions**. Such APs do not have a last term.

Now, to know about an AP, what is the minimum information that you need? Is it enough to know the first term? Or, is it enough to know only the common difference? You will find that you will need to know both – the first term $a$ and the common difference $d$.

For instance if the first term $a$ is 6 and the common difference $d$ is 3, then the AP is  
6, 9, 12, 15, . . .  
and if $a$ is 6 and $d$ is – 3, then the AP is  
6, 3, 0, –3, . . .

Similarly, when  
- $a = –7$, $d = –2$, the AP is – 7, – 9, – 11, – 13, . . .
- $a = 1.0$, $d = 0.1$, the AP is 1.0, 1.1, 1.2, 1.3, . . .
- $a = 0$, $d = 1\frac{1}{2}$, the AP is $0,\; 1\frac{1}{2},\; 3,\; 4\frac{1}{2},\; 6,\; \ldots$
- $a = 2$, $d = 0$, the AP is 2, 2, 2, 2, . . .

So, if you know what $a$ and $d$ are, you can list the AP. What about the other way round? That is, if you are given a list of numbers can you say that it is an AP and then find $a$ and $d$? Since $a$ is the first term, it can easily be written. We know that in an AP, every succeeding term is obtained by adding $d$ to the preceding term. So, $d$ found by subtracting any term from its succeeding term, i.e., the term which immediately follows it should be same for an AP.

For example, for the list of numbers : 6, 9, 12, 15, . . .,  
We have $a_2 – a_1 = 9 – 6 = 3$, $a_3 – a_2 = 12 – 9 = 3$, $a_4 – a_3 = 15 – 12 = 3$.  
Here the difference of any two consecutive terms in each case is 3. So, the given list is an AP whose first term $a$ is 6 and common difference $d$ is 3.

For the list of numbers : 6, 3, 0, – 3, . . .,  
$a_2 – a_1 = 3 – 6 = –3$, $a_3 – a_2 = 0 – 3 = –3$, $a_4 – a_3 = –3 – 0 = –3$.  
Similarly this is also an AP whose first term is 6 and the common difference is –3.

In general, for an AP $a_1$, $a_2$, . . ., $a_n$, we have  
$$d = a_{k+1} – a_k$$  
where $a_{k+1}$ and $a_k$ are the $(k + 1)$th and the $k$th terms respectively.

To obtain $d$ in a given AP, we need not find all of $a_2 – a_1$, $a_3 – a_2$, $a_4 – a_3$, . . . . It is enough to find only one of them.

Consider the list of numbers 1, 1, 2, 3, 5, . . . . By looking at it, you can tell that the difference between any two consecutive terms is not the same. So, this is not an AP.

Note that to find $d$ in the AP : 6, 3, 0, – 3, . . ., we have subtracted 6 from 3 and not 3 from 6, i.e., we should subtract the $k$th term from the $(k + 1)$th term even if the $(k + 1)$th term is smaller.

Let us make the concept more clear through some examples.

<div class="example" markdown="1">

### Example 1

For the AP : $\frac{3}{2},\; \frac{1}{2},\; -\frac{1}{2},\; -\frac{3}{2},\; \ldots$, write the first term $a$ and the common difference $d$.

**Solution :** Here, $a = \frac{3}{2}$, $d = \frac{1}{2} – \frac{3}{2} = –1$.

Remember that we can find $d$ using any two consecutive terms, once we know that the numbers are in AP.

</div>

<div class="example" markdown="1">

### Example 2

Which of the following list of numbers form an AP? If they form an AP, write the next two terms :

- (i) 4, 10, 16, 22, . . .
- (ii) 1, – 1, – 3, – 5, . . .
- (iii) – 2, 2, – 2, 2, – 2, . . .
- (iv) 1, 1, 1, 2, 2, 2, 3, 3, 3, . . .

**Solution :**

**(i)** We have $a_2 – a_1 = 10 – 4 = 6$, $a_3 – a_2 = 16 – 10 = 6$, $a_4 – a_3 = 22 – 16 = 6$.  
i.e., $a_{k+1} – a_k$ is the same every time. So, the given list of numbers forms an AP with the common difference $d = 6$. The next two terms are: 22 + 6 = 28 and 28 + 6 = 34.

**(ii)** $a_2 – a_1 = –1 – 1 = –2$, $a_3 – a_2 = –3 – (–1) = –2$, $a_4 – a_3 = –5 – (–3) = –2$.  
i.e., $a_{k+1} – a_k$ is the same every time. So, the given list of numbers forms an AP with the common difference $d = –2$. The next two terms are: –5 + (–2) = –7 and –7 + (–2) = –9.

**(iii)** $a_2 – a_1 = 2 – (–2) = 4$, $a_3 – a_2 = –2 – 2 = –4$.  
As $a_2 – a_1 \neq a_3 – a_2$, the given list of numbers does not form an AP.

**(iv)** $a_2 – a_1 = 1 – 1 = 0$, $a_3 – a_2 = 1 – 1 = 0$, $a_4 – a_3 = 2 – 1 = 1$.  
Here, $a_2 – a_1 = a_3 – a_2 \neq a_4 – a_3$. So, the given list of numbers does not form an AP.

</div>

---

## EXERCISE 5.1 {#exercise-51}

1. In which of the following situations, does the list of numbers involved make an arithmetic progression, and why?
   - **(i)** The taxi fare after each km when the fare is ₹ 15 for the first km and ₹ 8 for each additional km.
   - **(ii)** The amount of air present in a cylinder when a vacuum pump removes $\frac{1}{4}$ of the air remaining in the cylinder at a time.
   - **(iii)** The cost of digging a well after every metre of digging, when it costs ₹ 150 for the first metre and rises by ₹ 50 for each subsequent metre.
   - **(iv)** The amount of money in the account every year, when ₹ 10000 is deposited at compound interest at 8% per annum.

2. Write first four terms of the AP, when the first term $a$ and the common difference $d$ are given as follows:
   - **(i)** $a = 10$, $d = 10$
   - **(ii)** $a = –2$, $d = 0$
   - **(iii)** $a = 4$, $d = –3$
   - **(iv)** $a = –1$, $d = \frac{1}{2}$
   - **(v)** $a = –1.25$, $d = –0.25$

3. For the following APs, write the first term and the common difference:
   - **(i)** 3, 1, – 1, – 3, . . .
   - **(ii)** – 5, – 1, 3, 7, . . .
   - **(iii)** $\frac{1}{3},\; \frac{5}{3},\; \frac{9}{3},\; \frac{13}{3},\; \ldots$
   - **(iv)** 0.6, 1.7, 2.8, 3.9, . . .

4. Which of the following are APs? If they form an AP, find the common difference $d$ and write three more terms.
   - **(i)** 2, 4, 8, 16, . . .
   - **(ii)** $2,\; \frac{5}{2},\; 3,\; \frac{7}{2},\; \ldots$
   - **(iii)** – 1.2, – 3.2, – 5.2, – 7.2, . . .
   - **(iv)** – 10, – 6, – 2, 2, . . .
   - **(v)** $3,\; 3 + \sqrt{2},\; 3 + 2\sqrt{2},\; 3 + 3\sqrt{2},\; \ldots$
   - **(vi)** 0.2, 0.22, 0.222, 0.2222, . . .
   - **(vii)** 0, – 4, – 8, –12, . . .
   - **(viii)** $-\frac{1}{2},\; -\frac{1}{2},\; -\frac{1}{2},\; -\frac{1}{2},\; \ldots$
   - **(ix)** 1, 3, 9, 27, . . .
   - **(x)** $a$, $2a$, $3a$, $4a$, . . .
   - **(xi)** $a$, $a^2$, $a^3$, $a^4$, . . .
   - **(xii)** $\sqrt{2},\; \sqrt{8},\; \sqrt{18},\; \sqrt{32},\; \ldots$
   - **(xiii)** $\sqrt{3},\; \sqrt{6},\; \sqrt{9},\; \sqrt{12},\; \ldots$
   - **(xiv)** $1^2,\; 3^2,\; 5^2,\; 7^2,\; \ldots$
   - **(xv)** $1^2,\; 5^2,\; 7^2,\; 73,\; \ldots$
