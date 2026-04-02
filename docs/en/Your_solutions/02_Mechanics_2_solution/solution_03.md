# 3. Conservation of Energy

## Necessary definitions and formulas

### 1) Mechanical energy
For a pendulum, the total mechanical energy is the sum of:

- **Potential energy**
- **Kinetic energy**

If we ignore air resistance and friction, mechanical energy is conserved.

### 2) Gravitational potential energy

$$
U = mgh
$$

where:
- \(m\) = mass of the bob,
- \(g\) = gravitational acceleration,
- \(h\) = vertical height above the lowest point.

### 3) Kinetic energy

$$
K = \frac{1}{2}mv^2
$$

where:
- \(m\) = mass,
- \(v\) = speed.

### 4) Conservation of mechanical energy
At the release point, the pendulum has mostly potential energy.
At the bottom, that potential energy becomes kinetic energy.

So we use:

$$
mgh = \frac{1}{2}mv^2
$$

The mass cancels out:

$$
gh = \frac{1}{2}v^2
$$

which gives:

$$
v = \sqrt{2gh}
$$

### 5) Height of a pendulum released from angle \(\theta\)
If the pendulum length is \(L\), then the vertical height above the lowest point is:

$$
h = L(1 - \cos\theta)
$$

This is the key geometry formula for pendulum energy problems.

---

## Given

- Length of pendulum:

$$
L = 1.0 \text{ m}
$$

- Initial angle:

$$
\theta = 15^\circ
$$

- Gravitational acceleration:

$$
g = 9.8 \text{ m/s}^2
$$

We want the speed of the bob at the bottom.

---

## Step 1: Find the vertical height \(h\)

Use:

$$
h = L(1 - \cos\theta)
$$

Substitute the values:

$$
h = 1.0(1 - \cos 15^\circ)
$$

Now use:

$$
\cos 15^\circ \approx 0.9659
$$

So:

$$
h = 1.0(1 - 0.9659)
$$

$$
h = 0.0341 \text{ m}
$$

So the bob starts about \(0.0341\) m above the lowest point.

---

## Step 2: Apply conservation of energy

At the top:

$$
U = mgh
$$

At the bottom:

$$
K = \frac{1}{2}mv^2
$$

Set them equal:

$$
mgh = \frac{1}{2}mv^2
$$

Cancel \(m\):

$$
gh = \frac{1}{2}v^2
$$

Solve for \(v\):

$$
v = \sqrt{2gh}
$$

---

## Step 3: Substitute the values

$$
v = \sqrt{2(9.8)(0.0341)}
$$

First calculate inside the square root:

$$
2(9.8)(0.0341) = 0.66836
$$

So:

$$
v = \sqrt{0.66836}
$$

$$
v \approx 0.8175 \text{ m/s}
$$

---

## Final answer

$$
v \approx 0.82 \text{ m/s}
$$

So the speed of the pendulum bob at the bottom of its swing is:

$$
\boxed{0.82 \text{ m/s}}
$$

---

## Short explanation
The bob starts with gravitational potential energy because it is raised above the lowest point. As it swings downward, that energy changes into kinetic energy. At the bottom, the speed is maximum.

---
