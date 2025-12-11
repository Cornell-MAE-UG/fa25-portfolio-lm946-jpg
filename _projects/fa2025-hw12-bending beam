e---
layout: project
title: Actuator Project 
image: /assets/images/spaceship-design.jpg
link: https://drive.google.com/drive/u/1/my-drive
---
## STEP 1: RIGID BEAM ANALYSIS

**TASK**  
Determine the optimal geometric configuration of a rigid beam–actuator mechanism that maximizes both the lifted height and the maximum supported weight using the performance metric \(W \cdot h\).

**ASSUMPTIONS**  
- Beam is perfectly rigid (no bending)  
- Joints are ideal and frictionless  
- Actuator applies its maximum rated force \(F_\text{max}\)  
- All loads act perpendicular to the beam  
- Gravity acts vertically downward  
- Full trigonometric height–angle relations are used (no simplifications)

**ALL SPECIFICATIONS (DESIGN SPACE CONSTRAINTS)**  
- Beam length: \(L\)  
- Actuator attachment distance from pivot: \(d\)  
- Load applied at tip: \(W\)  
- Beam angle relative to horizontal: \(\theta\)  
- Actuator force angle relative to beam: \(\beta\)

**WHAT I DID**  
- Modeled the beam as a rigid bar pinned at a pivot, with the actuator force applied at distance \(d\)  
- Used static equilibrium to compute maximum liftable weight:  
  \[
  W_\text{max} = \frac{L \sin \theta F_\text{max} \cdot d \cdot \sin \beta}{}
  \]  
- Performed a sweep over beam angle \(\theta\)  
- Computed lifted height \(h(\theta)\) and evaluated the performance metric:  
  \[
  \text{Score} = W \cdot h
  \]  
- Implemented the entire design-space search in Python to locate the optimal orientation and actuator position

**RESULTS**  
- Identified the beam angle \(\theta\) and actuator placement \(d\) that maximize the metric \(W \cdot h\)  
- Obtained the best tradeoff between maximum load and maximum achievable height under rigid-beam assumptions

---

## STEP 2: FLEXIBLE BEAM ANALYSIS & DESIGN

**TASK**  
Relax the rigid-beam assumption and design a beam that limits deflection while remaining lightweight and structurally efficient.

**WHAT I DID**  
- Modeled the beam as a cantilever: fixed at the pivot, free at the tip  
- Considered two transverse loads:  
  - Downward tip weight: \(W\)  
  - Upward actuator force applied at distance \(d\): \(F\)  
- Applied Euler–Bernoulli beam theory:  
  \[
  w''(x) = \frac{M(x)}{EI}
  \]  
- Integrated bending moment and applied boundary conditions:  
  \[
  w(0) = 0, \quad w'(0) = 0
  \]  
- Derived maximum tip deflection:  
  \[
  \delta_\text{max} = \delta_W - \delta_F = \frac{3 E I W L^3 - 6 E I F (L-d)^2 (2L + d)}{}
  \]  
- Set allowable deflection (either a % of \(L\) or micron-level)  
- Solved for required flexural rigidity:  
  \[
  EI = \frac{\delta_\text{max}}{3WL^3 - 6F(L-d)^2(2L+d)}
  \]  
- Chose carbon fiber as the material (\(E \approx 400 \text{GPa}\))  
- Computed required moment of inertia \(I\)  
- Designed a hollow rectangular box cross-section and tuned wall thickness and outer dimensions to meet the required \(I\) with minimal mass

**RESULTS (CROSS-SECTION DESIGN)**  
- **Material:** Carbon fiber (\(E \approx 400 \text{ GPa}\))  
- **Geometry:** Hollow rectangular box beam for maximum stiffness-to-weight efficiency  
- **Cross-section dimensions:** Selected to provide the computed moment of inertia \(I\)  
- **Final design ensures:**  
  - Tip deflection stays below the allowable limit  
  - Beam remains lightweight  
  - Structural efficiency is maximized
- **The solution is linked below:**  
  **https://drive.google.com/file/d/1ivtSAr0In0znb_PCnoBRG0q-1dDljl1w/view?usp=drive_link**

---








