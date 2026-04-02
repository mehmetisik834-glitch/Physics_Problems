# Physics Analysis: Dynamics and Power in a 3D Force Field

This document derives the kinematic and dynamic properties of a particle moving through a specific force field based on its coordinate equations.

## 1. Key Definitions & Formulas

### Velocity ($\mathbf{v}$)
The rate of change of position with respect to time. It is the first derivative of the position vector:

$$
\mathbf{v}(t) = \frac{d\mathbf{r}}{dt} = \left( \frac{dx}{dt}, \frac{dy}{dt}, \frac{dz}{dt} \right)
$$

### Acceleration ($\mathbf{a}$)
The rate of change of velocity with respect to time. It is the second derivative of the position vector:

$$
\mathbf{a}(t) = \frac{d\mathbf{v}}{dt} = \frac{d^2\mathbf{r}}{dt^2}
$$

### Momentum ($\mathbf{p}$)
The product of an object's mass and its velocity:

$$
\mathbf{p}(t) = m \cdot \mathbf{v}(t)
$$

### Force ($\mathbf{F}$)
According to Newton's Second Law, the force is the product of mass and acceleration:

$$
\mathbf{F}(t) = m \cdot \mathbf{a}(t)
$$

### Power ($P$)
The rate at which work is done or energy is transferred. For a particle in motion, it is the dot product of the force and velocity vectors:

$$
P(t) = \mathbf{F}(t) \cdot \mathbf{v}(t) = F_x v_x + F_y v_y + F_z v_z
$$

---

## 2. Step-by-Step Solution

**Given:**
* Mass $m = 0.5 \text{ kg}$
* $x(t) = 5t^2 - t$
* $y(t) = 2t^3$
* $z(t) = -3t + 2$

### Step 1: Velocity Vector $\mathbf{v}(t)$
Differentiate each component with respect to $t$:

$$
v_x = \frac{dx}{dt} = 10t - 1
$$

$$
v_y = \frac{dy}{dt} = 6t^2
$$

$$
v_z = \frac{dz}{dt} = -3
$$

**Velocity Vector:** $\mathbf{v}(t) = (10t - 1) \mathbf{i} + (6t^2) \mathbf{j} - 3 \mathbf{k}$

---

### Step 2: Momentum Vector $\mathbf{p}(t)$
Multiply the velocity by mass $m = 0.5$:

$$
\mathbf{p}(t) = 0.5 \cdot [(10t - 1) \mathbf{i} + 6t^2 \mathbf{j} - 3 \mathbf{k}]
$$

**Momentum Vector:** $\mathbf{p}(t) = (5t - 0.5) \mathbf{i} + 3t^2 \mathbf{j} - 1.5 \mathbf{k}$

---

### Step 3: Acceleration Vector $\mathbf{a}(t)$
Differentiate the velocity components with respect to $t$:

$$
a_x = \frac{dv_x}{dt} = 10
$$

$$
a_y = \frac{dv_y}{dt} = 12t
$$

$$
a_z = \frac{dv_z}{dt} = 0
$$

**Acceleration Vector:** $\mathbf{a}(t) = 10 \mathbf{i} + 12t \mathbf{j} + 0 \mathbf{k}$

---

### Step 4: Force Vector $\mathbf{F}(t)$
Multiply the acceleration by mass $m = 0.5$:

$$
\mathbf{F}(t) = 0.5 \cdot [10 \mathbf{i} + 12t \mathbf{j}]
$$

**Force Vector:** $\mathbf{F}(t) = 5 \mathbf{i} + 6t \mathbf{j} + 0 \mathbf{k}$

---

### Step 5: Power Transferred $P(t)$
Calculate the dot product $\mathbf{F}(t) \cdot \mathbf{v}(t)$:

$$
P(t) = F_x v_x + F_y v_y + F_z v_z
$$

$$
P(t) = (5)(10t - 1) + (6t)(6t^2) + (0)(-3)
$$

$$
P(t) = 50t - 5 + 36t^3
$$

**Power Function:** $P(t) = 36t^3 + 50t - 5 \text{ Watts}$

---

## 3. Summary Table

| Quantity | Expression | Units |
| :--- | :--- | :--- |
| Velocity | $(10t - 1, 6t^2, -3)$ | $\text{m/s}$ |
| Momentum | $(5t - 0.5, 3t^2, -1.5)$ | $\text{kg}\cdot\text{m/s}$ |
| Acceleration | $(10, 12t, 0)$ | $\text{m/s}^2$ |
| Force | $(5, 6t, 0)$ | $\text{N}$ |
| Power | $36t^3 + 50t - 5$ | $\text{W}$ |
