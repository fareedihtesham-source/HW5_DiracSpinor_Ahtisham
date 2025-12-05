# HW5_DiracSpinor_AhtishamandSaad
Homework 05 – Dirac Spinor Solution
# Homework 05 – Dirac Spinor Analysis  
**Course:** Introduction to Nuclear and Particle Physics  
**Student:** Muhammad Ahtisham Nazakat and Muhammad Saad Aslam Qazi

---

## 1. Personalized Dirac Spinor  
Using  
\[
\phi_k = x_k e^{i y_k},
\]
the alphabet positions give:

**First name:** Muhammad Ahtisham → M(13), u(21), h(8), a(1)  
**Last name:** Nazakat → N(14), a(1), z(26), a(1)

So:

\[
\phi=
\begin{pmatrix}
13e^{i14}\\
21e^{i1}\\
8e^{i26}\\
1e^{i1}
\end{pmatrix}.
\]

Numerically:

\[
\phi \approx
(1.7776+12.8779i,\;
11.3463+17.6709i,\;
5.1754+6.1005i,\;
0.5403+0.8415i)^T
\]

---

## 2. Cause of Invalidity  
A free u–spinor must satisfy the dispersion relation:

\[
E^2 - \vec{p}^{\,2} = m^2.
\]

For the original spinor:

- \(E = 337.5\)
- \(m = 272.5\)
- \(\vec p \approx (178.32,\; 16.77,\; 66.76)\)

So:

\[
E^2 - p^2 \neq m^2.
\]

**Therefore the given spinor is invalid.**

---

## 3. Modified Valid Spinor  
Only two components may be changed.

Choose rest-frame u–spinor:

\[
\phi' =
\begin{pmatrix}
\phi_1\\
\phi_2\\
0\\
0
\end{pmatrix}.
\]

This satisfies Eq. (4) for u–spinors.

---

## 4. Physical Parameters of Valid Spinor

### Mass
\[
2m = \phi'^\dagger \gamma^0 \phi' = 610
\Rightarrow m = 305.
\]

### Energy
\[
2E = \phi'^\dagger \phi' = 610
\Rightarrow E = 305.
\]

### Momentum
\[
p_x = p_y = p_z = 0.
\]

### Spin Vector
\[
\vec S_0 \approx (0.812,\,-0.376,\,-0.446).
\]

Particle is at rest with spin along +x and tilted in –y,–z.

---

## 5. Distance Between Original and Valid Spinor  
\[
d = \frac12(|\phi_3|^2 + |\phi_4|^2)
     = \frac12(64 + 1)
     = 32.5.
\]

**Distance:**  
\[
d = 32.5.
\]

---

## 6. Bonus (+2 points)  
Optional program included in `bonus_program.py`:
- Generates spinor from name  
- Produces closest valid spinor  
- Computes \(m, E, \vec p, \vec S_0, d\)

---
