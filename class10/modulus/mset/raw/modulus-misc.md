# 🧮 Problem

Let $x=(\tan \theta)^{\tan \theta}$, $y=(\cot \theta)^{\cot \theta}$, $z=(\tan \theta)^{\cot \theta}$, $w=(\cot \theta)^{\tan \theta}$.  
Then which of the following is **TRUE** for $\theta \in \left(\frac{\pi}{4}, \frac{\pi}{2}\right)$?

**Options:**  
A) $w<z<y<x$  
B) $w<y<z<x$  
C) $y<z<w<x$  
D) $y<w<z<x$

---

# ✏️ Solution

### Step 1: Range of $\theta$
For $\theta \in \left(\frac{\pi}{4}, \frac{\pi}{2}\right)$:




$
\tan \theta = \frac{\sin \theta}{\cos \theta}, \quad \cot \theta = \frac{\cos \theta}{\sin \theta}

$

| $\theta$ | $\sin \theta$ | $\cos \theta$ | $\tan \theta = \frac{\sin\theta}{\cos\theta}$ |
|:--|:--:|:--:|:--:|
| $\frac{\pi}{4}$ | $\frac{1}{\sqrt{2}}$ | $\frac{1}{\sqrt{2}}$ | $1$ |
| $\frac{\pi}{2}$ | $1$ | $0$ | $\infty$ |

As $\theta$ increases from $\pi/4$ to $\pi/2$:  
$\sin \theta$ increases, $\cos \theta$ decreases, and therefore $\tan \theta$ increases beyond 1.

Hence,
$
\tan \theta > 1, \quad \cot \theta = \frac{1}{\tan \theta} < 1
$

Let $\tan \theta = t$  
⟹ $t > 1$ and $\cot \theta = \frac{1}{t}$

---

### Step 2: Express all variables in terms of $t$

$
\begin{aligned}
x &= t^t \\
y &= \left(\frac{1}{t}\right)^{1/t} = t^{-1/t} \\
z &= t^{1/t} \\
w &= \left(\frac{1}{t}\right)^t = t^{-t}
\end{aligned}
$

---

### Step 3: Compare magnitudes for $t>1$

$
x = t^t, \quad z = t^{1/t}, \quad y = t^{-1/t}, \quad w = t^{-t}
$

Now note:

- $t^t$ is **very large** (since $t>1$ and raised to a large exponent).  
- $t^{1/t}$ is **greater than 1**, because exponent $\frac{1}{t}$ is positive.  
- $t^{-1/t}$ is **less than 1**, but not extremely small.  
- $t^{-t}$ is **very small**, because exponent $-t$ is large and negative.

Hence, the order of magnitudes is:

$
t^{-t} < t^{-1/t} < t^{1/t} < t^t
$

---

### Step 4: Substitute back to $x, y, z, w$

$
w < y < z < x
$

✅ **Therefore, the correct answer is Option (B)**

$
\boxed{w < y < z < x}
$
