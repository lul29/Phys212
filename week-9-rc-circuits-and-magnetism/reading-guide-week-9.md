## RC Circuits

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">Section 28.9</span>
</stop-note>

Discharging a capacitor is really a circuit with two components: a resistor and a capacitor. The resistor could be the equivalent resistor of a combination of resistors.  

The Kirchhoff loop equation for the circuit (eq 28.25) + definition of current as the derivative of charge (eq 28.6) lead to the equation

<lrn-math> \frac{dQ}{dt}+\frac{Q}{RC} </lrn-math>

and the solution to this is the exponential decay with time constant 

<lrn-math>\tau = RC </lrn-math>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
 When a capacitor discharges, the charge, voltage and current all exponentially decrease. When a capacitor charges, the voltage and charge increase but the current still decreases. The end current through the capacitor of an RC circuit is zero. 
</lrndesign-sidenote>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The quantities describe in this section refers to the current, charge and voltage on the capacitor. Be careful not to apply these formulas to the entire circuit. 
If the capacitor is in parallel with a resistor for example, the end current after a long time on the capacitor will be zero (whether charging or discharging) but there could be a non-zero current on the resistor. 
</lrndesign-sidenote>


Example 28.12 is important while challenge example 28.13 is more advanced than what you need for this course. 

## Check your understanding RC Circuits. 