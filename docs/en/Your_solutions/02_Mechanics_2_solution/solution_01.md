# Problem 1 — Gravitational Dependence

For a simple pendulum:

`T = 2*pi*sqrt(L/g)`

This means:
- `T` = period
- `L` = length
- `g` = gravitational acceleration

## 1.1 Period on the Moon

Given:
- period on Earth: `T = 4 s`
- gravity on the Moon is about `1/6` of Earth's gravity

Since pendulum period is proportional to `1/sqrt(g)`, smaller gravity means a larger period.

Use:

`T_moon = T_earth * sqrt(g_earth / g_moon)`

Because:

`g_moon = g_earth / 6`

we get:

`T_moon = 4 * sqrt(6)`

`T_moon ≈ 4 * 2.449`

`T_moon ≈ 9.80 s`

**Final answer:** `9.80 s`

## 1.2 Length for a 1-second pendulum on Earth

Start with:

`T = 2*pi*sqrt(L/g)`

Solve for `L`:

`L = g * (T / (2*pi))^2`

Substitute:
- `T = 1 s`
- `g = 9.81 m/s^2`

`L = 9.81 * (1 / (2*pi))^2`

`L ≈ 0.2485 m`

**Final answer:** `0.249 m`

---