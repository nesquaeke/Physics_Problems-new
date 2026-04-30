

## 2. Ampere's Law
**The Problem:** We have two long, straight wires sitting side-by-side on a table, 10 cm apart. They both carry 5 Amps of electricity, but the electricity flows in *opposite* directions (one goes up, one goes down). We want to find the magnetic field exactly in the middle of them.

**Step-by-step Explanation:**
1.  **The Concept:** When electricity flows through a wire, it creates invisible "magnetic circles" spinning around the wire. (This is called the Right-Hand Rule).
2.  **The Direction Trick:** 
    *   Imagine grabbing the left wire with your right hand. Your thumb points UP (current). Your fingers wrap around to the right. So, in the space *between* the wires, the left wire's magnetic wind blows "INTO" the table.
    *   Now grab the right wire. Your thumb points DOWN. Your fingers wrap around to the left. In the space *between* the wires, the right wire's magnetic wind ALSO blows "INTO" the table.
    *   Because both winds blow in the exact same direction in the middle, they help each other. We must **add** them together.
3.  **The Distances:** The total distance is 10 cm ($0.1 \text{ m}$). The middle point is exactly 5 cm ($0.05 \text{ m}$) away from each wire. So, $r = 0.05 \text{ m}$.
4.  **The Formula for one wire:**
    
    $$ B = \frac{\mu_0 \cdot I}{2\pi \cdot r} $$

5.  **Calculate and Add:**
    Since both wires have the same current and are at the same distance from the middle, they create the exact same magnetic field.
    
    $$ B_{\text{total}} = B_1 + B_2 = \frac{\mu_0 \cdot I}{2\pi \cdot r} + \frac{\mu_0 \cdot I}{2\pi \cdot r} = \frac{\mu_0 \cdot I}{\pi \cdot r} $$
    
    Now, plug in the numbers ($\mu_0 = 4\pi \times 10^{-7}$, $I = 5$, $r = 0.05$):
    
    $$ B_{\text{total}} = \frac{(4\pi \times 10^{-7}) \times 5}{\pi \times 0.05} $$
    
    Cancel out the $\pi$ on top and bottom:
    
    $$ B_{\text{total}} = \frac{4 \times 10^{-7} \times 5}{0.05} = \frac{20 \times 10^{-7}}{0.05} = 4 \times 10^{-5} \text{ T} $$

**Final Answer:** The magnetic field is $4 \times 10^{-5} \text{ T}$ and it points perpendicular to the plane of the wires (either directly towards you or directly away from you, depending on how you look at the wires).

---

