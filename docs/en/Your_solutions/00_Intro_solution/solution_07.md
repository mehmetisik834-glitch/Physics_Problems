# Logic & Series: The Fly and the Bicycle Problem

## 1. Definitions and Formulas

### Constant Velocity
When an object moves at a constant speed, the relationship between distance, speed, and time is linear.



### The Formulas

$$
v = \frac{d}{t}
$$

$$
d = v \cdot t
$$

$$
t = \frac{d}{v}
$$

Where:
* **$d$**: Distance (meters)
* **$v$**: Velocity or speed (m/s)
* **$t$**: Time (seconds)

### The Logical Insight
In problems where an object (the fly) moves back and forth between two other points, the "infinite series" of its path can be bypassed if we know the **total time** the movement occurs. The fly stops flying only when the bicycle hits the wall.

---

## 2. Problem Statement

* **Initial Distance ($d_{initial}$):** 10 meters
* **Bicycle Speed ($v_b$):** 1 m/s
* **Fly Speed ($v_f$):** 2 m/s

**Goal:** Calculate the total distance the fly travels before the bicycle reaches the wall.

---

## 3. Step-by-Step Solution

### Step 1: Calculate the time the bicycle is in motion
We need to find out how long it takes for the bicycle to cover the 10 meters to the wall.

$$
t = \frac{d_{initial}}{v_b}
$$

$$
t = \frac{10 \text{ m}}{1 \text{ m/s}} = 10 \text{ seconds}
$$

The bicycle will hit the wall in exactly **10 seconds**.

### Step 2: Determine the fly's total flight time
Because the fly is constantly flying back and forth until the moment of impact, the fly's total time in the air is exactly the same as the bicycle's travel time.

$$
t_{fly} = 10 \text{ seconds}
$$

### Step 3: Calculate the fly's total distance
Since the fly moves at a constant speed of $2 \text{ m/s}$ during those 10 seconds, we use the distance formula:

$$
d_{fly} = v_f \cdot t_{fly}
$$

Substitute the values:

$$
d_{fly} = 2 \text{ m/s} \cdot 10 \text{ s}
$$

$$
d_{fly} = 20 \text{ meters}
$$

---

## 4. Why we don't need a Series
You *could* calculate the distance of the first leg (bicycle to wall), then the second leg (wall back to the moving bicycle), and so on. This would create a **geometric series**. However, since the fly's speed is constant and the total time is bounded by the bicycle's motion, the "Time-Speed" method used above is much faster and mathematically equivalent to the sum of that infinite series.

---

## Final Answer

The fly travels a total distance of **20 meters** before being crushed.
