First order circuit -> One capacitor or one inductor
Only one energy storage component 
Equations are given by first order differential equations

1. Reduce circuit into simple form
2. Define v and i directions for C or L, note initial conditions
		2.1. No charge in capacitor if t == 0
3. Write template solutions
4. Kind $K_1$  from new steady state

$$
V_S - iR - v = 0 \\[13pt]
i = C\frac{dv}{dt} \\[13pt]
V_S - RC\frac{dv}{dt} - v = 0 \\[13pt]
\frac{dv}{dt} + \frac{v}{RC} + \frac{V_s}{RC} 
$$
Separate variables
$$
	\frac{dt}{RC} = \frac{dv}{V_s - v}
$$
and integrate
$$
	v = V_s - V_se^{\frac{-t}{RC}}
$$

$V_se^{\frac{-t}{RC}}$ is a transient term so it tends to 0 as t -> n
Which means that a capacitors voltage will approach $V_s$ so eventually the potential difference will be 0 so the circuit will be steady state

Exponential part is the same when working out transient current and voltage

Capacitors start as short circuits and tend towards an open circuit
Inductors start as open circuits and tend towards short circuits

The time constant describes the rate at which the exponential function decays. This is useful if you want to control the speed of response of the circuit.