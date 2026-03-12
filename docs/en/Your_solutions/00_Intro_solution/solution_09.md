# Optimization: Maximizing Area Under a Curve

## 1. Definitions and Formulas

### Optimization
In calculus, **optimization** is the process of finding the maximum or minimum value of a function. This occurs where the slope of the function (the derivative) is zero.

### Area of a Rectangle
The area ($A$) of a rectangle is the product of its width and its height.

$$
A = \text{width} \times \text{height}
$$



### The Geometry of the Problem
* We are restricted to the **first quadrant**, meaning $x \ge 0$ and $y \ge 0$.
* The curve is a downward-opening parabola: $y = 3 - x^2$.
* The base of the rectangle lies on the x-axis, and one corner touches the curve at a point $(x, y)$.
* Therefore, the **width** of the rectangle is $x$ and the **height** is $y$.

---

## 2. Problem Statement

Find the dimensions ($x$ and $y$) that maximize the area of a rectangle bounded by $y = 3 - x^2$ in the first quadrant.

---

## 3. Step-by-Step Solution

### Step 1: Write the Area Function
The area $A$ is given by $x \cdot y$. Since $y = 3 - x^2$, we can write the area as a function of $x$ only:

$$
A(x) = x(3 - x^2)
$$

$$
A(x) = 3x - x^3
$$

### Step 2: Find the Derivative $A'(x)$
To find the maximum, we need the derivative of the area function with respect to $x$:

$$
A'(x) = \frac{d}{dx}(3x - x^3)
$$

$$
A'(x) = 3 - 3x^2
$$

### Step 3: Solve for Critical Points
Set the derivative to zero:

$$
3 - 3x^2 = 0
$$

$$
3x^2 = 3
$$

$$
x^2 = 1
$$

$$
x = 1
$$

*(Note: We ignore $x = -1$ because the problem is restricted to the first quadrant where $x > 0$.)*

### Step 4: Verify the Maximum (Second Derivative Test)
To ensure $x = 1$ gives a maximum area, we check the second derivative:

$$
A''(x) = -6x
$$

At $x = 1$:

$$
A''(1) = -6(1) = -6
$$

Since $A''(1) < 0$, the function is concave down, confirming that $x = 1$ is a **local maximum**.

### Step 5: Find the corresponding height ($y$)
Substitute $x = 1$ back into the original curve equation:

$$
y = 3 - (1)^2
$$

$$
y = 3 - 1 = 2
$$

---

## 4. Final Dimensions

The dimensions that maximize the area of the rectangle are:

* **Width ($x$):** 1
* **Height ($y$):** 2

The maximum area is $1 \times 2 = 2$ square units.

---

## Summary Table

| Variable | Optimal Value |
| :--- | :--- |
| $x$ (Width) | 1 |
| $y$ (Height) | 2 |
| **Max Area** | **2** |
