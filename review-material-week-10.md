## Math Review: The Line Integral. 

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">Look back at Sec 9.3</span>
</stop-note>

Line integral were first introduced in Chap 9 of your book when we discussed work although we did not use this terminology and we did not do complicated cases. We now expect more calculus knowledge so let us review quickly the idea of the line integral in the context of work before we move on to magnetic fields. 

In Phys 211, we saw that the work done by a force was

<lrn-math> W = =\int_C \vec{F}\cdot d\vec{l} </lrn-math>

where C is the one dimensional path in space where the force is applied. 

[ciscode|rev=1|tool=elmsmedia|item=4912|entity_type=node|render=display_mode|display_mode=image]

The trick to evaluate such integrals is as follows 

* Evaluate the dot product <lrn-math>\vec{F}\cdot d\vec{l} at each point along the path. This results in a scalar function which varies along the path. 	
* Express the resulting scalar as a function f(l)  dl with some limit of integration <lrn-math>l_1,\;l_2 </lrn-math> that covers the whole path from A to B. This is the crucial step. 
* Once written as a 1D definite integral, evaluate it.

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
Many quantities in physics turns out to not be dependent on the particular path you choose. We can then choose paths where the calculations is easier (where the dot product has the same value everywhere in the path. A path may be divided into two pieces for example, on some parts the integrand would be zero, while on the other, its constant. 
</lrndesign-sidenote>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
If the integrand is constant (say equal to F), then you can take it out of the line integral and the integral is just the length of the line. 
</lrndesign-sidenote>


## Physics Review: Circular motion. 

The motion of an electric charge in an uniform magnetic field is uniform circular motion. 

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message"></span>
</stop-note>