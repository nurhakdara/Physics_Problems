# Exercise 11: Dynamics with a Time-Dependent Force

## Given

Mass:
m = 3 kg

Force:
F(t) = (15t, 3t − 12, −6t²) N

Initial conditions:
r(0) = (5, 2, −3) m
v(0) = (2, 0, 1) m/s

---

# Step 1: Use Newton’s Second Law

F = ma

So:

a(t) = F(t) / m

---

## Compute acceleration

a(t) = (15t/3, (3t − 12)/3, −6t²/3)

a(t) = (5t, t − 4, −2t²)

---

# Step 2: Find Velocity

Velocity is integral of acceleration:

v(t) = ∫ a(t) dt

---

## Integrate each component

vₓ(t) = ∫ 5t dt = (5/2)t² + C₁

v_y(t) = ∫ (t − 4) dt = (1/2)t² − 4t + C₂

v_z(t) = ∫ (−2t²) dt = −(2/3)t³ + C₃

---

## Apply initial condition v(0) = (2, 0, 1)

At t = 0:

C₁ = 2
C₂ = 0
C₃ = 1

---

## Final velocity

v(t) = ( (5/2)t² + 2 , (1/2)t² − 4t , −(2/3)t³ + 1 )

---

# Step 3: Find Position

Position is integral of velocity:

r(t) = ∫ v(t) dt

---

## Integrate each component

x(t) = ∫[(5/2)t² + 2] dt
= (5/6)t³ + 2t + C₄

y(t) = ∫[(1/2)t² − 4t] dt
= (1/6)t³ − 2t² + C₅

z(t) = ∫[−(2/3)t³ + 1] dt
= −(1/6)t⁴ + t + C₆

---

## Apply initial condition r(0) = (5, 2, −3)

At t = 0:

C₄ = 5
C₅ = 2
C₆ = −3

---

## Final position

r(t) = ( (5/6)t³ + 2t + 5 , (1/6)t³ − 2t² + 2 , −(1/6)t⁴ + t − 3 )

---

# Final Answers

## Velocity

v(t) =
( (5/2)t² + 2 , (1/2)t² − 4t , −(2/3)t³ + 1 )

---

## Position

r(t) =
( (5/6)t³ + 2t + 5 , (1/6)t³ − 2t² + 2 , −(1/6)t⁴ + t − 3 )

---

# Key Concepts

* a(t) = F(t) / m
* v(t) = ∫ a(t) dt
* r(t) = ∫ v(t) dt
* Always apply initial conditions to find constants

---

# Important Insight

Time-dependent forces →
motion is found by **integration (not constant acceleration formulas)**

---
