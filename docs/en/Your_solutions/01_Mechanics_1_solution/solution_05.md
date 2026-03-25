# Physics and Kinematics Problem Set

This repository contains step-by-step analytical solutions for classical mechanics and vector calculus problems.

---

## 1. Projectile Motion
**Problem:** $v_0 = 100 \text{ m/s}$, $\theta = 37^\circ$, $g = 9.8 \text{ m/s}^2$.

### Differential Equations
Horizontal ($x$):

$$
\frac{d^2x}{dt^2} = 0
$$

Vertical ($y$):

$$
\frac{d^2y}{dt^2} = -g
$$

### Results
- **Time of Flight ($T$):** $\approx 12.24 \text{ s}$
- **Max Height ($H$):** $\approx 183.67 \text{ m}$
- **Range ($R$):** $\approx 979.2 \text{ m}$

---

## 2. Range Optimization
**Goal:** Prove max range occurs at $45^\circ$.

The range formula is:

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

The function $\sin(2\theta)$ is maximized when its value is $1$:

$$
2\theta = 90^\circ \implies \theta = 45^\circ
$$

---

## 3. Path Intersection
**Paths:** $A(t) = (2+t, 8-3t)$ and $B(t) = (2t-1, 2t+2)$.

### Collision Check
Setting $x_A = x_B$: $2+t = 2t-1 \implies t=3$.
Checking $y$ at $t=3$: $y_A = -1, y_B = 8$. 
**Result:** No collision.

### Minimum Distance
Distance squared $S(t) = 26t^2 - 66t + 45$. 

$$
\frac{dS}{dt} = 52t - 66 = 0 \implies t \approx 1.27 \text{ s}
$$

---

## 4. Vector Calculus
**Position:** $\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}$

### Velocity Vector ($\vec{v}$)

$$
\vec{v}(t) = \frac{d\vec{r}}{dt} = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

### Acceleration Vector ($\vec{a}$)

$$
\vec{a}(t) = \frac{d\vec{v}}{dt} = 6\hat{i} - 16\hat{j}
$$

---

## 5. Relative Velocity
**Data:** $v_{river} = 2 \text{ m/s}$ (East), $v_{boat} = 5 \text{ m/s}$, Width = $200 \text{ m}$.

### Heading Angle ($\theta$)
To cancel the drift:

$$
\sin(\theta) = \frac{2}{5} \implies \theta \approx 23.58^\circ \text{ West of North}
$$

### Crossing Time ($t$)
Resultant velocity $v_y = \sqrt{5^2 - 2^2} = \sqrt{21}$.

$$
t = \frac{200}{\sqrt{21}} \approx 43.64 \text{ s}
$$

