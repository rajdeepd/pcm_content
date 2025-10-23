---
layout: default
title: Kinematics & Optics — One Page Quick Sheet
mathjax: true
---

# 🧮 KINEMATICS & 🔭 OPTICS — One Page Quick Sheet

## Scalars vs Vectors
- **Scalar:** magnitude only (length, mass, time, speed).  
- **Vector:** magnitude **and** direction (displacement, velocity, acceleration, force).

---

## Distance vs Displacement
- **Distance:** total path length (scalar).  
- **Displacement:** shortest straight line from initial to final point (vector, direction from start → end).

---

## Speed, Velocity, Acceleration
- **Speed:** $v=\dfrac{s}{t}$ (scalar).  
- **Velocity:** $\vec v=\dfrac{\vec s}{t}$ (vector).  
- **Acceleration:** $\vec a=\dfrac{d\vec v}{dt}$ (vector).  
  - $a>0$ increasing speed; $a<0$ **retardation**.  
- **Units:** $\text{m s}^{-1}$, $\text{m s}^{-2}$ (MKS); $\text{cm s}^{-1}$, $\text{cm s}^{-2}$ (CGS).

---

## Equations of Motion (1D, constant $a$)
Let $u$=initial velocity, $v$=final velocity, $a$=acceleration, $t$=time, $s$=displacement.
1. **First:** $v=u+at$  
2. **Second:** $s=ut+\tfrac12 at^2$  
3. **Third (time-free):** $v^2=u^2+2as$  
- Displacement in the $t^{\text{th}}$ second: $s_t=u+\dfrac{a}{2}(2t-1)$

### Under Gravity (take upward $+$ if stated)
Replace $a$ by $\pm g$:
- $v=u\pm gt,\quad h=ut\pm \tfrac12 gt^2,\quad v^2=u^2\pm 2gh$

---

## Graph Tips
- **$v$–$t$ graph:** slope $\to a$; area under curve $\to s$.  
- **$a$–$t$ graph:** area $\to \Delta v$.

---

## OPTICS (Geometrical/Ray Optics)

### Rays, Beams, Objects & Images
- **Beam:** set of rays — **convergent**, **divergent**, or **parallel**.  
- **Object:** intersection of incident rays (or their extension).  
- **Image:** intersection of reflected/refracted rays (real) or their extensions (virtual).

### Reflection (Plane Mirrors)
- Laws: (i) $\angle i=\angle r$, (ii) incident ray, normal, reflected ray are coplanar.  
- **Image in plane mirror:** virtual, upright, laterally inverted, **object distance = image distance**.  
- **Mirror rotation:** mirror by $\theta$ $\Rightarrow$ reflected ray turns by $2\theta$.  
- **Two mirrors at $\theta$:** number of images $n=\begin{cases}m-1, & m=\frac{360^\circ}{\theta}\in\mathbb{Z}\\ \lfloor m\rfloor, & \text{general}\end{cases}$ (common exam rule of thumb).

### Paraxial Approximation
- Small apertures, rays close to principal axis $\Rightarrow$ small-angle formulas hold.

### Refraction (Snell’s Law)
- Rays bend **towards** normal going to **denser** medium; **away** when going to rarer.  
- **Snell:** $\dfrac{\sin i}{\sin r}={}_1\mu_2=\dfrac{\mu_2}{\mu_1}=\dfrac{c_1}{c_2}$  
- **Absolute index:** $\mu=\dfrac{c_{\text{vac}}}{c_{\text{medium}}}$

#### Useful Consequence
- With multiple media along a path: $\mu_1\sin i_1=\mu_2\sin i_2=\cdots=\text{constant}$

### Apparent Depth (near-normal view)
- $\displaystyle \frac{\text{Apparent depth}}{\text{Real depth}}=\frac{\mu_1}{\mu_2}$ (object in medium 2, observer in 1)  
- **Shift:** $\text{Real}-\text{Apparent}=\text{Real}\left(1-\dfrac{\mu_1}{\mu_2}\right)$  
  - Into denser medium ($\mu_2>\mu_1$) → object appears **shallower**.

---

## Lenses & Power
- **Power:** $P=\dfrac{1}{f(\text{m})}$ (dioptres).  
- Lenses in contact: $\displaystyle P_{\text{eq}}=P_1+P_2+\cdots$, so $\dfrac{1}{F}=\dfrac{1}{f_1}+\dfrac{1}{f_2}+\cdots$

---

## Quick Worked Examples (mini)
- **Car from rest with $a=1\,\text{m s}^{-2}$ for $3$ min:** $v=at=180\,\text{m s}^{-1}$.  
- **Braking to rest:** $u=20\,\text{m s}^{-1}$, $a=-10\,\text{m s}^{-2}$ → $s=\dfrac{u^2}{2|a|}=20\,\text{m}$.  
- **Vertical throw $u=39.2\,\text{m s}^{-1}$:** $t_\text{up}=u/g=4\,\text{s}$, $h_{\max}=u^2/(2g)=78.4\,\text{m}$.  
- **Lens combo:** $+6\,\text{D}$ with $-2\,\text{D}$ → $P=+4\,\text{D}$, $f=0.25\,\text{m}$.

---

## Units & Constants
- $g\approx 9.8\,\text{m s}^{-2}$, speed: $\text{m s}^{-1}$, acceleration: $\text{m s}^{-2}$, power of lens: dioptre (D).

---

### Exam Pointers
- Choose sign convention **once** and stick to it.  
- For uniform $a$, **pick the equation** that avoids the missing variable.  
- In layered media, use $\mu\sin i=\text{constant}$ along the ray.  
- For plane mirrors, **image distance = object distance** (behind mirror).
