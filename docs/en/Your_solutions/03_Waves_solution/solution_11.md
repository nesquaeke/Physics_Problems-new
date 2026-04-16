## ✅ 11. Two-Slit Interference (Mathematical Solution)

### 📌 Physical Idea
Two slits act as two wave sources. Each slit produces a wave that spreads in space.
The final wave is the **sum of both waves** (superposition).

---

### 📌 1. Wave from each slit
Each slit produces a spherical wave:
$$u_1(r,t) = \frac{A}{r_1}\sin(k r_1 - \omega t)$$
$$u_2(r,t) = \frac{A}{r_2}\sin(k r_2 - \omega t)$$

**Where:**
* $r_1$ = distance from slit 1
* $r_2$ = distance from slit 2
* $k = \frac{2\pi}{\lambda}$

---

### 📌 2. Total wave (Superposition)
The total wave is:
$$u(r,t) = u_1 + u_2$$

**So:**
$$u(r,t) = \frac{A}{r_1}\sin(k r_1 - \omega t) + \frac{A}{r_2}\sin(k r_2 - \omega t)$$

---

### 📌 3. Interference idea
The pattern comes from the **phase difference**:
$$\Delta r = r_2 - r_1$$

🟢 **Constructive Interference (Bright area)**
When waves are in phase:
$$\Delta r = n\lambda$$
👉 Waves add together → bright line appears

🔴 **Destructive Interference (Dark area)**
When waves are out of phase:
$$\Delta r = \left(n + \frac{1}{2}\right)\lambda$$
👉 Waves cancel → dark line appears

---

### 📌 4. What the simulation does
For each pixel:
1. Compute distances $r_1$ and $r_2$
2. Compute wave1 and wave2
3. Add them: $$u = u_1 + u_2$$
4. Convert result into brightness (color)

---

### 📌 5. Effect of parameters
* If **$d$ increases** → more interference stripes
* If **$\lambda$ increases** → wider spacing between stripes
* If **$\lambda$ decreases** → tighter pattern

---

### 📌 6. Summary
* Two slits → two waves
* Waves combine using superposition
* Phase difference creates interference
* Bright and dark patterns appear on screen

---

### 🎯 Final idea
The interference pattern is created by adding two wave functions and observing how their phase difference changes the intensity.

### 📌 Concept (simple explanation)
Thomas Young’s double-slit experiment shows that light behaves like a wave.
* **Peaks + peaks** → bright band (constructive interference)
* **Peak + valley** → dark band (destructive interference)