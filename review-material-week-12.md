Faraday's law is fairly all new but the second part of this week has many similarities with previous work we have seen so let me spelled those out. 

## Review of capacitor. 

Earlier in the class, we defined the capacitance of an object as 

<lrn-math> C = \frac{Q}{\Delta V_C} </lrn-math>

The capacitance turned out to depend only on the geometry of the object and it measure the ability to store charge for a given amount of potential needed. 

The most typical capacitor is the parallel plate capacitor (area A, distance d) with capacitance equal to 

<lrn-math>C=\frac{epsilon_0A}{d} </lrn-math>

In a circuit with a capacitor and a resistor 

[ciscode|rev=1|tool=elmsmedia|item=4943|entity_type=node|render=display_mode|display_mode=image]

The capacitor will discharge. Using Kirchoff's loop law of conservation of energy, one finds that

<lrn-math>\Delta V_C +\Delta V_R = 0 </lrn-math>

<lrn-math> Q/C +R \frac{dQ}{dt} </lrn-math>

where we wrote the current as the rate of change of charge (the derivative). The solution, to this differential equation is 

<lrn-math> Q(t) = Q_0 e^{-t/\tau} </lrn-math>

with the time constant <lrn-math>\tau = RC </lrn-math>. Adding a battery to the circuit will lead to a new source term and we can now charge the capacitor. The resulting equation for charge and (for the potential on the capacitor) is fairly similar (see your formula sheet). 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The charge and potential can charge (increase) or discharge (decrease) in a RC circuit depending how you start. In either cases the current always decrease over time and the end current in a RC circuit is always zero (either the capacitor is empty or full). 
</lrndesign-sidenote>

To repeat, the current in a RC circuits always go like

<lrn-math> I = I_0 e^{-t\tau} </lrn-math> 

In the second part of this week we will introduce the "magnetic analog" of the capacitor, **the inductor**. We will discuss inductance and the the LR circuits. The LR circuits will have similar exponential decay of the current. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The final equations looks the same but the physics and the reasoning is very different.  
</lrndesign-sidenote>

## Simple Harmonic Oscillator. 


