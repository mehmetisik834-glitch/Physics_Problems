# Simple Pendulum Physics: Gravitational Dependence

Before solving the problems, let's review the fundamental physics governing a simple pendulum.

## 1. Key Definitions & Formulas

### Definitions
* **Period ($T$):** The time taken for one complete cycle of an oscillation (back and forth).
* **Gravitational Acceleration ($g$):** The acceleration of an object due to gravity. On Earth, $g \approx 9.81 \text{ m/s}^2$.
* **Length ($L$):** The distance from the pivot point to the center of mass of the pendulum bob.

### The Period Formula
For small angles of oscillation, the period of a simple pendulum is given by:

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

From this formula, we can derive two important relationships:
1. **Relationship with Gravity:** $T \propto \frac{1}{\sqrt{g}}$ (Period is inversely proportional to the square root of gravity).
2. **Relationship with Length:** $T \propto \sqrt{L}$ (Period is directly proportional to the square root of length).

---

## 2. Problem Solving

### Part A: Period on the Moon
**Scenario:** A pendulum has a period $T_E = 4\text{s}$ on Earth. We need to find $T_M$ on the Moon, where $g_M = \frac{1}{6}g_E$.

**Step 1: Set up the ratio**
Since $L$ remains constant, we can compare the periods on Earth and the Moon using a ratio:

$$
\frac{T_M}{T_E} = \frac{2\pi \sqrt{\frac{L}{g_M}}}{2\pi \sqrt{\frac{L}{g_E}}} = \sqrt{\frac{g_E}{g_M}}
$$

**Step 2: Substitute the gravity relationship**
We know $g_M = \frac{g_E}{6}$, so $\frac{g_E}{g_M} = 6$.

$$
\frac{T_M}{T_E} = \sqrt{6}
$$

**Step 3: Calculate the Moon period**

$$
T_M = T_E \cdot \sqrt{6} = 4 \cdot \sqrt{6}
$$

$$
T_M \approx 4 \cdot 2.449 = 9.796 \text{ seconds}
$$

**Conclusion:** The period on the Moon would be approximately **9.80 seconds**. Because gravity is weaker, the restoring force is smaller, making the pendulum swing much slower.

---

### Part B: Required Length for a 1-Second Period
**Scenario:** Find $L$ such that $T = 1\text{s}$ on Earth ($g = 9.81 \text{ m/s}^2$).

**Step 1: Isolate $L$ from the period formula**
First, square both sides:

$$
T^2 = 4\pi^2 \left( \frac{L}{g} \right)
$$

Now, solve for $L$:

$$
L = \frac{T^2 \cdot g}{4\pi^2}
$$

**Step 2: Plug in the values**
Using $T = 1\text{s}$ and $g = 9.81 \text{ m/s}^2$:

$$
L = \frac{1^2 \cdot 9.81}{4\pi^2}
$$

$$
L = \frac{9.81}{4 \cdot 3.14159^2} \approx \frac{9.81}{39.478}
$$

**Step 3: Final Calculation**

$$
L \approx 0.2485 \text{ meters}
$$

**Conclusion:** To have a period of exactly 1 second on Earth, the pendulum needs to be approximately **24.85 cm** long.
