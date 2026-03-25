## 4. Vector Calculus: Kinematics Derivation

### Problem Statement
Given the position vector of an object:

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

Find the velocity and acceleration vectors.

---

### 1. Velocity Vector ($\vec{v}$)
Velocity is the first derivative of position with respect to time $t$:

$$
\vec{v}(t) = \frac{d}{dt} \left[ (3t^2)\hat{i} + (5t - 8t^2)\hat{j} \right]
$$

Differentiating term by term:

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

### 2. Acceleration Vector ($\vec{a}$)
Acceleration is the derivative of the velocity vector:

$$
\vec{a}(t) = \frac{d}{dt} \left[ (6t)\hat{i} + (5 - 16t)\hat{j} \right]
$$

Differentiating term by term:

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$

### Summary of Results
| Vector | Expression |
| :--- | :--- |
| **Position** | $\vec{r}(t) = 3t^2 \hat{i} + (5t - 8t^2) \hat{j}$ |
| **Velocity** | $\vec{v}(t) = 6t \hat{i} + (5 - 16t) \hat{j}$ |
| **Acceleration** | $\vec{a}(t) = 6 \hat{i} - 16 \hat{j}$ |
