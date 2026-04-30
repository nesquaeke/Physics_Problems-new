

## 6. EM Wave Analysis
**The Problem:** Light is an "Electromagnetic Wave". It is electricity and magnetism waving together. The problem gives us the math code for the electrical part of a light wave:
$$ E_y(x,t) = 100 \sin(10^7 x - \omega t) \text{ V/m} $$

**Step-by-step Explanation:**
The standard map for a wave is: $E = E_{\max} \sin(kx - \omega t)$. By comparing our wave to the map, we can steal the numbers!
*   $E_{\max}$ (Maximum height) = $100$
*   $k$ (Wave number) = $10^7$

**1. Direction:** 
Look inside the parenthesis: $(kx - \omega t)$. Because it is an 'x', it moves on the X-axis. Because the sign in the middle is a minus ($-$), it means it is moving forward in the **positive X-direction**.

**2. Wavelength ($\lambda$):**
Wavelength is related to the '$k$' number. The formula is $\lambda = \frac{2\pi}{k}$.
    
$$ \lambda = \frac{2\pi}{10^7} \approx 6.28 \times 10^{-7} \text{ meters} $$

**3. Angular Frequency ($\omega$):**
This tells us how fast the wave wiggles. The formula is $\omega = c \cdot k$ (speed of light multiplied by $k$).
    
$$ \omega = (3 \times 10^8) \times (10^7) = 3 \times 10^{15} \text{ rad/s} $$

**4. Magnetic Field Equation ($B_z$):**
Light always has a Magnetic ($B$) part that dances perfectly with the Electric ($E$) part, but perpendicular to it.
*   Find the $B_{\max}$ height: $B_{\max} = \frac{E_{\max}}{c} = \frac{100}{3 \times 10^8} = 3.33 \times 10^{-7} \text{ T}$.
*   Since the wave travels on the X-axis, and the Electric part wiggles on the Y-axis ($E_y$), the Magnetic part MUST wiggle on the Z-axis ($B_z$). Everything else in the bracket stays exactly the same!
    
$$ B_z(x,t) = 3.33 \times 10^{-7} \sin(10^7 x - 3 \times 10^{15} t) \text{ T} $$

