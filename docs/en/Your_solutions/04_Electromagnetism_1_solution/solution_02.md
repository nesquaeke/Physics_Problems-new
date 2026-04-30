Öncelikle `$$` işaretlerinin ne işe yaradığını kısaca açıklayayım: GitHub, normal yazdığımız matematik formüllerini (örneğin kesirleri veya karekökleri) güzel bir şekilde göstermez. `$$` işaretleri GitHub'a "Hey, bu iki işaretin arasındaki şey bir matematik formülü, bunu bir matematik kitabındaki gibi şık ve düzenli çiz" demek için kullandığımız bir koddur. GitHub Preview (Önizleme) moduna geçtiğinde, o `$$` işaretleri kaybolacak ve yerine kusursuz formüller belirecektir. O yüzden kopyalarken onları silme.

Şimdi, sadece **Section 4 (Electromagnetism I)** kısmını, fizikten hiç anlamayan birine anlatır gibi (ELI5 mantığıyla), en temelden alarak ve hiçbir adımı atlamadan tamamen İngilizce hazırlıyorum. Neyi, neden yaptığımızı her adımda açıkladım.


## 2. Electric Potential
**The Problem:** We have a 1.0 meter square again. We put different charges on the corners: +1C, -2C, +3C, and -4C. We need to find the "Electric Potential" at the center. Electric potential is like measuring "electric pressure" or "elevation" at a specific point. It is just a number, it does not have a direction.

**Step-by-step Explanation:**
1.  **Find the distance ($r$) to the center:**
    First, we need the length of the square's diagonal (from one corner to the opposite). Using Pythagorean theorem ($a^2 + b^2 = c^2$) for a square with sides of 1:
    $$ \text{Diagonal} = \sqrt{1^2 + 1^2} = \sqrt{2} \text{ meters} $$
    The center is exactly half of that diagonal:
    $$ r = \frac{\sqrt{2}}{2} \approx 0.707 \text{ meters} $$
2.  **The Formula:** To find total potential ($V$), we calculate the potential from each corner and just add them up. The formula for one charge is $V = k \cdot \frac{q}{r}$.
    $$ V_{\text{total}} = k \frac{q_1}{r} + k \frac{q_2}{r} + k \frac{q_3}{r} + k \frac{q_4}{r} $$
3.  **Make the Math Easy:** Because $k$ and $r$ are the same for all four corners, we can pull them out to make it simpler:
    $$ V_{\text{total}} = \frac{k}{r} (q_1 + q_2 + q_3 + q_4) $$
4.  **Plug in the Numbers:**
    $$ V_{\text{total}} = \frac{9 \times 10^9}{0.707} (+1 - 2 + 3 - 4) $$
    First, add the charges: $1 - 2 + 3 - 4 = -2$
    $$ V_{\text{total}} = \frac{9 \times 10^9}{0.707} \times (-2) \approx -2.54 \times 10^{10} \text{ Volts} $$

**Final Answer:**
$$ V \approx -2.54 \times 10^{10} \text{ V} $$

