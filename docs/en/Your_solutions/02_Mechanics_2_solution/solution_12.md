# Physics Analysis: Work and Energy with a Constant Force

This document provides a comprehensive derivation of the kinematics and energetics of a mass subjected to a constant 2D force vector.

## 1. Key Definitions & Formulas

### Newton's Second Law
Acceleration is the ratio of the net force to the mass:

$$
\vec a = \frac{\vec F}{m}
$$

### Kinematic Equations (Constant Acceleration)
Since the force is constant, the acceleration is constant. We can use the following vector integrals:

$$
\vec v(t) = \vec v_0 + \vec a t
$$

$$
\vec r(t) = \vec r_0 + \vec v_0 t + \frac{1}{2} \vec a t^2
$$

### Work ($W$)
Work done by a constant force over a displacement $\Delta \vec r$:

$$
W = \vec F \cdot \Delta \vec r = F_x \Delta x + F_y \Delta y
$$

### Work-Energy Theorem
The total work done on a particle is equal to the change in its kinetic energy ($K$):

$$
W = \Delta K = \frac{1}{2} m v_f^2 - \frac{1}{2} m v_i^2
$$

---

## 2. Step-by-Step Solution

**Given:**
* $m = 2 \text{ kg}$
* $\vec F = [6, 2] \text{ N}$
* $\vec v_0 = (1, -1) \text{ m/s}$
* $\vec r_0 = (0, 0) \text{ m}$

### Step 1: Determine $\vec a(t)$
Using Newton's Second Law:

$$
\vec a = \frac{[6, 2]}{2} = [3, 1] \text{ m/s}^2
$$

The acceleration is constant over time.

---

### Step 2: Determine $\vec v(t)$
Apply the initial velocity $\vec v_0$:

$$
\vec v(t) = (1, -1) + [3, 1]t = (1 + 3t, -1 + t) \text{ m/s}
$$

---

### Step 3: Determine $\vec r(t)$
Apply the initial position $\vec r_0$:

$$
\vec r(t) = (0, 0) + (1, -1)t + \frac{1}{2}[3, 1]t^2
$$

$$
\vec r(t) = (t + 1.5t^2, -t + 0.5t^2) \text{ m}
$$

---

### Step 4: Trajectory of Motion
The trajectory is a **parabola** because $x$ and $y$ are both quadratic functions of $t$, and the force (acceleration) is constant. 



To visualize, at $t=3\text{s}$:
* $x(3) = 3 + 1.5(9) = 16.5 \text{ m}$
* $y(3) = -3 + 0.5(9) = 1.5 \text{ m}$

---

### Step 5: Work done at $t=3\text{s}$
First, find the displacement vector $\Delta \vec r$ at $t=3\text{s}$:

$$
\Delta \vec r = \vec r(3) - \vec r(0) = (16.5, 1.5) \text{ m}
$$

Now, calculate the dot product with the force vector:

$$
W = \vec F \cdot \Delta \vec r = (6)(16.5) + (2)(1.5)
$$

$$
W = 99 + 3 = 102 \text{ J}
$$

---

### Step 6: Verify Work-Energy Theorem
**1. Initial Kinetic Energy ($K_i$):**
Find the magnitude of initial velocity $v_0^2 = 1^2 + (-1)^2 = 2$:

$$
K_i = \frac{1}{2}(2)(2) = 2 \text{ J}
$$

**2. Final Kinetic Energy ($K_f$) at $t=3\text{s}$:**
Find velocity components at $t=3\text{s}$:
* $v_x(3) = 1 + 3(3) = 10 \text{ m/s}$
* $v_y(3) = -1 + 1(3) = 2 \text{ m/s}$
* $v_f^2 = 10^2 + 2^2 = 104$

$$
K_f = \frac{1}{2}(2)(104) = 104 \text{ J}
$$

**3. Change in Kinetic Energy ($\Delta K$):**

$$
\Delta K = 104 \text{ J} - 2 \text{ J} = 102 \text{ J}
$$

**Conclusion:** Since $W = \Delta K = 102 \text{ J}$, the results are perfectly consistent with the Work-Energy Theorem.

---

## 3. Summary Table

| Parameter | Vector Value (at $t=3\text{s}$) | Scalar Value |
| :--- | :--- | :--- |
| Acceleration | $[3, 1]$ | $3.16 \text{ m/s}^2$ |
| Velocity | $(10, 2)$ | $10.20 \text{ m/s}$ |
| Position | $(16.5, 1.5)$ | Distance: $16.57 \text{ m}$ |
| Work Done | - | $102 \text{ J}$ |
| Energy Change| - | $102 \text{ J}$ |
