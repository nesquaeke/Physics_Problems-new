## 3) Path Intersection

Alice moves along:

`A(t) = (2 + t, 8 - 3t)`

Bob moves along:

`B(t) = (2t - 1, 2t + 2)`

We want to know:
- do they meet at the same place?
- do they meet at the same time?

---

### Step 1: Compare x-coordinates

Set x-coordinates equal:

`2 + t = 2t - 1`

Solve:

`3 = t`

So:

`t = 3`

### Step 2: Compare y-coordinates

Set y-coordinates equal:

`8 - 3t = 2t + 2`

Solve:

`6 = 5t`

`t = 6/5 = 1.2`

### Step 3: Interpret

The x-coordinates match at `t = 3`, but the y-coordinates match at `t = 1.2`.

So there is no single time when both coordinates are equal.

That means they do **not collide**.

---

### Step 4: Minimum distance between them

Define the relative position:

`D(t) = A(t) - B(t)`

So:

`D(t) = (2 + t - (2t - 1), 8 - 3t - (2t + 2))`

Simplify:

`D(t) = (3 - t, 6 - 5t)`

Distance squared is:

`d^2(t) = (3 - t)^2 + (6 - 5t)^2`

Expand:

`d^2(t) = 9 - 6t + t^2 + 36 - 60t + 25t^2`

`d^2(t) = 26t^2 - 66t + 45`

To minimize distance, minimize `d^2(t)`.

For a quadratic `at^2 + bt + c`, minimum occurs at:

`t = -b / (2a)`

So:

`t = 66 / (2 * 26) = 66 / 52 = 33 / 26 ≈ 1.27 s`

Now compute minimum distance squared:

`d^2(33/26) ≈ 3.115`

So:

`d_min ≈ sqrt(3.115) ≈ 1.77`

**Final answers:**
- They do **not** collide
- Minimum distance occurs at `t ≈ 1.27 s`
- Minimum distance is `1.77 units`

---
