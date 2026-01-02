---
layout: default
title: 07. Electric Current
nav_order: 7
description: ""
parent: Cengage Electricity
grand_parent: Class 10 Physics
tags: [MathJax, Mathematic]
mathjax: true
---

# 07. Electric Current

## Definition of Current

The time rate of flow of charge through any cross section in a particular direction is called current:

$$i = \lim_{\Delta t \to 0} \frac{\Delta Q}{\Delta t}$$

If flow is uniform, then:

$$i = \frac{Q}{t}$$

Current is a scalar quantity.

**Units:**
* Its SI unit is ampere (A)
* CGS unit is emu called Biot (Bi)
* $1 \text{ A} = \frac{1}{10} \text{ Bi}$

---

## Conventional Direction of Current

The conventional direction of current is taken to be the direction of flow of positive charge, i.e., in the direction of electric field, and is opposite to the direction of flow of negative charge as shown below.

> **📷 TODO - Image Needed:** `07-fig1.png`  
> **Description:** Conventional direction of current diagram showing horizontal cylindrical conductor with positive charges flowing right, negative charges flowing left, current arrow above, electric field arrow below  
> **Source:** `page_14.jpg`  
> **Size:** 60% width

**Key Points:**
* The net charge in a current-carrying conductor is zero.
* Conventional current flows in the direction of positive charge movement
* Actual electron flow is opposite to conventional current direction

---

## Definition of 1 Ampere of Current

1 ampere is the electric current flowing through a conducting wire when 1 coulomb charge flows through it in 1 second.

$$1 \text{ ampere} = \frac{1 \text{ coulomb}}{1 \text{ sec}} = 1 \text{ Cs}^{-1}$$

**Alternative Definition:** 1 ampere of current means the flow of $6.25 \times 10^{18}$ electrons/sec through any cross section of the conductor.

---

## 7.1 Two Types of Current

Current is of two types: (i) direct current (DC), and (ii) alternating current (AC).

### Difference between AC and DC

**Alternating Current (AC):**
* **(i)** Direction of current changes after regular interval.
* **(ii)** Shows only heating effect.
* **(iv)** Symbol: ~ (wavy line)

> **📷 TODO - Image Needed:** `07-fig2.png`  
> **Description:** AC graphs showing sine wave and square wave graphs with positive/negative cycles labeled  
> **Source:** `page_14.jpg`  
> **Size:** 60% width

**Direct Current (DC):**
* **(i)** Direction of current do not change with time.
* **(iii)** Shows heating effect, chemical effect, and magnetic effect of current.
* **(iv)** Symbol: — (long line) and — (short line), representing positive and negative terminals

> **📷 TODO - Image Needed:** `07-fig3.png`  
> **Description:** DC graphs showing rectified sine wave and constant current graphs  
> **Source:** `page_14.jpg`  
> **Size:** 60% width

**Note:** AC → Rectifier → DC (rectifier converts AC to DC)  
**Note:** DC → Inverter → AC (inverter converts DC to AC)

---

## Current in Conductors

For a given conductor, the current does not change with changes in cross-sectional areas.

> **📷 TODO - Image Needed:** `07-fig4.png`  
> **Description:** Current in conductors with varying cross-sections - three cylindrical segments connected in series with arrows $i_1$, $i_2$, $i_3$ indicating constant current  
> **Source:** `page_15.jpg`  
> **Size:** 60% width

**Formulas for Current:**

* If $n$ particles each having a charge $q$ pass through a given area in time $t$, then:
  $$i = \frac{nq}{t}$$

* If $n$ particles each having a charge $q$ pass per second per unit area, then the current associated with the cross-sectional area $A$ is:
  $$i = nqA$$

* If there are $n$ particles per unit volume each having a charge $q$ and moving with velocity $v$, then the current through the cross-sectional area $A$ is:
  $$i = nqvA$$

---

## Current Carriers

The charged particles, whose flow is in a definite direction, constitute the electric current and are called current carriers. In different situations, current carriers are different.

> **📷 TODO - Image Needed:** `07-fig5.png`  
> **Description:** Current carriers diagram showing oval shape with positive charges around and inside, arrows indicating flow  
> **Source:** `page_15.jpg`  
> **Size:** 60% width

* **(i) Solids:** In solid conductors like metals, current carriers are free electrons.
* **(ii) Liquids:** In liquids, current carriers are positive and negative ions.
* **(iii) Gases:** In gases, current carriers are positive ions and free electrons.
* **(iv) Semiconductor:** In semiconductors, current carriers are holes and free electrons.

---

## INSIGHTS

**Skin Effect:** DC flows uniformly throughout the cross section of conductor, whereas AC mainly flows through the outer surface area of the conductor. This is known as SKIN EFFECT.

---

## Examples

### Example 15

**Problem:** Calculate the current flowing through a conductor when a charge $q$ travels a length $l$ with velocity $v$.

> **📷 TODO - Image Needed:** `07-fig6.png`  
> **Description:** Cylindrical conductor diagram with length $l$, charge $q$ entering, velocity $v$ m/s, and "i = ?" below  
> **Source:** `page_22.jpg`  
> **Size:** 60% width

**Solution:**

From the definition of current: $i = \frac{q}{t}$

The time taken for charge to travel length $l$: $v = \frac{l}{t}$, therefore $t = \frac{l}{v}$

Substituting into the current formula:

$$i = \frac{q}{l/v} = \frac{qv}{l}$$

**Answer:** The current flowing through the conductor is $i = \frac{qv}{l}$.

---

### Example 16

**Problem:** Determine the strength of the current when an electron of charge $e$ moves in a circular orbit at a frequency of $n$ revolutions per second.

> **📷 TODO - Image Needed:** `07-fig7.png`  
> **Description:** Circular orbit diagram (oval shape) with point P marked on circumference  
> **Source:** `page_22.jpg`  
> **Size:** 60% width

**Solution:**

Current is defined as the rate of flow of charge: $i = \frac{q}{t}$

Consider a time interval of $t = 1$ second.

In 1 second, the electron completes $n$ revolutions (frequency).

Therefore, the charge passing through any point $P$ on the orbit in 1 second is $q = ne$.

Hence, the current is:

$$i = \frac{ne}{1} = ne \text{ ampere}$$

**Answer:** The current is $i = ne$ A.

---

### Example 17

**Problem:** Calculate the current in nanoamperes if a million electrons travel through a conductor in 1 microsecond (μs).

**Solution:**

**Given:**
* Number of electrons, $n = 1$ million $= 10^6$ electrons
* Time, $t = 1 \mu\text{s} = 10^{-6}$ s
* Charge of 1 electron, $e = 1.6 \times 10^{-19}$ C

**Using the formula:** $i = \frac{q}{t} = \frac{ne}{t}$

Substituting the values:

$$i = \frac{10^6 \times 1.6 \times 10^{-19}}{10^{-6}} = 1.6 \times 10^{-7} \text{ C/s} = 1.6 \times 10^{-7} \text{ A}$$

**Conversion to nanoamperes:**
* $10^{-9}$ A = 1 nA
* Therefore, 1 A = $10^9$ nA

$$i = 1.6 \times 10^{-7} \times 10^9 \text{ nA} = 1.6 \times 10^2 \text{ nA} = 160 \text{ nA}$$

**Answer:** The current is 160 nA.

