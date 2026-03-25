## 3. Path Intersection and Proximity Analysis

### Problem Statement
Alice: $A(t) = (2+t, 8-3t)$  
Bob: $B(t) = (2t-1, 2t+2)$

### 1. Collision Check
To check for a collision, we set $A(t) = B(t)$:

$$
2 + t = 2t - 1 \implies t = 3
$$

Testing $t=3$ in the y-coordinates:
- $y_A(3) = 8 - 3(3) = -1$
- $y_B(3) = 2(3) + 2 = 8$

**Conclusion:** No collision occurs because $y_A(3) \neq y_B(3)$.

### 2. Minimum Distance Calculation
The separation vector is $\vec{D}(t) = B(t) - A(t) = (t-3, 5t-6)$. The squared distance is:

$$
S(t) = (t-3)^2 + (5t-6)^2 = 26t^2 - 66t + 45
$$

Finding the minimum via differentiation:

$$
\frac{dS}{dt} = 52t - 66 = 0 \implies t = \frac{33}{26} \approx 1.27
$$

### 3. Results
- **Time of closest approach:** $t \approx 1.27$
- **Minimum Distance:** $$
d_{min} = \sqrt{S(1.27)} \approx 1.76 \text{ units}
$$
