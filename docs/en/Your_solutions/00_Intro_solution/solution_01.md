# Section 0 — Mathematical Foundations

## Problem 1: Vector Algebra (Step-by-step)

We are given two vectors in $\mathbb{R}^3$:

$$
\vec{a} = [2,,1,,-3],
\qquad
\vec{b} = [4,,-2,,1].
$$

---

# Necessary definitions and formulas

## 1) Magnitude (length) of a vector

For a vector

$$
\vec{v} = [v_x, v_y, v_z]
$$

the magnitude is

$$
|\vec{v}| = \sqrt{v_x^2 + v_y^2 + v_z^2}.
$$

This represents the **length of the vector in 3D space**.

---

## 2) Dot product

For two vectors

$$
\vec{a} = [a_x,a_y,a_z], \qquad \vec{b}=[b_x,b_y,b_z]
$$

the dot product is

$$
\vec{a}\cdot\vec{b} = a_x b_x + a_y b_y + a_z b_z.
$$

Geometrically,

$$
\vec{a}\cdot\vec{b} = |\vec{a}|,|\vec{b}| \cos\theta
$$

where $\theta$ is the **angle between the vectors**.

---

## 3) Cross product

The cross product produces a **vector perpendicular to both vectors**:

$$
\vec{a}\times\vec{b} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k}\
a_x & a_y & a_z\
b_x & b_y & b_z
\end{vmatrix}
$$

Expanding the determinant gives

$$
\vec{a}\times\vec{b} =
(a_y b_z - a_z b_y)\hat{i}
-(a_x b_z - a_z b_x)\hat{j}
+(a_x b_y - a_y b_x)\hat{k}.
$$

---

## 4) Angle between vectors

Using the dot product relation

$$
\vec{a}\cdot\vec{b} = |\vec{a}|,|\vec{b}| \cos\theta
$$

we obtain

$$
\cos\theta =
\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|,|\vec{b}|}.
$$

Then

$$
\theta =
\arccos
\left(
\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|,|\vec{b}|}
\right).
$$

---

# Solution

## a) Magnitude of each vector

### Magnitude of $\vec{a}$

$$
|\vec{a}| =
\sqrt{2^2 + 1^2 + (-3)^2}
$$

# $$

\sqrt{4 + 1 + 9}
$$

# $$

\sqrt{14}
$$

---

### Magnitude of $\vec{b}$

$$
|\vec{b}| =
\sqrt{4^2 + (-2)^2 + 1^2}
$$

# $$

\sqrt{16 + 4 + 1}
$$

# $$

\sqrt{21}
$$

Therefore

$$
|\vec{a}| = \sqrt{14}, \qquad |\vec{b}| = \sqrt{21}.
$$

---

# b) Dot product

Using

$$
\vec{a}\cdot\vec{b} =
a_x b_x + a_y b_y + a_z b_z
$$

we compute

$$
\vec{a}\cdot\vec{b}
===================

(2)(4) + (1)(-2) + (-3)(1)
$$

# $$

8 - 2 - 3
$$

$$
= 3
$$

So

$$
\vec{a}\cdot\vec{b} = 3.
$$

---

# c) Cross product

Using

$$
\vec{a}\times\vec{b} =
(a_y b_z - a_z b_y)\hat{i}
-(a_x b_z - a_z b_x)\hat{j}
+(a_x b_y - a_y b_x)\hat{k}
$$

### i-component

$$
a_y b_z - a_z b_y
=================

(1)(1) - (-3)(-2)
$$

$$
= 1 - 6
= -5
$$

---

### j-component

$$
-(a_x b_z - a_z b_x)
$$

$$
= -(2\cdot1 - (-3)\cdot4)
$$

$$
= -(2 + 12)
= -14
$$

---

### k-component

$$
a_x b_y - a_y b_x
$$

$$
= (2)(-2) - (1)(4)
$$

$$
= -4 - 4
= -8
$$

---

### Final cross product

$$
\vec{a}\times\vec{b}
====================

[-5,-14,-8].
$$

---

# d) Angle between vectors

Using

$$
\cos\theta =
\frac{\vec{a}\cdot\vec{b}}{|\vec{a}|,|\vec{b}|}
$$

Substitute the values:

$$
\cos\theta =
\frac{3}{\sqrt{14}\sqrt{21}}
$$

Combine the square roots:

$$
\cos\theta =
\frac{3}{\sqrt{294}}
$$

Numerically

$$
\cos\theta \approx 0.175
$$

Therefore

$$
\theta =
\arccos(0.175)
$$

$$
\theta \approx 79.9^\circ
$$

---

# Final Answers

### Magnitudes

$$
|\vec{a}|=\sqrt{14}, \qquad |\vec{b}|=\sqrt{21}
$$

### Dot product

$$
\vec{a}\cdot\vec{b}=3
$$

### Cross product

$$
\vec{a}\times\vec{b}=[-5,-14,-8]
$$

### Angle between vectors

$$
\theta \approx 79.9^\circ
$$

