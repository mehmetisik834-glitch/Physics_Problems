# Rearranging the Pendulum Formula

## 1. Definitions and Key Variables

Before we dive into the algebra, let's define the players in this equation. A simple pendulum consists of a mass (the "bob") swinging on a string of a certain length.



* **$T$ (Period):** The time it takes for the pendulum to complete one full back-and-forth swing. Usually measured in seconds ($s$).
* **$L$ (Length):** The distance from the pivot point to the center of the mass. Measured in meters ($m$).
* **$g$ (Acceleration due to gravity):** The constant acceleration exerted by a planet's gravity. On Earth, this is approximately $9.81 \text{ m/s}^2$.
* **$\pi$ (Pi):** A mathematical constant, approximately $3.14159$.

### The Original Formula

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

---

## 2. Step-by-Step Rearrangement

The goal is to get $g$ all by itself on one side of the equal sign. Think of this like peeling an onion—we start from the outside and work our way into the center where $g$ is "hiding."

### Step 1: Isolate the square root
First, we need to move the $2\pi$. Since it is multiplied by the square root, we divide both sides by $2\pi$.

$$
\frac{T}{2\pi} = \sqrt{\frac{L}{g}}
$$

### Step 2: Remove the square root
To "undo" a square root, we must square both sides of the equation.

$$
\left( \frac{T}{2\pi} \right)^2 = \frac{L}{g}
$$

When we apply the square to the fraction on the left, we get:

$$
\frac{T^2}{4\pi^2} = \frac{L}{g}
$$

### Step 3: Get $g$ out of the denominator
Currently, $g$ is on the bottom of a fraction. To fix this, we can multiply both sides by $g$.

$$
g \cdot \left( \frac{T^2}{4\pi^2} \right) = L
$$

### Step 4: Final isolation of $g$
Now, to leave $g$ alone, we multiply by the reciprocal of the fraction next to it (which is the same as multiplying by $4\pi^2$ and dividing by $T^2$).

$$
g = \frac{4\pi^2 L}{T^2}
$$

---

## 3. Final Formula for Gravity

After rearranging the terms, we have our result:

$$
g = \frac{4\pi^2 L}{T^2}
$$

> **Pro-Tip:** This formula is actually how scientists can measure the local gravity of a planet just by using a piece of string, a weight, and a stopwatch!
