# Physics Analysis: Dynamics with Friction in a Stacked System

This analysis determines the acceleration of a lower block when the upper block is stationary (tethered) and friction is present at multiple interfaces.

## 1. Key Definitions & Formulas

### Newton's Second Law
The acceleration of an object is directly proportional to the net force acting on it and inversely proportional to its mass:

$$
\sum F = ma
$$

### Kinetic Friction ($f_k$)
Friction that opposes the motion of surfaces sliding past each other. It is calculated as:

$$
f_k = \mu_k \cdot F_N
$$

Where:
* **$\mu_k$:** Coefficient of kinetic friction.
* **$F_N$:** Normal force (the perpendicular force pressing the surfaces together).

### Normal Force in Stacks
* At the interface between the two blocks, $F_N$ is the weight of the top block.
* At the interface between the bottom block and the floor, $F_N$ is the combined weight of both blocks.

---

## 2. System Configuration

**Given Data:**
* Mass of top block ($m_1$): $5 \text{ kg}$
* Mass of bottom block ($m_2$): $10 \text{ kg}$
* Applied force ($F_{app}$): $45 \text{ N}$ (acting on $m_2$)
* Coefficient of kinetic friction ($\mu_k$): $0.2$
* Gravitational acceleration ($g$): $9.8 \text{ m/s}^2$

**Important Note:** Since the 5 kg block is tied to the wall, it does not move ($a_1 = 0$). However, the 10 kg block slides underneath it, creating friction at **two** surfaces:
1. Between the 5 kg block and the 10 kg block.
2. Between the 10 kg block and the floor.

---

## 3. Step-by-Step Solution

### Step 1: Calculate Frictional Forces

**Friction at the top surface ($f_{k1}$):**
The normal force here is just the weight of the top block ($m_1 g$).

$$
f_{k1} = \mu_k \cdot m_1 \cdot g
$$

$$
f_{k1} = 0.2 \cdot 5 \cdot 9.8 = 9.8 \text{ N}
$$

**Friction at the bottom surface ($f_{k2}$):**
The normal force here is the weight of both blocks pressing down on the floor ($(m_1 + m_2)g$).

$$
f_{k2} = \mu_k \cdot (m_1 + m_2) \cdot g
$$

$$
f_{k2} = 0.2 \cdot (5 + 10) \cdot 9.8
$$

$$
f_{k2} = 0.2 \cdot 15 \cdot 9.8 = 29.4 \text{ N}
$$

### Step 2: Determine the Net Force on the 10 kg Block
The 10 kg block is being pulled by $F_{app}$, while both frictional forces oppose this motion.

$$
\sum F = F_{app} - f_{k1} - f_{k2}
$$

$$
\sum F = 45 \text{ N} - 9.8 \text{ N} - 29.4 \text{ N}
$$

$$
\sum F = 45 - 39.2 = 5.8 \text{ N}
$$

### Step 3: Calculate Acceleration
Using Newton's Second Law for the 10 kg block ($m_2$):

$$
a = \frac{\sum F}{m_2}
$$

$$
a = \frac{5.8 \text{ N}}{10 \text{ kg}} = 0.58 \text{ m/s}^2
$$

---

## 4. Final Result

The acceleration of the 10 kg block is **$0.58 \text{ m/s}^2$**.

### Summary of Forces
| Force Component | Value | Direction |
| :--- | :--- | :--- |
| Applied Force | $45.0 \text{ N}$ | Forward |
| Friction (Top Block) | $9.8 \text{ N}$ | Backward |
| Friction (Floor) | $29.4 \text{ N}$ | Backward |
| **Net Force** | **$5.8 \text{ N}$** | **Forward** |
