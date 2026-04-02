# Physics Analysis: Vertical Throw with Linear Air Resistance

This study examines the trajectory of an object thrown upward when subject to both gravity and a velocity-dependent drag force.

## 1. Key Definitions & Formulas

### Linear Drag Force ($F_d$)
For small objects moving at relatively low speeds, drag is often modeled as being proportional to velocity:

$$
F_d = -kv
$$

Where $k$ is the drag coefficient. The negative sign indicates the force always opposes motion.

### Equation of Motion (Newton's Second Law)
Summing the forces (Gravity and Drag) acting on the mass $m$:

$$
m \frac{dv}{dt} = -mg - kv
$$

### Terminal Velocity ($v_t$)
The velocity at which the drag force equals the gravitational force (magnitude-wise), causing acceleration to become zero:

$$
v_t = \frac{mg}{k}
$$

---

## 2. Analytical Solution

### Step 1: Solving for Velocity $v(t)$
We start with the differential equation:

$$
\frac{dv}{dt} = -g - \frac{k}{m}v
$$

This is a first-order linear differential equation. We can solve it using separation of variables:

$$
\frac{dv}{g + \frac{k}{m}v} = -dt
$$

Integrating both sides from $v_0$ to $v(t)$ and $0$ to $t$:

$$
\frac{m}{k} \ln\left( \frac{g + \frac{k}{m}v}{g + \frac{k}{m}v_0} \right) = -t
$$

Solving for $v(t)$:

$$
v(t) = \left( v_0 + \frac{mg}{k} \right) e^{-\frac{k}{m}t} - \frac{mg}{k}
$$



### Step 2: Solving for Position $x(t)$
Integrate $v(t)$ with respect to time, using the initial condition $x(0) = 10$:

$$
x(t) = 10 + \int_{0}^{t} \left[ \left( v_0 + \frac{mg}{k} \right) e^{-\frac{k}{m}t'} - \frac{mg}{k} \right] dt'
$$

$$
x(t) = 10 + \frac{m}{k}\left( v_0 + \frac{mg}{k} \right) \left( 1 - e^{-\frac{k}{m}t} \right) - \frac{mg}{k}t
$$

---

## 3. Determining Maximum Height ($H_{max}$)

The object reaches maximum height when $v(t_{peak}) = 0$. 

**1. Find the time to reach peak ($t_p$):**

$$
0 = \left( v_0 + \frac{mg}{k} \right) e^{-\frac{k}{m}t_p} - \frac{mg}{k}
$$

$$
t_p = \frac{m}{k} \ln\left( 1 + \frac{kv_0}{mg} \right)
$$

**2. Substitute $t_p$ into $x(t)$:**
After algebraic simplification, the maximum height is:

$$
H_{max} = 10 + \frac{m v_0}{k} - \frac{m^2 g}{k^2} \ln\left( 1 + \frac{k v_0}{m g} \right)
$$

---

## 4. Comparison: Drag vs. No Drag

| Feature | Without Drag ($k=0$) | With Linear Drag ($k > 0$) |
| :--- | :--- | :--- |
| **Velocity** | $v(t) = v_0 - gt$ | Decays exponentially toward terminal velocity |
| **Max Height** | $10 + \frac{v_0^2}{2g}$ | Always lower than the vacuum case |
| **Symmetry** | Rise time equals fall time | Rise time is shorter than fall time |
| **Acceleration** | Constant ($-g$) | Decreases as the object falls |



---

## 5. Numerical Simulation (Python)

You can use the following script to visualize the effect of different drag coefficients.

```python
import numpy as np
import matplotlib.pyplot as plt

# Constants
m = 1.0      # mass (kg)
g = 9.81     # gravity (m/s^2)
v0 = 20.0    # initial velocity (m/s)
x0 = 10.0    # initial height (m)
k = 0.5      # drag coefficient
dt = 0.01    # time step
t_max = 4.0  # total simulation time

# Arrays for simulation
t_vals = np.arange(0, t_max, dt)
v = v0
x = x0
x_history = []

for t in t_vals:
    x_history.append(x)
    # Euler Method for integration
    dv = (-g - (k/m)*v) * dt
    v += dv
    x += v * dt
    if x < 0: break # stop at ground

plt.plot(t_vals[:len(x_history)], x_history, label=f'k={k}')
plt.xlabel('Time (s)')
plt.ylabel('Height (m)')
plt.title('Vertical Throw with Drag')
plt.grid(True)
plt.legend()
plt.show()
