# Infinite Series: The Ant's Final Position

## 1. Definitions and Formulas

### Vector Displacement
The position of the ant can be represented as a coordinate $(x, y)$ in a 2D plane. 
* **East/West** movements affect the **$x$-coordinate** (East is positive, West is negative).
* **North/South** movements affect the **$y$-coordinate** (North is positive, South is negative).

### The Alternating Harmonic Series
The problem utilizes the alternating harmonic series, which is defined as:

$$
\sum_{n=1}^{\infty} \frac{(-1)^{n-1}}{n} = 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots
$$

The sum of this specific infinite series is known to converge to the natural logarithm of 2:

$$
\ln(2) \approx 0.693
$$



---

## 2. Problem Statement

An ant moves in a repeating directional pattern (East, North, West, South) with decreasing step sizes:
* Step 1: $1$ m East
* Step 2: $1/2$ m North
* Step 3: $1/3$ m West
* Step 4: $1/4$ m South
* Step 5: $1/5$ m East ... and so on.

**Goal:** Determine the final $(x, y)$ position of the ant.

---

## 3. Step-by-Step Solution

### Step 1: Analyze the Horizontal Motion ($x$)
The ant moves East on steps 1, 5, 9... and West on steps 3, 7, 11...
The $x$-coordinate is the sum of the odd-numbered steps with alternating signs:

$$
x = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
$$

This is the **Gregory-Leibniz series**. It is a famous series that converges to:

$$
x = \frac{\pi}{4} \approx 0.785
$$

### Step 2: Analyze the Vertical Motion ($y$)
The ant moves North on steps 2, 6, 10... and South on steps 4, 8, 12...
The $y$-coordinate is the sum of the even-numbered steps with alternating signs:

$$
y = \frac{1}{2} - \frac{1}{4} + \frac{1}{6} - \frac{1}{8} + \dots
$$

We can factor out $1/2$ from this series:

$$
y = \frac{1}{2} \left( 1 - \frac{1}{2} + \frac{1}{3} - \frac{1}{4} + \dots \right)
$$

The term inside the parentheses is the **Alternating Harmonic Series**, which equals $\ln(2)$. Therefore:

$$
y = \frac{1}{2} \ln(2) \approx 0.346
$$

---

## 4. Final Position

The final position of the ant as it continues this pattern to infinity is:

$$
(x, y) = \left( \frac{\pi}{4}, \frac{\ln(2)}{2} \right)
$$

### Numerical Approximation
Rounding to three decimal places, the ant ends up at:
* **$x \approx 0.785$ m**
* **$y \approx 0.347$ m**
