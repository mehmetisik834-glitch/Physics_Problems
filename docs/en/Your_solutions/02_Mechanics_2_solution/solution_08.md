# Physics Analysis: Work, Energy, and Variable Forces

This document explores the dynamics and energetics of a system governed by a linear restoring force, such as a spring.

## 1. Key Definitions & Formulas

### Newton's Second Law
The net force acting on an object is equal to its mass times its acceleration:

$$
F = m a = m \frac{d^2x}{dt^2}
$$

### Work Done by a Variable Force
For a force that changes with position $F(x)$, the work done $W$ during a displacement from $x_1$ to $x_2$ is the integral of the force over that distance:

$$
W = \int_{x_1}^{x_2} F(x) \, dx
$$

### Potential Energy ($U$)
Potential energy is defined as the negative of the work done by a conservative force:

$$
\Delta U = -W = -\int_{x_1}^{x_2} F(x) \, dx
$$

### Relationship between Force and Potential
A conservative force is the negative gradient of its potential energy:

$$
F(x) = -\frac{dU}{dx}
$$

---

## 2. Step-by-Step Solution

**Given:** $F(x) = -kx$

### Step 1: Equation of Motion and its Solution
Using Newton's Second Law:

$$
m \frac{d^2x}{dt^2} = -kx
$$

Rearranging into the standard form of a second-order linear differential equation:

$$
\frac{d^2x}{dt^2} + \frac{k}{m}x = 0
$$

By defining the angular frequency $\omega^2 = \frac{k}{m}$, the general solution is:

$$
x(t) = A \cos(\omega t + \phi)
$$

This describes **Simple Harmonic Motion (SHM)**, where the object oscillates about the equilibrium position $x=0$.

### Step 2: Calculate Work Done (from $0$ to $x_0$)
The work done by the force $F(x) = -kx$ as the object moves from $0$ to $x_0$:

$$
W = \int_{0}^{x_0} (-kx) \, dx
$$

$$
W = -k \left[ \frac{1}{2}x^2 \right]_{0}^{x_0}
$$

$$
W = -\frac{1}{2}kx_0^2
$$

### Step 3: Interpret as Potential Energy
The change in potential energy $U$ is defined as the negative of the work done by the conservative restoring force:

$$
U(x) = -W = -\left( -\frac{1}{2}kx^2 \right)
$$

$$
U(x) = \frac{1}{2}kx^2
$$

This represents the **Elastic Potential Energy** stored in the system due to its displacement from equilibrium.

### Step 4: Verify $F = -\frac{dU}{dx}$
To verify the relationship, we take the negative derivative of our derived potential energy:

$$
-\frac{dU}{dx} = -\frac{d}{dx} \left( \frac{1}{2}kx^2 \right)
$$

$$
-\frac{dU}{dx} = -\frac{1}{2}k(2x) = -kx
$$

Since $-kx$ is the original force $F(x)$, the relationship is verified.

---

## 3. Graphical Representation



* **Graph of $F(x) = -kx$:** A straight line passing through the origin with a negative slope $-k$. This shows that as displacement increases, the force becomes more negative (acts in the opposite direction).
* **Graph of $U(x) = \frac{1}{2}kx^2$:** A parabola opening upwards with its vertex at the origin. This shows that energy increases quadratically regardless of whether the displacement is positive or negative.



[Image of potential energy curve of a simple harmonic oscillator]


---

## 4. Summary

| Quantity | Mathematical Expression | Physical Interpretation |
| :--- | :--- | :--- |
| Force | $F = -kx$ | Restoring force proportional to displacement. |
| Potential Energy | $U = \frac{1}{2}kx^2$ | Energy stored in the "stretched" system. |
| Equation of Motion | $\ddot{x} + \omega^2x = 0$ | System undergoes periodic oscillation. |
