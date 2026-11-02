[[Circuit Theory]]

Thévenin's theorem says that the effect of a complicated linear circuit on a particular circuit element can be analysed by replacing the circuit, other than the element under analysis, by an equivalent circuit comprising a volt age source with internal resistance, as shown in Fig.3.
# Own Words

Any complicated linear (?) circuit can be simplified into an equivalent circuit comprising only of one source and one resistor.

# Complicated Circuit

![[Pasted image 20261014170102.png]]

# Simplified Circuit - Thévenin equivalent

![[Pasted image 20261014170134.png]]


# Theorem

Steps:
1. Remove the circuit element that you wish to find the current in, or voltage across
2. Calculate the voltage produced by the remaining circuit across the open-circuited terminals of the removed element, the calculated voltage is the Thévenin voltage.
3. Zero voltage and current sources and calculate Thévenin resistance looking back into open-circuited terminals.
4. The Thévenin equivalent circuit is then added to removed element to calculate it's operating conditions. 


# Example

![[Pasted image 20261014170642.png]]

Remove load element and calculate voltage

![[Pasted image 20261014170744.png]]

Remove voltage supply and replace with short circuit

![[Pasted image 20261014170802.png]]

Jump to supposed correct resistance? 
We know that the 2ohm resistor has no current as that is open circuited so we can safely ignore that.
I think it's only interested in the resistance going from one of the open circuits to the other, which would be 4ohms

![[Pasted image 20261014170950.png]]

Now we can replace the original circuit with the simplified circuit

![[Pasted image 20261014171154.png]]

and we can do a simple voltage divider equation to show that the Vrl is 2V

![[Pasted image 20261014171254.png]]

# Flashcards
#flashcards/eee/circuit_theory
What are the steps for calculating the Thevnin Equivalent circuit?
?
1. Remove the circuit element that you wish to find the current in, or voltage across
2. Calculate the voltage produced by the remaining circuit across the open-circuited terminals of the removed element, the calculated voltage is the Thévenin voltage.
3. Zero voltage and current sources and calculate Thévenin resistance looking back into open-circuited terminals.
4. The Thévenin equivalent circuit is then added to removed element to calculate it's operating conditions.
<!--SR:!2026-11-05,5,230-->


What is Thevnin's Theorem?
?
Any complicated linear circuit can be simplified into an equivalent circuit comprising only of one source and one resistor.
<!--SR:!2026-11-20,20,250-->


