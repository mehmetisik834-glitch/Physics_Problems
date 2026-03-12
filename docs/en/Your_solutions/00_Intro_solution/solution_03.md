# Physics Problem: Proportionality in Universal Gravitation

## 1. Definitions and Formulas

### Universal Law of Gravitation
Proposed by Isaac Newton, this law states that every point mass attracts every other point mass by a force acting along the line intersecting both points. This force is proportional to the product of the two masses and inversely proportional to the square of the distance between them.



[Image of Newton's law of universal gravitation diagram]


### The Formula

$$
F = G \frac{m_1 m_2}{r^2}
$$

Where:
* **$F$**: Gravitational force between masses.
* **$G$**: Gravitational constant ($\approx 6.674 \times 10^{-11} \text{ N·m}^2/\text{kg}^2$).
* **$m_1, m_2$**: Masses of the two objects.
* **$r$**: Distance between the centers of the masses.

### Relationships (Proportionality)
* **Direct Proportionality:** $F \propto m_1 m_2$. If the product of the masses increases, the force increases.
* **Inverse-Square Law:** $F \propto \frac{1}{r^2}$. If the distance increases, the force decreases by the square of the factor of increase.

---

## 2. Problem Statement

Determine the factor by which the force $F$ changes if:
1.  The distance $r$ is **doubled**.
2.  Both masses ($m_1$ and $m_2$) are **halved**.

---

## 3. Step-by-Step Solution

### Step 1: Define the initial state
Let the initial force be $F_1$:

$$
F_1 = G \frac{m_1 m_2}{r^2}
$$

### Step 2: Define the new variables (The "Primes")
According to the problem, we create new values for our variables:
* New mass 1: $m_1' = \frac{1}{2}m_1$
* New mass 2: $m_2' = \frac{1}{2}m_2$
* New distance: $r' = 2r$

### Step 3: Set up the equation for the new force ($F_2$)
Substitute the new values into the original gravitation formula:

$$
F_2 = G \frac{(\frac{1}{2}m_1)(\frac{1}{2}m_2)}{(2r)^2}
$$

### Step 4: Simplify the expression
First, handle the numerator (the masses):

$$
\frac{1}{2}m_1 \times \frac{1}{2}m_2 = \frac{1}{4} m_1 m_2
$$

Next, handle the denominator (the distance squared):

$$
(2r)^2 = 4r^2
$$

Now, plug these back into the $F_2$ equation:

$$
F_2 = G \frac{\frac{1}{4} m_1 m_2}{4r^2}
$$

### Step 5: Extract the change factor
Move the numerical constants to the front to compare $F_2$ to $F_1$:

$$
F_2 = \left( \frac{\frac{1}{4}}{4} \right) \times G \frac{m_1 m_2}{r^2}
$$

Since $\frac{1}{4} \div 4 = \frac{1}{4} \times \frac{1}{4} = \frac{1}{16}$, we get:

$$
F_2 = \frac{1}{16} \times F_1
$$

---

## 4. Final Conclusion

By doubling the distance and halving both masses, the gravitational force becomes much weaker. Specifically:

**The force $F$ decreases by a factor of 16 (or is multiplied by $\frac{1}{16}$).**
