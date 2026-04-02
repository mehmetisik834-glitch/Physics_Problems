# Physics Analysis: Perfectly Inelastic Collision

This analysis examines the interaction between a moving object (runner) and a stationary object (cart) when they couple together upon impact.

## 1. Key Definitions & Formulas

### Momentum ($p$)
Momentum is the product of an object's mass and its velocity. It is a vector quantity.

$$
p = mv
$$

### Conservation of Momentum
In an isolated system (where no external forces like friction are considered), the total momentum before the collision is equal to the total momentum after the collision.

$$
\sum p_{initial} = \sum p_{final}
$$

### Perfectly Inelastic Collision
A collision where the two objects "stick together" and move with a common final velocity ($v_f$). In these collisions, **momentum is conserved**, but **kinetic energy is not conserved** (some energy is converted into heat, sound, or deformation).

### Kinetic Energy ($K$)
The energy of motion is defined as:

$$
K = \frac{1}{2}mv^2
$$

---

## 2. Problem Solving

**Given Data:**
* Mass of runner ($m_1$): $70 \text{ kg}$
* Velocity of runner ($v_1$): $3 \text{ m/s}$
* Mass of cart ($m_2$): $140 \text{ kg}$
* Velocity of cart ($v_2$): $0 \text{ m/s}$ (stationary)

### Step 1: Calculate Final Velocity ($v_f$)
Using the conservation of momentum for two objects that stick together:

$$
m_1v_1 + m_2v_2 = (m_1 + m_2)v_f
$$

Substitute the known values:

$$
(70 \cdot 3) + (140 \cdot 0) = (70 + 140) \cdot v_f
$$

$$
210 + 0 = 210 \cdot v_f
$$

$$
v_f = \frac{210}{210} = 1 \text{ m/s}
$$

**Result:** The final speed of the cart with the runner is **$1 \text{ m/s}$**.

---

### Step 2: Determine if Kinetic Energy is Conserved
To check for conservation, we compare the total kinetic energy before ($K_i$) and after ($K_f$) the collision.

**Initial Kinetic Energy ($K_i$):**

$$
K_i = \frac{1}{2}m_1v_1^2 + \frac{1}{2}m_2v_2^2
$$

$$
K_i = \frac{1}{2}(70)(3^2) + 0 = \frac{1}{2}(70)(9) = 315 \text{ J}
$$

**Final Kinetic Energy ($K_f$):**

$$
K_f = \frac{1}{2}(m_1 + m_2)v_f^2
$$

$$
K_f = \frac{1}{2}(210)(1^2) = 105 \text{ J}
$$

**Comparison:**
* $K_i = 315 \text{ J}$
* $K_f = 105 \text{ J}$

---

## 3. Conclusion & Explanation

**Is kinetic energy conserved?**
**No.** Kinetic energy is not conserved in this collision.

**Explanation:**
This is a **perfectly inelastic collision**. While the momentum of the system remains constant, a significant portion of the initial kinetic energy ($210 \text{ J}$ in this case) was transformed into other forms of energy. 

When the runner jumps onto the cart, energy is "lost" to:
* **Internal Friction:** The work done to bring the runner's body to the same speed as the cart.
* **Sound:** The noise of the impact.
* **Deformation/Heat:** Slight thermal energy increase due to the impact forces.

In any collision where objects stick together, the loss of kinetic energy is mathematically guaranteed to be at its maximum relative to the conservation of momentum.
