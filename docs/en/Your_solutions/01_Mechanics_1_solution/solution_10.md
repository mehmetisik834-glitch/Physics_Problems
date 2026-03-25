## 10. 3D Kinematics: Elliptical Helix Analysis

### Problem Statement
$\vec{r}(t) = (a \cos(\omega t), b \sin(\omega t), bt)$

### 1. Trajectory Equation
By eliminating the parameter $t$ using the trig identity $\cos^2\theta + \sin^2\theta = 1$:

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

The path is an **elliptical helix**. It climbs in the $z$-direction while revolving around an elliptical cylinder.

### 2. Path Length Calculation
The velocity vector is:

$$
\vec{v}(t) = (-a\omega \sin(\omega t), b\omega \cos(\omega t), b)
$$

The path length $s$ from $0$ to $t_0$ is:

$$
s = \int_{0}^{t_0} \sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2} \, dt
$$

### 3. Special Cases
- **Circular Helix:** If $a = b$, the base is a circle, and the speed is constant: $|\vec{v}| = b\sqrt{\omega^2 + 1}$.
- **Straight Line:** If $\omega = 0$, the point moves only in the $x$ and $z$ directions.
- **Flat Ellipse:** If $b = 0$ (for the $z$ component), the motion is restricted to a 2D ellipse in the $xy$-plane.
