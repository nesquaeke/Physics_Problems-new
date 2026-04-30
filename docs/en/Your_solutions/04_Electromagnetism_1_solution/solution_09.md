

## 9. Vector Lorentz Force
**The Problem:** A proton is flying in 3D space. Its speed has an x, y, and z direction: $\vec{v} = (2\hat{i} - 4\hat{j} + \hat{k})$. It enters a magnetic field that also has 3D directions: $\vec{B} = (\hat{i} + 2\hat{j} - \hat{k})$. We need to find the total force.
*(Note: $\hat{i}$ means X-axis, $\hat{j}$ means Y-axis, $\hat{k}$ means Z-axis).*

**Step-by-step Explanation:**
1.  **The Cross Product (The math trick):**
    Because both speed and magnetic field are 3D arrows (vectors), the force will push in a 3rd, completely different 3D direction. To find this new direction, we use a matrix math trick called the "Cross Product" ($\vec{v} \times \vec{B}$).
    We set up a grid:
    $$ \vec{v} \times \vec{B} = \begin{vmatrix} \hat{i} & \hat{j} & \hat{k} \\ 2 & -4 & 1 \\ 1 & 2 & -1 \end{vmatrix} $$
2.  **Solve the Grid:**
    *   **For $\hat{i}$:** Cover the $\hat{i}$ column. Multiply diagonally: $(-4 \times -1) - (1 \times 2) = 4 - 2 = 2$.
    *   **For $\hat{j}$:** Cover the $\hat{j}$ column. Multiply diagonally, but always flip the sign for the middle one: $-((2 \times -1) - (1 \times 1)) = -(-2 - 1) = 3$.
    *   **For $\hat{k}$:** Cover the $\hat{k}$ column. Multiply diagonally: $(2 \times 2) - (-4 \times 1) = 4 - (-4) = 8$.
    So, our new Force direction arrow is: $2\hat{i} + 3\hat{j} + 8\hat{k}$.
3.  **Find the "Length" of this arrow (Magnitude):**
    To find the total size of this 3D arrow, we use a 3D Pythagorean theorem.
    $$ \text{Size} = \sqrt{2^2 + 3^2 + 8^2} $$
    $$ \text{Size} = \sqrt{4 + 9 + 64} = \sqrt{77} \approx 8.775 $$
4.  **Calculate Final Force:**
    The formula is $F = q \times \text{Size}$. The charge of a proton ($q$) is $1.6 \times 10^{-19}$.
    $$ F = (1.6 \times 10^{-19}) \times 8.775 \approx 1.4 \times 10^{-18} \text{ Newtons} $$

**Final Answer:** The magnitude of the magnetic force is roughly $1.4 \times 10^{-18} \text{ N}$.

