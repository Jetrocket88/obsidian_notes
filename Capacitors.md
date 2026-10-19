[[Circuit Theory]]

# Capacitance Equation

$$
C = \frac{\varepsilon_0\varepsilon_rA}{d}
$$

C = capacitance (measured in farads)
eps_0 = permittivity of free space (usually a vacuum) (F/m)
eps_r = relative permittivity (dielectric constant) of the material between the panes, which 
is dimensionless 
A is the plate area  (m^2)
d is the distance separation between the plates (m)

# Charge Stored

$$
Q = CV
$$
Q (charge) (coulomb)
C (capacitance) (farad)
V (voltage) (volt)

# Current In A Capacitor

$$
i = C \frac{dv}{dt}
$$
i (current) (amps)
C (capacitance) (farad)
dv/dt (rate of change of voltage) (volts)
## Capacitors connected in series

![[Pasted image 20261016162026.png]]

$$
\frac{1}{C_S} = \frac{1}{C_1} + \frac{1}{C_2} +\frac{1}{C_3} + \dots
$$
(Because we are increasing the distance between the top plate and the bottom)
## Capacitors connected in parallel 

![[Pasted image 20261016162124.png]]

$$
C_p = C_1 + C_2 + C_3 + \dots
$$
## Note: It's opposite to the resistor equation

# Proving Series Eqn (Optional)

With N series-connected capacitors, the same current flows in all capacitors. Hence, each 
capacitor gains the same charge in the same time period.  This only applies to the capacitors in series.
$$
q = C_1v_1 = C_2v_2 = C_3v_3
$$


# Proving Parallel Eqn (Optional)

Note that all the capacitors in the branches must have the same voltages, therefore the same 
rate of change of the voltage. 
$$
i = (C_1 + C_2 + C_3 + \dots) \frac{dv}{dt}
$$

## Important note
Capacitors receive a potential difference that is the opposite to the resistor voltage eqn. A capacitor with the LOWEST capacitance receives the highest potential difference.

Capacitors can use a capacitor division equation. It is the same as the voltage division eqn but the capacitor values are inversed.

## Used in transformers
Capacitors can be used to drop voltage with very little power dissipation.

# Flashcards
#flashcards/eee/circuit_theory
What is the equation for the capacitance of a capacitor involving the area between the plates and the distance that separates them?
?
$$
C = \frac{\varepsilon_0\varepsilon_rA}{d}
$$
<!--SR:!2026-10-22,3,250-->

What is the equation for the charge stored in a capacitor? (steady state)
?
$$
Q = CV
$$
<!--SR:!2026-10-23,4,270-->

What is the time sensitive equation for the current flowing through a capacitor?
?
$$
i = C \frac{dv}{dt}
$$
<!--SR:!2026-10-22,3,250-->

What is the equation for total capacitance of capacitors connected in series?
?
$$
\frac{1}{C_S} = \frac{1}{C_1} + \frac{1}{C_2} +\frac{1}{C_3} + \dots
$$
<!--SR:!2026-10-22,3,250-->

What is the equation for total capacitance of capacitors connected in parallel?
?
$$
C_p = C_1 + C_2 + C_3 + \dots
$$
<!--SR:!2026-10-22,3,250-->

What is one of the special properties of capacitors connected in series?
?
The capacitors all charge at the same rate (current in a series circuit is the same at all points)
$$
q = C_1v_1 = C_2v_2 = C_3v_3
$$
<!--SR:!2026-10-22,3,250-->


What is one of the special properties of capacitors connected in parallel?
?
The capacitors all have the same rate of change of voltage (total voltage is the same in parallel branches)
<!--SR:!2026-10-22,3,250-->

What is the difference between the capacitor voltage division equation and the resistance voltage
division equation? Only when the capacitors all start with the same stored charge (equal or none)
?
The capacitor voltage division equation is the same, but all the values of capacitance are inversed.
$$
V_n = V_S \frac{1/C_n}{1/C_1 + 1/C_2 + \dots}
$$
<!--SR:!2026-10-22,3,250-->

What does it mean for a capacitor circuit to be "steady state?"
?
This happens when the capacitor voltage has settled to a constant value and transient current has
decayed to zero. Capital letters are used to represent steady state levels, as well as DC quantities.
<!--SR:!2026-10-20,1,230-->

What is the convention for writing time varying quantities?
?
Lower case letters
$$
	Q = CV \\[13pt]
	q = Cv
$$
<!--SR:!2026-10-22,3,250-->

When does current flow through a capacitor? How does it act when there is no voltage drop? why?
?
Current flows through a capacitor when the voltage across it is changing, due to this eqn:
$$
i = C\frac{dv}{dt}
$$
When there is no voltage drop, there is no current flow.
<!--SR:!2026-10-20,1,230-->

When there are rapidly changing voltages, how does a capacitor behave?
?
Like a short circuit (high current, low resistance)
<!--SR:!2026-10-22,3,250--> 

Once the capacitor has fully charged, what state is it said to be in?
?
Steady state, with a constant change of voltage, so no current. Effectively an open circuit.
Capacitor behaves like an open-circuit to DC (constant voltage)
<!--SR:!2026-10-20,1,230-->




