# Definite Integrals: Area Under a Curve

## 1. Definitions and Formulas

### Definite Integral
The **definite integral** of a function $f(x)$ between two points $a$ and $b$ calculates the total area accumulated between the function's curve and the x-axis.



### Fundamental Theorem of Calculus
This theorem provides the link between differentiation and integration. To solve a definite integral, we find the antiderivative $F(x)$ and evaluate it at the boundaries:

$$
\int_{a}^{b} f(x) \, dx = F(b) - F(a)
$$

### Integration Rule for Sine
Since the derivative of $\cos(x)$ is $-\sin(x)$, the antiderivative (integral) of $\sin(x)$ is:

$$
\int \sin(x) \, dx = -\cos(x) + C
$$

---

## 2. Problem Statement

Find the area under the curve of the function:

$$
f(x) = \sin(x)
$$

Over the interval:
* **Lower limit ($a$):** $0$
* **Upper limit ($b$):** $\pi$

---

## 3. Step-by-Step Solution

### Step 1: Set up the integral
We express the area as the definite integral of $\sin(x)$ from $0$ to $\pi$:

$$
\text{Area} = \int_{0}^{\pi} \sin(x) \, dx
$$

### Step 2: Find the antiderivative
We apply the integration rule. We use the notation $[ \dots ]_a^b$ to indicate that the limits still need to be applied:

$$
\text{Area} = [ -\cos(x) ]_{0}^{\pi}
$$

### Step 3: Apply the Fundamental Theorem of Calculus
Substitute the upper limit ($\pi$) into the antiderivative first, then subtract the value of the antiderivative at the lower limit ($0$):

$$
\text{Area} = (-\cos(\pi)) - (-\cos(0))
$$

### Step 4: Evaluate the trigonometric values
Using the unit circle, we know:
* $\cos(\pi) = -1$
* $\cos(0) = 1$

Substituting these values into our equation:

$$
\text{Area} = (-(-1)) - (-(1))
$$

### Step 5: Simplify the arithmetic
Carefully handle the double negatives:

$$
\text{Area} = 1 - (-1)
$$

$$
\text{Area} = 1 + 1 = 2
$$

---

## 4. Final Answer

The area under the curve of $f(x) = \sin(x)$ from $0$ to $\pi$ is exactly:

$$
\text{Area} = 2
$$
