# Exercise 10: Force Field and Power

## Given

Mass:
m = 0.5 kg

Position as functions of time:

x(t) = 5t² − t
y(t) = 2t³
z(t) = −3t + 2

---

# Step 1: Velocity

Velocity is the derivative of position:

v = (dx/dt, dy/dt, dz/dt)

---

## Compute components

dx/dt = 10t − 1
dy/dt = 6t²
dz/dt = −3

---

## Velocity vector

v(t) = (10t − 1, 6t², −3)

---

# Step 2: Acceleration

Acceleration is derivative of velocity:

a = dv/dt

---

## Compute components

d²x/dt² = 10
d²y/dt² = 12t
d²z/dt² = 0

---

## Acceleration vector

a(t) = (10, 12t, 0)

---

# Step 3: Momentum

Momentum:

p = mv

---

## Multiply by mass (m = 0.5)

p(t) = 0.5 × (10t − 1, 6t², −3)

---

## Result

p(t) = (5t − 0.5, 3t², −1.5)

---

# Step 4: Force

Using Newton’s Second Law:

F = ma

---

## Multiply acceleration by mass

F(t) = 0.5 × (10, 12t, 0)

---

## Result

F(t) = (5, 6t, 0)

---

# Step 5: Power

Power is:

P = F · v   (dot product)

---

## Compute dot product

F · v = (5)(10t − 1) + (6t)(6t²) + (0)(−3)

---

## Simplify

= 50t − 5 + 36t³

---

## Final Power

P(t) = 36t³ + 50t − 5

---

# Final Answers Summary

Velocity:
v(t) = (10t − 1, 6t², −3)

Acceleration:
a(t) = (10, 12t, 0)

Momentum:
p(t) = (5t − 0.5, 3t², −1.5)

Force:
F(t) = (5, 6t, 0)

Power:
P(t) = 36t³ + 50t − 5

---

# Key Concepts

* Velocity = first derivative of position
* Acceleration = second derivative
* Force = mass × acceleration
* Power = dot product of force and velocity

---

# Important Insight

Power depends on alignment:

* If F and v same direction → positive power
* If opposite → negative power

---
