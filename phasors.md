## Phasors and Reactances 

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">32.1-32.4</span>
</stop-note>

An AC circuit is a circuit powered by a source whose EMF alternate with time. Our convention will be to take a cosine. 

<lrn-math>\mathcal{E}=\mathcal{E}_0\cos(\omega t) </lrn-math>

where <lrn-math>\mathcal{E}_0 </lrn-math> is the peak value. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The average value over time of the potential is zero.
</lrndesign-sidenote>> 

To do AC circuit correctly, one needs to be careful with notation, we will use

* lower case for instantaneous values 
* upper case for peak values. 

For example, the current on a resistor at any given time will be denoted <lrn-math> i_R </lrn-math>. That current could be zero it could be the max current (denoted <lrn-math> I_R </lrn-math>), it could be the max current but in opposite direction or anything in between. 

Capacitor and inductor voltages are related to the integral/derivative of the current (eq 32.8 inverted and eq 32.16). This has two main implications: 

* The derivative/integral changes the phase by <lrn-math>\pm \pi/2 </lrn-math> between their voltage and theirs current. The capacitor lags while the inductor leads the current. 
* The peak value of <lrn-math>V_C </lrn-math> and <lrn-math>V_L </lrn-math> **depends on angular frequency**. 

In terms of peak value (and only peak value), the capacitor and the inductor obey something that looks like Ohm's law

<lrn-math> V_C = X_C I_C </lrn-math>
while
</lrn-math> V_L = X_L I_L </lrn-math>

but the "reactances" <lrn-math>X_{C,L} </lrn-math> depend on the frequencies unlike for a resistor where it is just a constant R. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
This dependence on the angular frequency allows one to build circuits for low-pass and high pass filters. The idea is that you measure the voltage of a circuit element and that voltage will be blocked (near zero) for low or high frequencies depending on how you build the circuit. 
</lrndesign-sidenote>

Examples, 31.1-32.5 are all very good to practice. 


[ciscode|rev=1|tool=elmsmedia|item=4970|entity_type=node|render=display_mode|display_mode=h5p]

[ciscode|rev=1|tool=elmsmedia|item=4971|entity_type=node|render=display_mode|display_mode=h5p]