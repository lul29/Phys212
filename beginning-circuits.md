## Beginning Circuits. 

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">26.4-26.6</span>
</stop-note>

Ok we are now ready to put all the things together and apply them to circuits. The book starts nicely by first introducing the battery and the the capacitor. Not many examples or problems here in this section. 

### EMF
This section introduces the first two circuits concepts, the emf (pronounce e-m-f) of a battery and the capacitance of capacitor. 

<lrndesign-sidenote label="Definition" icon="bookmark" bg-color="#c2c2a3">
EMF: This stands for electromotive force. Essentially it is a measure of the work (energy) per unit of charge that a particular source can do. The nature of the process depends on the source and typical battery use chemical reactions to move positive ions. But later in this course, we will create emf using magnetic fields. For a typical battery, the emf of the battery is nearly the same as the voltage of the battery. For an ideal battery, it is the same. 
</lrndesign-sidenote>


<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
You should assume ideal batteries in all physics problems unless otherwise specified.  In the video below I create an extremely non-ideal battery. 
</lrndesign-sidenote>


[ciscode|rev=1|tool=elmsmedia|item=4844|entity_type=node|render=display_mode|display_mode=mediavideo]

### Capacitance. 

Capacitance measures how hard it is to charge a particular object. It measures the amount of charge you get per amount of potential it cost you. 

Interestingly capacitance only depends on the shape of the object. This is because different object shape will have different E field configuration (e.g. line of charge versus plane of charge). The E field configuration determines the potential (via the integral relationship). 

The key formula is 

<lrn-math>
C=\frac{Q}{\Delta V_C}
</lrn-math>


<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
 The book then discusses the equivalent capacitance of capacitor in series and in parallel. See my video next page for more on this. 
</lrndesign-sidenote>

### Energy in capacitor and E field

Formula 26.25 for the energy inside of a capacitor is super important. It is obtained by calculating the total work of charging a capacitor and this is an integral with the answer quadratic in the charge.

Conceptually, this is because it takes more energy to put an extra charge on a charged capacitors than the energy it took to put the first charge at the beginning. 

Note that there is two ways to write this energy. Either as 

<lrn-math>
U_C = \frac{Q^2}{2C} </lrn-math>

or 

<lrn-math>
U_C = \frac12 C(\Delta V_C)^2 </lrn-math>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
 This is potential energy, we can get back this energy by discharging the capacitor. Where is the energy?? It turns out that the energy is in the electric field. The electric field, again, is very real and contain the energy. Eq 26.27 about the energy density of an electric field is always true. Whenever there is an electric field in space, the energy density is given by <lrn-math>\frac{\epsilon_0}{2} E^2 </lrn-math>. The total energy is this density times the volume of space over which the E field constant. For a non-constant E field, we need to do a volume integral. 
</lrndesign-sidenote>
