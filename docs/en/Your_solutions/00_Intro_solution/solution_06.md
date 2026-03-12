# Function Analysis: Finding Local Extrema

## 1. Definitions and Formulas

### Local Maxima and Minima
A **local maximum** is a point where the function reaches its highest value in a specific neighborhood. A **local minimum** is where it reaches its lowest value. For a quadratic function (a parabola), there is only one global vertex which acts as the local extremum.



### Critical Points
A critical point occurs where the first derivative of the function is equal to zero or undefined. This is where the slope of the tangent line is horizontal.

$$
f'(x) = 0
$$

### The Power Rule
To find the derivative of a polynomial term:

$$
\frac{d}{dx}[ax^n] = nax^{n-1}
$$



### Second Derivative Test
This test helps us classify the critical point:
* If **$f''(x) > 0$**, the function is concave up (like a cup), and the point is a **local minimum**.
* If **$f''(x) < 0$**, the function is concave down (like a frown), and the point is a **local maximum**.

---

## 2. Problem Statement

Analyze the function:

$$
f(x) = 3x^2 - 12x + 7
$$

**Goal:** Identify any local maxima or minima.

---

## 3. Step-by-Step Solution

### Step 1: Find the First Derivative $f'(x)$
Apply the power rule to each term of the function:

$$
f'(x) = \frac{d}{dx}(3x^2) - \frac{d}{dx}(12x) + \frac{d}{dx}(7)
$$

$$
f'(x) = 6x - 12
$$

### Step 2: Find the Critical Point(s)
Set the derivative to zero and solve for $x$:

$$
6x - 12 = 0
$$

$$
6x = 12
$$

$$
x = 2
$$

### Step 3: Classify the Point (Second Derivative Test)
Now, find the second derivative $f''(x)$ to see if the graph is "smiling" or "frowning":

$$
f''(x) = \frac{d}{dx}(6x - 12)
$$

$$
f''(x) = 6
$$

Since **$6 > 0$**, the function is concave up. This means our critical point at $x = 2$ is a **local minimum**.

### Step 4: Find the $y$-coordinate
Plug $x = 2$ back into the original function $f(x)$ to find the exact point:

$$
f(2) = 3(2)^2 - 12(2) + 7
$$

$$
f(2) = 3(4) - 24 + 7
$$

$$
f(2) = 12 - 24 + 7 = -5
$$

---

## 4. Final Answer

The function $f(x) = 3x^2 - 12x + 7$ has:

* **No local maxima.**
* **A local minimum at the point $(2, -5)$.**
