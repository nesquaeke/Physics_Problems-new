## 6) Variable Velocity

Given:

`v(t) = t^2 + 2t - 5`

Also:

`x(0) = 4`

We want:
- position at `t = 3`
- acceleration at `t = 3`

---

### Step 1: Find acceleration

Acceleration is derivative of velocity:

`a(t) = dv/dt = 2t + 2`

At `t = 3`:

`a(3) = 2*3 + 2 = 8`

**Acceleration at `t = 3`:** `8 m/s^2`

---

### Step 2: Find position function

Velocity is derivative of position:

`dx/dt = t^2 + 2t - 5`

Integrate:

`x(t) = (1/3)t^3 + t^2 - 5t + C`

Use initial condition `x(0) = 4`:

`C = 4`

So:

`x(t) = (1/3)t^3 + t^2 - 5t + 4`

Now substitute `t = 3`:

`x(3) = (1/3)*27 + 9 - 15 + 4`

`x(3) = 9 + 9 - 15 + 4 = 7`

**Final answers:**
- Position at `t = 3`: `7 m`
- Acceleration at `t = 3`: `8 m/s^2`

---