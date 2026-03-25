# Physics Problem: Projectile Motion Analysis

## 1. Problem Statement
A projectile is fired from the ground with an initial velocity of $100 \text{ m/s}$ at an angle of $37^\circ$ above the horizontal. Assume no air resistance and $g = 9.8 \text{ m/s}^2$.

---

## 2. Differential Equations of Motion
Applying Newton's Second Law ($\sum F = ma$):

**Horizontal ($x$):**
No forces act in the x-direction.

$$
\frac{d^2x}{dt^2} = 0
$$

**Vertical ($y$):**
Gravity is the only force acting.

$$
\frac{d^2y}{dt^2} = -g
$$

---

## 3. Calculations

### Initial Velocity Components
Using $\sin(37^\circ) \approx 0.6$ and $\cos(37^\circ) \approx 0.8$:

$$
v_{0x} = 100 \cdot \cos(37^\circ) = 80 \text{ m/s}
$$

$$
v_{0y} = 100 \cdot \sin(37^\circ) = 60 \text{ m/s}
$$

### Time of Flight ($T$)
Calculated where vertical displacement $y = 0$:

$$
T = \frac{2 v_0 \sin\theta}{g} = \frac{2(60)}{9.8} \approx 12.24 \text{ s}
$$

### Maximum Height ($H$)
Calculated where vertical velocity $v_y = 0$:

$$
H = \frac{(v_0 \sin\theta)^2}{2g} = \frac{60^2}{2(9.8)} \approx 183.67 \text{ m}
$$

### Range ($R$)
The total horizontal distance:

$$
R = v_{0x} \cdot T = 80 \cdot 12.24 \approx 979.2 \text{ m}
$$
