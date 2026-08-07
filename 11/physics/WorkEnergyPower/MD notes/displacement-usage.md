Yes, whether you use vertical displacement or direct displacement depends entirely on **which force** you are calculating work for.

---

### 1. When to Use ONLY Vertical Displacement ($y$)

Use vertical displacement ($y$) when calculating work done by **gravity** (or gravitational potential energy, $\Delta U = mgy$).

* **Why:** Gravity acts exclusively in the vertical direction ($\vec{F}_g = -mg\hat{j}$). Any horizontal displacement vector component $\Delta x \hat{i}$ produces a dot product of zero ($\hat{j} \cdot \hat{i} = 0$).
* **Examples:**
* A block sliding down a curved track or incline.
* A pendulum bob swinging in an arc.
* A mass attached to a string pulling it through an irregular path (like in your $2\text{ kg}$ block problem).



> **Rule of Thumb:** If the force is purely vertical, only vertical displacement matters: $W_g = \pm mgy$.

---

### 2. When You MUST Use Actual Path/Total Displacement ($s$)

You **cannot** just use vertical displacement when dealing with forces that act along the path of motion or depend on other axes.

#### A. Friction and Air Resistance (Non-Conservative Forces)

Friction acts parallel to the contact surface at every point, opposing the direction of motion.

* **Calculation:** $W_{\text{friction}} = -\mu N \cdot s_{\text{total}}$
* You must use the **total path length (distance)** traveled along the surface, not just vertical or straight-line displacement.

#### B. Normal Force / Tension

* **Tension:** Always acts along the string. If the direction of motion changes relative to the string, you must calculate $\int \vec{T} \cdot d\vec{r}$.
* **Normal Force:** Acts perpendicular to the surface. On a stationary track, it does zero work because it is always at $90^\circ$ to the displacement at every instant.

#### C. Applied Horizontal or Angled Forces

* If a person pulls a box horizontally or at an angle $\theta$, the work done by that applied force depends on the horizontal displacement ($\Delta x$) or total displacement ($s$), **not** the vertical displacement.
* **Calculation:** $W_{\text{applied}} = F \cdot s \cdot \cos\theta$.

---

### Summary Checklist

| Force | Displacement to Use | Formula |
| --- | --- | --- |
| **Gravity** | Vertical Displacement ($y$) | $W = \pm mgy$ |
| **Friction** | Total Path Distance ($s_{\text{path}}$) | $W = -\mu N \cdot s_{\text{path}}$ |
| **Spring Force** | Compression/Elongation ($x$) | $W = -\frac{1}{2}k(x_f^2 - x_i^2)$ |
| **General Force ($\vec{F}$)** | Total Displacement ($\vec{s}$) | $W = \vec{F} \cdot \vec{s} = F s \cos\theta$ |