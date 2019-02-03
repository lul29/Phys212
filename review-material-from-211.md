## Review material

Again, let us start by reviewing the fundamental ideas we have already seen that will be needed this week. 



[ciscode|rev=1|tool=elmsmedia|item=4842|entity_type=node|render=display_mode|display_mode=image]

The relationship from Phys 211 was that the potential energy associated with a conservative force is the negative of the work done by that force while it goes from some initial point i to some final point f

<lrn-math> \Delta U = - W(i\rightarrow f) = -\int_{s_i}^{s_f}\vec{F} \cdot d\vec{s} </lrn-math>

### Notes

* only the component of the force along the path matters. If the force is perpendicular to the path, the work is zero. 
* Potential energy depends on position, the formula above gives the potential energy at position <lrn-math>s_f </lrn-math> - the potential energy at position <lrn-math> s_i </lrn-math>
* The electric force is conservative which means that the work will be the same for all paths between position i and position f. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The last part is important! You can choose the path when doing the integral so choose something that simplifies your life and make the integral easier. 
</lrndesign-sidenote>

## Line integral. 

A line integral is an integral of a function to be evaluated over a specific path. The path has a direction (from A to B in the figure below). In this course, we will encounter line integrals of vectors functions so we will only discuss this case here. 

[ciscode|rev=1|tool=elmsmedia|item=4843|entity_type=node|render=display_mode|display_mode=image]

Suppose you have some vector functions that varies over space    <lrn-math> \vec{F}(x,y,z) </lrn-math>. We define the line integral of this vector function over a path C as follows
<lrn-math> \int_C \vec{F}(x,y,z \cdot d\vec{l} </lrn-math>
where we took a dot product between <lrn-math>\vec{F} </lrn-math> and <lrn-math>d\vec{l} </lrn-math> which is a vector with length dl that points tangent to the path in the direction of the path.

To do this integral you may need to divide the part into different segment, evaluate the dot products and integrate over the appropriate limits for each segments. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
 The figure shows the force vector. For us we will mostly use the electric (and later magnetic) fields in our line integrals. 
</lrndesign-sidenote>
