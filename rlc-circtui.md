## The RLC Circuit

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">32.5</span>
</stop-note>

The RLC circuit puts everything together, the phasor of the RLC circuit will always look something like

[ciscode|rev=1|tool=elmsmedia|item=4972|entity_type=node|render=display_mode|display_mode=image]

<lrn-math> V_R is always in phase with current while V_L leads and V_C lags </lrn-math>

Note that the length of these phasors are all the peak values at each circuit element. The instantaneous voltage obey the equation

<lrn-math> v_L+v_R+v_C=\mathcal{E} <lrn-math>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
Note that one of those must be positive when the other is negative since the V_L and V_C phasor are 180 degrees shifted from one another.  
</lrndesign-sidenote>

To find the relationship between the peak values, **we add the phasors as vectors** and find the magnitude. The easiest way is to first subtract V_C from V_L (if the capacitor is bigger, you would do the reverse). 

[ciscode|rev=1|tool=elmsmedia|item=4973|entity_type=node|render=display_mode|display_mode=image]

The resulting addition of all the phasor will give the source phasor of length <lrn-math>\mathcal{E}_0 </lrn-math>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
Whats the point of all this? Two things, what we are interested is to see the lag between the current in the circuit (aligned with V_R) and the emf of the source. This is denoted <lrn-math>\phi </lrn-math> in the figure. Second we can find a relationship for the size of the current. 
</lrndesign-sidenote>

Using Pythagoras and the known relationships between capacitive/inductive reactances, one arrives at

 <lrn-math> I =\frac{\mathcal{E}_0 }{Z} </lrn-math>
 
 with the impedance of the RLC circuit given by
 
 <lrn-math>Z=\sqrt{R^2+(X_L-X_C)^2} </lrn-math>
 
 [ciscode|rev=1|tool=elmsmedia|item=4974|entity_type=node|render=display_mode|display_mode=image]
 
## Resonance

One can see that the impedance of an RLC circuit is minimized when the phasor for the inductor and capacitor exactly cancel. This is called resonance and the phase angle is zero, source emf and current are in phase. 

[ciscode|rev=1|tool=elmsmedia|item=4969|entity_type=node|render=display_mode|display_mode=mediavideo]

