## Math Review: The Line Integral. 

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">Look back at Sec 9.3</span>
</stop-note>

Line integral were first introduced in Chap 9 of your book when we discussed work although we did not use this terminology and we did not do complicated cases. We now expect more calculus knowledge so let us review quickly the idea of the line integral in the context of work before we move on to magnetic fields. 

In Phys 211, we saw that the work done by a force was

<lrn-math> W = =\int_C \vec{F}\cdot d\vec{l} </lrn-math>

where C is the one dimensional path in space over which the force is applied. 

[ciscode|rev=1|tool=elmsmedia|item=4912|entity_type=node|render=display_mode|display_mode=image]

The trick to evaluate such integrals is as follows 

* Evaluate the dot product <lrn-math>\vec{F}\cdot d\vec{l} at each point along the path. This results in a scalar function which varies along the path. 	
* Express the resulting scalar as a function f(l)  dl with some limit of integration <lrn-math>l_1,\;l_2 </lrn-math> that covers the whole path from A to B. This is the crucial step. 
* Once written as a 1D definite integral, evaluate it.

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
Many quantities in physics turns out to not be dependent on the particular path you choose (or the path is completely up to you).  We can then choose paths where the calculations is easier, i.e. where the dot product has the same value everywhere on the path. A path may need be divided into multiple pieces. For example, on some parts the integrand would be zero, while on others, it would  constant. 
</lrndesign-sidenote>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
If the integrand is constant (say equal to F), then you can take it out of the line integral and the integral is just the length of the line. (over which the force was constant). The large majority of the examples in these courses usually reduce to such cases. 
</lrndesign-sidenote>


## Physics Review: Circular motion. 

As we will see, the motion of an electric charge in a uniform magnetic field is uniform circular motion (with no electric field and neglecting gravity). 

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">You may want to review Sec 4.4-4.5 and 8.1-8.4 from Phys 211 (available on the etext in masteringphysics</span>
</stop-note>

### Angular variable

omega is the angular velocity and it is related to the angular displacement via the usual kinematic relationships. 

[ciscode|rev=1|tool=elmsmedia|item=4289|entity_type=node|render=display_mode|display_mode=image]

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
We will take counter clockwise rotation to be positive and clockwise rotation to be negative but this is a convention. 
</lrndesign-sidenote>

### Connection angular to linear variables. 

Uniform circular motion means constant angular velocity and speed but the velocity vector is constantly changing direction. This means that circular motion always has an acceleration. This is the centripetal acceleration. 

For circular motion, we do not use the x-y coordinate system. Instead we will talk about radial (r) and tangential (t) direction. The radial direction points toward the center of the circle. This is really a coordinate system that spins with the motion.

[ciscode|rev=1|tool=elmsmedia|item=4290|entity_type=node|render=display_mode|display_mode=image]

The connection between linear variable (in the rt coordinate system) and angular variables <lrn-math>\theta, \omega </lrn-math> can be summarized as follows. 

[ciscode|rev=1|tool=elmsmedia|item=4291|entity_type=node|render=display_mode|display_mode=image]
 
<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The tangential acceleration <lrn-math>a_t </lrn-math> is zero for now because we are dealing with uniform circular motion only. 
</lrndesign-sidenote>



