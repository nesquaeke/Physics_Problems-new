## 10) Kinematics

Given:

`r(t) = (a cos(wt), b sin(wt), bt)`

where:
- `a > 0`
- `b > 0`
- `w > 0`

We want:
- trajectory equation
- path length from `t = 0` to `t = t0`
- discuss special cases

---

### 10.1) Trajectory equation

Coordinates are:

`x = a cos(wt)`
`y = b sin(wt)`
`z = bt`

To eliminate time using `x` and `y`, divide by constants:

`x/a = cos(wt)`
`y/b = sin(wt)`

Square and add:

`(x^2)/(a^2) + (y^2)/(b^2) = 1`

So in the `xy` plane, the motion follows an ellipse.

Since also:

`z = bt`

the point rises linearly upward while moving around the ellipse.

So the full 3D path is an **elliptical helix**.

**Final answer:**  
`(x^2)/(a^2) + (y^2)/(b^2) = 1`, with `z = bt`

---

### 10.2) Path length from `0` to `t0`

Speed is the magnitude of velocity.

First differentiate:

`dx/dt = -aw sin(wt)`
`dy/dt = bw cos(wt)`
`dz/dt = b`

So:

`v(t) = (-aw sin(wt), bw cos(wt), b)`

Now speed is:

`|v(t)| = sqrt((aw)^2 sin^2(wt) + (bw)^2 cos^2(wt) + b^2)`

So path length is:

`s = integral from 0 to t0 of |v(t)| dt`

That is:

`s = integral from 0 to t0 of sqrt(a^2 w^2 sin^2(wt) + b^2 w^2 cos^2(wt) + b^2) dt`

This is the exact formula.

In general, this integral does not simplify nicely unless special values are chosen.

**Final answer:**  
`s = integral from 0 to t0 of sqrt(a^2 w^2 sin^2(wt) + b^2 w^2 cos^2(wt) + b^2) dt`

---

### 10.3) Interpretation of the motion

The point moves:
- around an ellipse in the `xy` plane
- upward at constant speed in the `z` direction

So the total motion is a spiral-like curve wrapped around an elliptical cylinder.

---

### 10.4) Special cases

#### Case 1: `a = b`

Then the ellipse becomes a circle:

`x^2 + y^2 = a^2`

So the path becomes a **circular helix**.

#### Case 2: `b = 0`

Then:

- `y = 0`
- `z = 0`

and motion stays in the x-direction only in an oscillatory way.

#### Case 3: `w = 0`

Then:

- `x = a`
- `y = 0`
- `z = bt`

So the point moves straight upward.

---

### 10.5) Python code to draw the trajectory

```python
import numpy as np
import matplotlib.pyplot as plt

a = 3
b = 2
w = 1
t0 = 10

t = np.linspace(0, t0, 1000)

x = a * np.cos(w * t)
y = b * np.sin(w * t)
z = b * t

fig = plt.figure()
ax = fig.add_subplot(111, projection='3d')

ax.plot(x, y, z)
ax.set_xlabel("x")
ax.set_ylabel("y")
ax.set_zlabel("z")
ax.set_title("Trajectory of the Point")

plt.show()