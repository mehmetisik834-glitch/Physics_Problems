## 7. Parametric Path and Acceleration Analysis

### Problem Statement
Given: $x(t) = 2t^2$ and $y(t) = 3t^3$.

### 1. Elimination of Parameter $t$
From $x = 2t^2$, we have $t^3 = (x/2)^{3/2}$. Substituting into $y$:

$$
y = 3\left(\frac{x}{2}\right)^{3/2} \implies y^2 = \frac{9x^3}{8}
$$

The trajectory follows the curve $8y^2 = 9x^3$.

### 2. Velocity and Acceleration Vectors
The position vector is $\vec{r}(t) = \langle 2t^2, 3t^3 \rangle$.

**Velocity:**

$$
\vec{v}(t) = \frac{d\vec{r}}{dt} = \langle 4t, 9t^2 \rangle
$$

**Speed (Magnitude of Velocity):**

$$
|\vec{v}(t)| = \sqrt{16t^2 + 81t^4}
$$

**Acceleration:**

$$
\vec{a}(t) = \frac{d\vec{v}}{dt} = \langle 4, 18t \rangle
$$

**Acceleration Magnitude:**

$$
|\vec{a}(t)| = \sqrt{16 + 324t^2}
$$

### 3. Interpretation
The acceleration is **not constant**. While the horizontal acceleration is constant ($4 \text{ units/s}^2$), the vertical acceleration increases linearly with time ($18t$), causing the total acceleration vector to change in both magnitude and direction.
