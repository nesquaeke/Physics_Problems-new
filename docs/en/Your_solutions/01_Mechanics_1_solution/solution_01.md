## 1) Projectile Motion

A projectile is launched from the ground with:

- initial speed: `v0 = 100 m/s`
- launch angle: `37 degrees`
- no air resistance

We use:
- horizontal axis: `x`
- vertical axis: `y`
- gravity: `g = 9.81 m/s^2`

---

### 1.1) Differential equations of motion

There is no horizontal force, so horizontal acceleration is zero:

`d^2x/dt^2 = 0`

In the vertical direction, only gravity acts downward:

`d^2y/dt^2 = -g`

These are the differential equations of motion.

**Answer:**
- Horizontal: `d^2x/dt^2 = 0`
- Vertical: `d^2y/dt^2 = -g`

---

### 1.2) Horizontal and vertical components of initial velocity

We split the initial velocity into components:

`vx0 = v0 cos(theta)`
`vy0 = v0 sin(theta)`

Using:
- `v0 = 100`
- `theta = 37 degrees`
- `cos(37 deg) ≈ 0.7986`
- `sin(37 deg) ≈ 0.6018`

So:

`vx0 = 100 * 0.7986 = 79.86 m/s`
`vy0 = 100 * 0.6018 = 60.18 m/s`

---

### 1.3) Equations of motion

Since horizontal acceleration is zero:

`x(t) = vx0 * t`

So:

`x(t) = 79.86 t`

In the vertical direction:

`y(t) = vy0 * t - (1/2)gt^2`

So:

`y(t) = 60.18 t - 4.905 t^2`

---

### 1.4) Time of flight

The projectile lands when `y = 0`.

So solve:

`0 = 60.18 t - 4.905 t^2`

Factor:

`t(60.18 - 4.905 t) = 0`

So:
- `t = 0` at launch
- `t = 60.18 / 4.905`

`T ≈ 12.27 s`

**Final answer:** `12.27 s`

---

### 1.5) Maximum height

At the highest point, vertical velocity becomes zero.

Use:

`vy = vy0 - gt`

Set `vy = 0`:

`0 = 60.18 - 9.81 t`

` t = 60.18 / 9.81 ≈ 6.13 s`

Now substitute into height formula:

`H = vy0^2 / (2g)`

`H = (60.18)^2 / (2 * 9.81)`

`H ≈ 184.6 m`

**Final answer:** `184.6 m`

---

### 1.6) Range

Range is horizontal speed times total flight time:

`R = vx0 * T`

`R = 79.86 * 12.27`

`R ≈ 979.8 m`

**Final answer:** `979.8 m`

---