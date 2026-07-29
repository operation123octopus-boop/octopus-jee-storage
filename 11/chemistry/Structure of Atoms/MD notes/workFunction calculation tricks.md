# Calculation shortcuts for Work Function $W_0$

Here is a comprehensive cheatsheet of shortcuts specifically tailored for **Photoelectric Effect & Work Function ($\phi$)** calculations.

---

## Photoelectric Effect & Work Function Cheat Sheet

### 1. Core Equation (in $\text{eV}$)

Note: $\phi$ = $W_0$

$$\phi = E - KE_{\text{max}}$$


or in terms of stopping potential ($V_0$):


$$\phi = E - e V_0$$

---

#### 2. Photon Energy ($E$) & Threshold Wavelength ($\lambda_0$) Shortcuts

* **Wavelength in Angstroms ($\text{\AA}$):**

$$E (\text{in eV}) = \frac{12400}{\lambda (\text{in \AA})}$$


* **Wavelength in Nanometers ($\text{nm}$):**

$$E (\text{in eV}) = \frac{1240}{\lambda (\text{in nm})}$$


* **Threshold Wavelength ($\lambda_0$) directly from Work Function ($\phi$ in $\text{eV}$):**

$$\lambda_0 (\text{in \AA}) = \frac{12400}{\phi (\text{in eV})}$$



---

### 3. Kinetic Energy ($KE_{\text{max}}$) & Velocity ($v$) Shortcuts

Instead of doing $\frac{1}{2} m v^2 = \frac{1}{2} (9 \times 10^{-31}) v^2$:

* **$KE$ in $\text{eV}$ from Velocity ($v$ in $\text{m/s}$):**

$$KE (\text{in eV}) \approx 2.81 \times 10^{-12} \times v^2$$



*(For quick estimates, use $KE (\text{in eV}) \approx 2.8 \times 10^{-12} v^2$)*
* **Velocity ($v$) directly from $KE_{\text{max}}$ in $\text{eV}$:**

$$v \approx 5.93 \times 10^5 \sqrt{KE_{\text{in eV}}} \quad \text{m/s}$$


* **Stopping Potential ($V_0$) directly from $KE_{\text{max}}$:**

$$\text{If } KE_{\text{max}} = X \text{ eV} \implies V_0 = X \text{ Volts}$$



---

### 4. De Broglie Wavelength of Photoelectrons

* **$\lambda_{\text{db}}$ from $KE_{\text{max}}$ (in $\text{eV}$):**

$$\lambda_{\text{db}} = \sqrt{\frac{150}{KE_{\text{in eV}}}} \text{ \AA} = \frac{12.27}{\sqrt{KE_{\text{in eV}}}} \text{ \AA}$$


* **$\lambda_{\text{db}}$ from Stopping Potential ($V_0$ in Volts):**

$$\lambda_{\text{db}} = \frac{12.27}{\sqrt{V_0}} \text{ \AA}$$



---

### 5. Work Functions of Common Elements (Quick Reference)

| Metal | Work Function ($\phi$ in $\text{eV}$) |
| --- | --- |
| **Cesium ($\text{Cs}$)** | $\approx 2.14 \text{ eV}$ *(Lowest work function, highly sensitive to visible light)* |
| **Potassium ($\text{K}$)** | $\approx 2.30 \text{ eV}$ |
| **Sodium ($\text{Na}$)** | $\approx 2.75 \text{ eV}$ |
| **Copper ($\text{Cu}$)** | $\approx 4.65 \text{ eV}$ |
| **Platinum ($\text{Pt}$)** | $\approx 5.65 \text{ eV}$ *(Highest work function)* |

---

### 6. Quick Calculation Strategy Checklist

1. **Convert $\lambda \to E$ immediately** using $\frac{12400}{\lambda_{\text{\AA}}}$.
2. **Convert $v \to KE$** using $v = 6 \times 10^5 \text{ m/s} \implies KE \approx 1 \text{ eV}$ (since $(6 \times 10^5)^2 \times 2.81 \times 10^{-12} \approx 1.01 \text{ eV}$).
3. **Subtract in $\text{eV}$ directly:** $\phi = E - KE$.