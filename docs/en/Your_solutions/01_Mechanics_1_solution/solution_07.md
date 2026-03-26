## 7) Elimination of Time and Interpretation of Acceleration

Given:

`x(t) = 2t^2`
`y(t) = 3t^3`

We want:
- eliminate `t`
- draw the trajectory
- find velocity and acceleration
- decide if acceleration is constant

---

### 7.1) Eliminate the parameter

From:

`x = 2t^2`

we get:

`t^2 = x/2`

So:

`t = sqrt(x/2)` for `t >= 0`

Now use:

`y = 3t^3 = 3t*t^2`

Substitute `t^2 = x/2` and `t = sqrt(x/2)`:

`y = 3 * sqrt(x/2) * (x/2)`

This can be written as:

`y = (3 / (2*sqrt(2))) * x^(3/2)`

**Final answer:**  
`y = (3 / (2*sqrt(2))) * x^(3/2)`

---

### 7.2) Shape of the trajectory

This is a curved path starting from the origin.

Since `y` grows like `x^(3/2)`, the curve rises faster than a straight line but slower than a quadratic for small `x`.

---

### 7.3) Velocity vector

Differentiate position components:

`vx = dx/dt = 4t`
`vy = dy/dt = 9t^2`

So:

`v(t) = (4t, 9t^2)`

**Final answer:**  
`v(t) = (4t, 9t^2)`

---

### 7.4) Speed

Speed is magnitude of velocity:

`|v(t)| = sqrt((4t)^2 + (9t^2)^2)`

`|v(t)| = sqrt(16t^2 + 81t^4)`

`|v(t)| = t * sqrt(16 + 81t^2)` for `t >= 0`

**Final answer:**  
`|v(t)| = sqrt(16t^2 + 81t^4)`

---

### 7.5) Acceleration vector

Differentiate velocity:

`ax = d/dt(4t) = 4`
`ay = d/dt(9t^2) = 18t`

So:

`a(t) = (4, 18t)`

**Final answer:**  
`a(t) = (4, 18t)`

---

### 7.6) Magnitude of acceleration

`|a(t)| = sqrt(4^2 + (18t)^2)`

`|a(t)| = sqrt(16 + 324t^2)`

**Final answer:**  
`|a(t)| = sqrt(16 + 324t^2)`

---

### 7.7) Is acceleration constant?

No.

The x-component is constant (`4`), but the y-component is `18t`, which changes with time.

So the acceleration vector is **not constant**.

**Final answer:**  
Acceleration is **not constant**.

---