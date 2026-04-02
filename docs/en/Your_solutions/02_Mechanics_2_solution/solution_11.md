# Physics Analysis: Dynamics with a Time-Dependent Force

This document derives the trajectory and velocity of a particle subjected to a force that changes over time.

## 1. Key Definitions & Formulas

### Newton's Second Law (Vector Form)
The acceleration of a particle is the force divided by its mass:

$$
\mathbf{a}(t) = \frac{\mathbf{F}(t)}{m}
$$

### Kinematic Integrals
To find velocity from acceleration, we integrate with respect to time:

$$
\mathbf{v}(t) = \mathbf{v}_0 + \int_{0}^{t} \mathbf{a}(t') \, dt'
$$

To find position from velocity, we integrate again:

$$
\mathbf{r}(t) = \mathbf{r}_0 + \int_{0}^{t} \mathbf{v}(t') \, dt'
$$

Where:
* **$\mathbf{v}_0$:** Initial velocity vector at $t=0$.
* **$\mathbf{r}_0$:** Initial position vector at $t=0$.

---

## 2. Step-by-Step Solution

**Given Data:**
* Mass $m = 3 \text{ kg}$
* Force $\mathbf{F}(t) = (15t, 3t - 12, -6t^2) \text{ N}$
* $\mathbf{v}_0 = (2, 0, 1) \text{ m/s}$
* $\mathbf{r}_0 = (5, 2, -3) \text{ m}$

### Step 1: Find the Acceleration $\mathbf{a}(t)$
Divide each component of the force by the mass ($m=3$):

$$
a_x = \frac{15t}{3} = 5t
$$

$$
a_y = \frac{3t - 12}{3} = t - 4
$$

$$
a_z = \frac{-6t^2}{3} = -2t^2
$$

**Acceleration Vector:** $\mathbf{a}(t) = (5t, t - 4, -2t^2) \text{ m/s}^2$

---

### Step 2: Determine Velocity $\mathbf{v}(t)$
Integrate the acceleration components and add the initial velocity $\mathbf{v}_0$:

$$
v_x(t) = 2 + \int_{0}^{t} 5t' \, dt' = 2 + \frac{5}{2}t^2
$$

$$
v_y(t) = 0 + \int_{0}^{t} (t' - 4) \, dt' = \frac{1}{2}t^2 - 4t
$$

$$
v_z(t) = 1 + \int_{0}^{t} -2t'^2 \, dt' = 1 - \frac{2}{3}t^3
$$

**Velocity Vector:** $\mathbf{v}(t) = \left( 2 + 2.5t^2, 0.5t^2 - 4t, 1 - \frac{2}{3}t^3 \right) \text{ m/s}$

---

### Step 3: Determine Position $\mathbf{r}(t)$
Integrate the velocity components and add the initial position $\mathbf{r}_0$:

**X-component:**

$$
x(t) = 5 + \int_{0}^{t} (2 + 2.5t'^2) \, dt' = 5 + 2t + \frac{2.5}{3}t^3 = 5 + 2t + \frac{5}{6}t^3
$$

**Y-component:**

$$
y(t) = 2 + \int_{0}^{t} (0.5t'^2 - 4t') \, dt' = 2 + \frac{0.5}{3}t^3 - 2t^2 = 2 + \frac{1}{6}t^3 - 2t^2
$$

**Z-component:**

$$
z(t) = -3 + \int_{0}^{t} (1 - \frac{2}{3}t'^3) \, dt' = -3 + t - \frac{2}{12}t^4 = -3 + t - \frac{1}{6}t^4
$$

---

## 3. Final Results

The time-dependent vectors for the particle are:

### Velocity Vector $\mathbf{v}(t)$

$$
\mathbf{v}(t) = \begin{bmatrix} 2 + 2.5t^2 \\ 0.5t^2 - 4t \\ 1 - \frac{2}{3}t^3 \end{bmatrix} \text{ m/s}
$$

### Position Vector $\mathbf{r}(t)$

$$
\mathbf{r}(t) = \begin{bmatrix} 5 + 2t + \frac{5}{6}t^3 \\ 2 - 2t^2 + \frac{1}{6}t^3 \\ -3 + t - \frac{1}{6}t^4 \end{bmatrix} \text{ m}
$$

---

## 4. Summary Table of Components

| Axis | Acceleration ($a$) | Velocity ($v$) | Position ($r$) |
| :--- | :--- | :--- | :--- |
| **X** | $5t$ | $2 + 2.5t^2$ | $5 + 2t + 0.833t^3$ |
| **Y** | $t - 4$ | $0.5t^2 - 4t$ | $2 - 2t^2 + 0.167t^3$ |
| **Z** | $-2t^2$ | $1 - 0.667t^3$ | $-3 + t - 0.167t^4$ |
