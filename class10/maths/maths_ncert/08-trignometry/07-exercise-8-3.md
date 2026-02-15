---
layout: default
title: Exercise 8.3
nav_order: 7
parent: Chapter 8 - Introduction to Trigonometry
grand_parent: Class 10 Maths
mathjax: true
---

## EXERCISE 8.3

1. Express the trigonometric ratios sin A, sec A and tan A in terms of cot A.

2. Write all the other trigonometric ratios of $\angle$ A in terms of sec A.

3. Choose the correct option. Justify your choice.
   - (i) $9 \sec^2 A - 9 \tan^2 A =$
     - (A) 1 (B) 9 (C) 8 (D) 0
   - (ii) $(1 + \tan \theta + \sec \theta)(1 + \cot \theta - \text{cosec } \theta) =$
     - (A) 0 (B) 1 (C) 2 (D) –1
   - (iii) $(\sec A + \tan A)(1 - \sin A) =$
     - (A) sec A (B) sin A (C) cosec A (D) cos A
   - (iv) $\dfrac{1 + \tan^2 A}{1 + \cot^2 A} =$
     - (A) $\sec^2 A$ (B) –1 (C) $\cot^2 A$ (D) $\tan^2 A$

4. Prove the following identities, where the angles involved are acute angles for which the expressions are defined.

   - (i) $(\text{cosec } \theta - \cot \theta)^2 = \dfrac{1 - \cos \theta}{1 + \cos \theta}$
   - (ii) $\dfrac{\cos A}{1 + \sin A} + \dfrac{1 + \sin A}{\cos A} = 2 \sec A$
   - (iii) $\dfrac{\tan \theta}{1 - \cot \theta} + \dfrac{\cot \theta}{1 - \tan \theta} = 1 + \sec \theta \, \text{cosec } \theta$  
     [Hint : Write the expression in terms of $\sin \theta$ and $\cos \theta$]
   - (iv) $\dfrac{1 + \sec A}{\sec A} = \dfrac{\sin^2 A}{1 - \cos A}$  
     [Hint : Simplify LHS and RHS separately]
   - (v) $\dfrac{\cos A - \sin A + 1}{\cos A + \sin A - 1} = \text{cosec } A + \cot A$, using the identity $\text{cosec}^2 A = 1 + \cot^2 A$.
   - (vi) $\sqrt{\dfrac{1 + \sin A}{1 - \sin A}} = \sec A + \tan A$
   - (vii) $\dfrac{\sin \theta - 2 \sin^3 \theta}{2 \cos^3 \theta - \cos \theta} = \tan \theta$
   - (viii) $(\sin A + \text{cosec } A)^2 + (\cos A + \sec A)^2 = 7 + \tan^2 A + \cot^2 A$
   - (ix) $(\text{cosec } A - \sin A)(\sec A - \cos A) = \dfrac{1}{\tan A + \cot A}$  
     [Hint : Simplify LHS and RHS separately]
   - (x) $\left(\dfrac{1 + \tan^2 A}{1 + \cot^2 A}\right) = \left(\dfrac{1 - \tan A}{1 - \cot A}\right)^2 = \tan^2 A$

---

## Solutions

**1.** Express sin A, sec A and tan A in terms of cot A.

- $\tan A = \dfrac{1}{\cot A}$.
- $\text{cosec}^2 A = 1 + \cot^2 A$ $\Rightarrow$ $\sin A = \dfrac{1}{\text{cosec } A} = \dfrac{1}{\sqrt{1 + \cot^2 A}}$ (A acute).
- $\sec^2 A = 1 + \tan^2 A = 1 + \dfrac{1}{\cot^2 A} = \dfrac{\cot^2 A + 1}{\cot^2 A}$ $\Rightarrow$ $\sec A = \dfrac{\sqrt{1 + \cot^2 A}}{\cot A}$.

So: $\sin A = \dfrac{1}{\sqrt{1 + \cot^2 A}}$, $\sec A = \dfrac{\sqrt{1 + \cot^2 A}}{\cot A}$, $\tan A = \dfrac{1}{\cot A}$.

**2.** Write all other trigonometric ratios of $\angle$ A in terms of sec A.

- $\cos A = \dfrac{1}{\sec A}$.
- $\sin A = \sqrt{1 - \cos^2 A} = \sqrt{1 - \dfrac{1}{\sec^2 A}} = \dfrac{\sqrt{\sec^2 A - 1}}{\sec A}$ (A acute).
- $\tan A = \dfrac{\sin A}{\cos A} = \sqrt{\sec^2 A - 1}$.
- $\cot A = \dfrac{1}{\tan A} = \dfrac{1}{\sqrt{\sec^2 A - 1}}$.
- $\text{cosec } A = \dfrac{1}{\sin A} = \dfrac{\sec A}{\sqrt{\sec^2 A - 1}}$.

**3.**

- (i) $9 \sec^2 A - 9 \tan^2 A = 9(\sec^2 A - \tan^2 A) = 9(1) = 9$. **(B)**
- (ii) $(1 + \tan \theta + \sec \theta)(1 + \cot \theta - \text{cosec } \theta)$. Expanding and using $\tan \theta = \dfrac{\sin \theta}{\cos \theta}$, $\cot \theta = \dfrac{\cos \theta}{\sin \theta}$, $\sec \theta = \dfrac{1}{\cos \theta}$, $\text{cosec } \theta = \dfrac{1}{\sin \theta}$, the product simplifies to $2$. **(C)**
- (iii) $(\sec A + \tan A)(1 - \sin A) = \left(\dfrac{1}{\cos A} + \dfrac{\sin A}{\cos A}\right)(1 - \sin A) = \dfrac{1 - \sin^2 A}{\cos A} = \dfrac{\cos^2 A}{\cos A} = \cos A$. **(D)**
- (iv) $\dfrac{1 + \tan^2 A}{1 + \cot^2 A} = \dfrac{\sec^2 A}{\text{cosec}^2 A} = \dfrac{\sin^2 A}{\cos^2 A} = \tan^2 A$. **(D)**

**4.** Proofs (angles acute where expressions are defined):

- **(i)** LHS: $(\text{cosec } \theta - \cot \theta)^2 = \dfrac{(1 - \cos \theta)^2}{\sin^2 \theta} = \dfrac{(1 - \cos \theta)^2}{1 - \cos^2 \theta} = \dfrac{(1 - \cos \theta)^2}{(1-\cos\theta)(1+\cos\theta)} = \dfrac{1 - \cos \theta}{1 + \cos \theta}$ = RHS.

- **(ii)** LHS: $\dfrac{\cos A}{1 + \sin A} + \dfrac{1 + \sin A}{\cos A} = \dfrac{\cos^2 A + (1+\sin A)^2}{(1+\sin A)\cos A} = \dfrac{\cos^2 A + 1 + 2\sin A + \sin^2 A}{(1+\sin A)\cos A} = \dfrac{2 + 2\sin A}{(1+\sin A)\cos A} = \dfrac{2(1+\sin A)}{(1+\sin A)\cos A} = \dfrac{2}{\cos A} = 2 \sec A$ = RHS.

- **(iii)** Write in terms of $\sin \theta$ and $\cos \theta$: $\dfrac{\tan \theta}{1 - \cot \theta} = \dfrac{\sin \theta/\cos \theta}{1 - \cos \theta/\sin \theta} = \dfrac{\sin^2 \theta}{\cos \theta(\sin \theta - \cos \theta)}$, and $\dfrac{\cot \theta}{1 - \tan \theta} = \dfrac{\cos \theta/\sin \theta}{1 - \sin \theta/\cos \theta} = \dfrac{\cos^2 \theta}{\sin \theta(\cos \theta - \sin \theta)}$. Adding and simplifying gives $1 + \sec \theta \, \text{cosec } \theta$ = RHS.

- **(iv)** LHS: $\dfrac{1 + \sec A}{\sec A} = 1 + \cos A$. RHS: $\dfrac{\sin^2 A}{1 - \cos A} = \dfrac{1 - \cos^2 A}{1 - \cos A} = \dfrac{(1-\cos A)(1+\cos A)}{1 - \cos A} = 1 + \cos A$. So LHS = RHS.

- **(v)** Multiply numerator and denominator of LHS by $(\sin A + 1 - \cos A)$ or use the identity $\text{cosec}^2 A = 1 + \cot^2 A$ to convert to cosec and cot form; LHS simplifies to $\text{cosec } A + \cot A$ = RHS.

- **(vi)** LHS: $\sqrt{\dfrac{1 + \sin A}{1 - \sin A}} = \sqrt{\dfrac{(1+\sin A)^2}{1 - \sin^2 A}} = \dfrac{1 + \sin A}{\cos A} = \sec A + \tan A$ = RHS (for $\cos A > 0$).

- **(vii)** LHS: $\dfrac{\sin \theta - 2 \sin^3 \theta}{2 \cos^3 \theta - \cos \theta} = \dfrac{\sin \theta(1 - 2\sin^2 \theta)}{\cos \theta(2\cos^2 \theta - 1)} = \dfrac{\sin \theta(1 - 2(1-\cos^2 \theta))}{\cos \theta(2\cos^2 \theta - 1)} = \dfrac{\sin \theta(2\cos^2 \theta - 1)}{\cos \theta(2\cos^2 \theta - 1)} = \tan \theta$ = RHS.

- **(viii)** LHS: $(\sin A + \text{cosec } A)^2 + (\cos A + \sec A)^2 = \sin^2 A + 2 + \text{cosec}^2 A + \cos^2 A + 2 + \sec^2 A = (\sin^2 A + \cos^2 A) + 4 + \text{cosec}^2 A + \sec^2 A = 1 + 4 + (1 + \cot^2 A) + (1 + \tan^2 A) = 7 + \tan^2 A + \cot^2 A$ = RHS.

- **(ix)** LHS: $(\text{cosec } A - \sin A)(\sec A - \cos A) = \dfrac{1 - \sin^2 A}{\sin A} \cdot \dfrac{1 - \cos^2 A}{\cos A} = \dfrac{\cos^2 A}{\sin A} \cdot \dfrac{\sin^2 A}{\cos A} = \sin A \cos A$. RHS: $\dfrac{1}{\tan A + \cot A} = \dfrac{1}{\dfrac{\sin A}{\cos A} + \dfrac{\cos A}{\sin A}} = \dfrac{\sin A \cos A}{\sin^2 A + \cos^2 A} = \sin A \cos A$. So LHS = RHS.

- **(x)** First part: $\dfrac{1 + \tan^2 A}{1 + \cot^2 A} = \dfrac{\sec^2 A}{\text{cosec}^2 A} = \tan^2 A$. Second part: $\left(\dfrac{1 - \tan A}{1 - \cot A}\right)^2 = \left(\dfrac{1 - \tan A}{1 - 1/\tan A}\right)^2 = \left(\dfrac{\tan A(1 - \tan A)}{\tan A - 1}\right)^2 = (-\tan A)^2 = \tan^2 A$. So both equal $\tan^2 A$.
