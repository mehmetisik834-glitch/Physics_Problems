## 6. Variable Velocity: Kinematics via Calculus

### Problem Statement
Given $v(t) = t^2 + 2t - 5$ and initial condition $x(0) = 4$. Find position and acceleration at $t = 3$.

### 1. Finding Position $x(t)$
Position is the integral of velocity:

$$
x(t) = \int (t^2 + 2t - 5) \, dt = \frac{t^3}{3} + t^2 - 5t + C
$$

Using $x(0) = 4$, we find $C = 4$. Therefore:

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

At $t = 3$:

$$
x(3) = \frac{27}{3} + 9 - 15 + 4 = 7
$$

### 2. Finding Acceleration $a(t)$
Acceleration is the derivative of velocity:

$$
a(t) = \frac{d}{dt}(t^2 + 2t - 5) = 2t + 2
$$

At $t = 3$:

$$
a(3) = 2(3) + 2 = 8
$$

### Summary of Results at $t = 3$
- **Position:** $x = 7$
- **Acceleration:** $a = 8$
