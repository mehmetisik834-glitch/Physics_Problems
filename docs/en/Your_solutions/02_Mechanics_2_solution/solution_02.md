# Simple Harmonic Motion: Spring-Mass System Analysis

This document provides a breakdown of how to extract physical constants and energy values from a displacement-time equation.

## 1. Key Definitions & Formulas

### Simple Harmonic Motion (SHM)
SHM is a type of periodic motion where the restoring force is directly proportional to the displacement. The general equation for displacement $x(t)$ is:

$$
x(t) = A \cos(\omega t + \phi)
$$

Where:
* **$A$:** Amplitude (maximum displacement from equilibrium).
* **$\omega$:** Angular frequency (measured in rad/s).
* **$\phi$:** Phase constant.

### The Spring Constant ($k$)
The angular frequency $\omega$ is determined by the mass ($m$) and the spring constant ($k$):

$$
\omega = \sqrt{\frac{k}{m}} \implies k = m\omega^2
$$

### Total Mechanical Energy ($E_{total}$)
In an ideal system (no friction), the total energy is the sum of kinetic and potential energy. At maximum displacement (amplitude), all energy is potential:

$$
E = \frac{1}{2} k A^2
$$

---

## 2. Problem Solving

**Given:**
* Mass $m = 10 \text{ kg}$
* Equation: $x(t) = 0.2 \cos(10\pi t)$

### Step 1: Identify Parameters from the Equation
By comparing the given equation $x(t) = 0.2 \cos(10\pi t)$ to the standard form $x(t) = A \cos(\omega t)$, we find:
* **Amplitude ($A$):** $0.2 \text{ m}$
* **Angular Frequency ($\omega$):** $10\pi \text{ rad/s}$

### Step 2: Calculate the Spring Constant ($k$)
Using the relationship between angular frequency, mass, and the spring constant:

$$
k = m \omega^2
$$

Substitute the known values:

$$
k = 10 \cdot (10\pi)^2
$$

$$
k = 10 \cdot 100\pi^2 = 1000\pi^2
$$

Using $\pi^2 \approx 9.87$:

$$
k \approx 1000 \cdot 9.8696 = 9869.6 \text{ N/m}
$$

**Result:** The spring constant $k$ is $1000\pi^2 \text{ N/m}$ (approx. **$9870 \text{ N/m}$**).

---

### Step 3: Calculate the Total Mechanical Energy ($E$)
Using the energy formula for the maximum displacement point:

$$
E = \frac{1}{2} k A^2
$$

Substitute $k = 1000\pi^2$ and $A = 0.2$:

$$
E = \frac{1}{2} (1000\pi^2) (0.2)^2
$$

$$
E = 500\pi^2 \cdot 0.04
$$

$$
E = 20\pi^2
$$

Using $\pi^2 \approx 9.87$:

$$
E \approx 20 \cdot 9.8696 = 197.39 \text{ Joules}
$$

**Result:** The total mechanical energy of the system is $20\pi^2 \text{ J}$ (approx. **$197.4 \text{ J}$**).

---

## 3. Summary Table

| Parameter | Value | Unit |
| :--- | :--- | :--- |
| Amplitude ($A$) | $0.2$ | $\text{m}$ |
| Angular Frequency ($\omega$) | $10\pi$ | $\text{rad/s}$ |
| Spring Constant ($k$) | $9869.6$ | $\text{N/m}$ |
| Total Energy ($E$) | $197.4$ | $\text{J}$ |
