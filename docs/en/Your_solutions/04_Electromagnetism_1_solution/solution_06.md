<img width="937" height="339" alt="image" src="https://github.com/user-attachments/assets/492ad3eb-e550-4530-a737-db2db516c9c4" />



-----
-----
-----

Field at a Point from a System of Charges
Given

Two point charges are placed on the x-axis:

+q at point (-a, 0)
+2q at point (a, 0)

We use Coulomb’s Law for the electric field:

E
=
4πε
0
	​

1
	​

r
3
q
	​

r

Components and Their Meanings
Symbol	Meaning
\vec{E}	Electric field vector
q	Electric charge
2q	Charge with double magnitude
\varepsilon_0	Vacuum permittivity
\frac{1}{4\pi\varepsilon_0}	Coulomb constant k ≈ 9×10^9 N·m²/C²
\vec{r}	Vector from charge to observation point
r	Distance between charge and observation point
a	Distance of charges from origin
(x,y)	Observation point
E_x	x-component of electric field
E_y	y-component of electric field
Step 1 — Electric Field at General Point (x,y)

Observation point:

P(x,y)
Field Produced by Charge +q at (-a,0)

Position vector from charge to point:

r₁ = (x+a , y)

Magnitude:

r
1
	​

=
(x+a)
2
+y
2
	​


Electric field:

E
1
	​

=kq
[(x+a)
2
+y
2
]
3/2
(x+a)
i
^
+y
j
^
	​

	​


Field Produced by Charge +2q at (a,0)

Position vector:

r₂ = (x-a , y)

Magnitude:

r
2
	​

=
(x−a)
2
+y
2
	​


Electric field:

E
2
	​

=k(2q)
[(x−a)
2
+y
2
]
3/2
(x−a)
i
^
+y
j
^
	​

	​


Total Electric Field

Using superposition:

E = E₁ + E₂

So:

E
(x,y)=kq
[(x+a)
2
+y
2
]
3/2
(x+a)
i
^
+y
j
^
	​

	​

+2kq
[(x−a)
2
+y
2
]
3/2
(x−a)
i
^
+y
j
^
	​

	​


Components of the Electric Field
x-component

E
x
	​

=kq
[(x+a)
2
+y
2
]
3/2
x+a
	​

+2kq
[(x−a)
2
+y
2
]
3/2
x−a
	​


y-component

E
y
	​

=kq
[(x+a)
2
+y
2
]
3/2
y
	​

+2kq
[(x−a)
2
+y
2
]
3/2
y
	​


Step 2 — Field on the y-axis (0,y)

Set:

x = 0
x-component

E
x
	​

(0,y)=kqa[
(a
2
+y
2
)
3/2
1
	​

−
(a
2
+y
2
)
3/2
2
	​

]

Simplify:

E
x
	​

(0,y)=−
(a
2
+y
2
)
3/2
kqa
	​


y-component

E
y
	​

(0,y)=
(a
2
+y
2
)
3/2
3kqy
	​


Final Field on y-axis

E
(0,y)=−
(a
2
+y
2
)
3/2
kqa
	​

i
^
+
(a
2
+y
2
)
3/2
3kqy
	​

j
^
	​


Step 3 — Field on the x-axis (x,0)

Set:

y = 0

Then:

Ey = 0

and

E
x
	​

(x,0)=kq
∣x+a∣
3
x+a
	​

+2kq
∣x−a∣
3
x−a
	​


Therefore:

E
(x,0)=[kq
∣x+a∣
3
x+a
	​

+2kq
∣x−a∣
3
x−a
	​

]
i
^

Step 4 — Conditions for Zero Components
Condition for Ey = 0

From formula:

E
y
	​

=kq
[(x+a)
2
+y
2
]
3/2
y
	​

+2kq
[(x−a)
2
+y
2
]
3/2
y
	​


This becomes zero when:

y=0

So the y-component vanishes on the x-axis.

Condition for Ex = 0

On x-axis:

∣x+a∣
3
x+a
	​

+2
∣x−a∣
3
x−a
	​

=0

For the region -a < x < a:

|x+a| = x+a
|x-a| = a-x

Thus:

(x+a)
2
1
	​

=
(a−x)
2
2
	​


Solving:

a−x=
2
	​

(x+a)

Final result:

x=a
1+
2
	​

1−
2
	​

	​


Rationalized form:

x=a(3−2
2
	​

)

Zero Electric Field

The total field becomes zero when BOTH components vanish:

Ex = 0
Ey = 0

Since Ey = 0 requires y = 0, the zero-field point is:

(a(3−2
2
	​

),0)

Step 5 — Numerical Calculation

Given:

a = 0.2 m
y = 0.3 m
q = 2 μC = 2×10⁻⁶ C
k = 9×10⁹ N·m²/C²

We use:

E
x
	​

=−
(a
2
+y
2
)
3/2
kqa
	​


and

E
y
	​

=
(a
2
+y
2
)
3/2
3kqy
	​


Compute denominator

(a
2
+y
2
)
3/2
=(0.2
2
+0.3
2
)
3/2
=0.0469

Compute Ex

E
x
	​

=−
0.0469
(9×10
9
)(2×10
−6
)(0.2)
	​


Result:

Ex ≈ -7.67 × 10⁴ N/C
Compute Ey

E
y
	​

=
0.0469
3(9×10
9
)(2×10
−6
)(0.3)
	​


Result:

Ey ≈ 3.45 × 10⁵ N/C
Final Numerical Electric Field
E ≈ (-7.67×10⁴)i + (3.45×10⁵)j   N/C

Magnitude:

∣
E
∣=
E
x
2
	​

+E
y
2
	​

	​


Result:

|E| ≈ 3.53 × 10⁵ N/C
Step 6 — Limit for y >> a

When:

y >> a

then:

a
2
+y
2
≈y
2

So:

E
x
	​

≈−
y
3
kqa
	​


and

E
y
	​

≈
y
2
3kq
	​


Since:

Ey >> Ex

the field becomes approximately vertical:

E
≈
y
2
3kq
	​

j
^
	​
