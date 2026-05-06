# 9. Vector Lorentz Force

## Given

Velocity vector:

\[
\vec{v} = (2\hat{i} - 4\hat{j} + \hat{k}) \ \text{m/s}
\]

Magnetic field vector:

\[
\vec{B} = (\hat{i} + 2\hat{j} - \hat{k}) \ \text{T}
\]

Particle: Proton

Charge of proton:

\[
q = 1.6 \times 10^{-19} \ \text{C}
\]

---

# Main Formula

\[
\vec{F}=q(\vec{v}\times\vec{B})
\]

Where:

- \(\vec{F}\) = magnetic force vector  
- \(q\) = electric charge of the particle  
- \(\vec{v}\) = velocity vector  
- \(\vec{B}\) = magnetic field vector  
- \(\times\) = cross product operation  

---

# Step 1 — Compute the Cross Product

\[
\vec{v} \times \vec{B}
=
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
2 & -4 & 1 \\
1 & 2 & -1
\end{vmatrix}
\]

Expanding the determinant:

\[
=
\hat{i}[(-4)(-1) - (1)(2)]
-
\hat{j}[(2)(-1) - (1)(1)]
+
\hat{k}[(2)(2) - (-4)(1)]
\]

---

# Step 2 — Simplify Components

## \( \hat{i} \)-component

\[
(-4)(-1) - (1)(2)
=
4 - 2
=
2
\]

## \( \hat{j} \)-component

\[
(2)(-1) - (1)(1)
=
-2 - 1
=
-3
\]

Because of the minus sign before \(\hat{j}\):

\[
-(-3) = 3
\]

## \( \hat{k} \)-component

\[
(2)(2) - (-4)(1)
=
4 + 4
=
8
\]

So:

\[
\vec{v} \times \vec{B}
=
2\hat{i} + 3\hat{j} + 8\hat{k}
\]

---

# Step 3 — Find the Magnitude

Magnitude formula:

\[
|\vec{A}|= \sqrt{A_x^2+A_y^2+A_z^2}
\]

Apply it:

\[
|\vec{v} \times \vec{B}|
=
\sqrt{2^2 + 3^2 + 8^2}
\]

\[
=
\sqrt{4 + 9 + 64}
\]

\[
=
\sqrt{77}
\]

\[
\approx 8.775
\]

---

# Step 4 — Calculate the Magnetic Force

\[
|\vec{F}|
=
q |\vec{v} \times \vec{B}|
\]

Substitute values:

\[
=
(1.6 \times 10^{-19})(8.775)
\]

\[
\approx 1.40 \times 10^{-18} \ \text{N}
\]

---

# Final Answer

\[
\boxed{
|\vec{F}| \approx 1.4 \times 10^{-18} \ \text{N}
}
\]
