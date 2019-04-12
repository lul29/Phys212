## Relativity Optional Reading

Section 31.1 of your book is very interesting, albeit technical. It is well worth reading briefly but we will not have any questions on it. The basic idea is that the magnetic force and magnetic field depends on velocity (in the force equation and in Biot-Savard or Ampere's law with current). But velocity measured relative to who? Remember back in PHYS 211, we saw that velocity is not an absolute concept. It must mean that the notion of a B field is not an absolute concept either. Indeed, this section shows with some specific examples that what an observer might call a B field, another observer will describe it as an E field and vice versa. You can be very quantitative and derive formula on how to relate E,B field for observers moving relative to one another at constant velocity.


<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
This idea that E or B depends on the observers strongly imply that the fundamental law of E&M should have E and B on "equal footing" up to the fact that we have electrically charged objects while we don't have magnetically charged objects.
</lrndesign-sidenote>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
A fun extra side note. The study of the concept of relativity in E&M led to the birth of the theory of special relativity and general relativity of Einstein. Very interesting story to look more into!
</lrndesign-sidenote>


## Displacement Current

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">31.2-31.3</span>
</stop-note>

Maxwell was the first to realize that there must be a missing terms in Ampere's related to the change in electric flux.

The book motivate this terms by looking at capacitor circuit and nothing that the amperian curve and surface can have any shape.

[ciscode|rev=1|tool=elmsmedia|item=4986|entity_type=node|render=display_mode|display_mode=image]

The two surfaces in the figure above should give the same answer for the B field but one on the left as an electric current made of electric charges piercing through it while the one on the right just has the flux of the electric field from the capacitor.

You can make Ampere's law if you imagine that there is a current inside the capacitor. We call it the displacement current.

<lrn-math>I_{disp}=\epsilon_0 \frac{d\Phi_e}{dt} </lrn-math>

This had unit of current (amps) but it is not really due to the motion of charges. It is just a changing flux of electric field.

Then Ampere-Maxwell law is

<lrn-math>\oint \vec{B}\cdot d\vec{l} = \mu_0 I_{through} + \mu_0\epsilon_0 \frac{d\Phi_e}{dt} </lrn-math>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The last is really <lrn-math>\mu_0 I_{disp}. Note that this last term looks very similar to Faraday's law with two important difference. There is a prefactor of <lrn-math>\epsilon_0\mu_0 </lrn-math> and it **it is a + sign**.
</lrndesign-sidenote>

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
The plus sign means that the induced magnetic field due to a changing E field obeys the opposite of Lenz's law. It wants to reinforce the change.
</lrndesign-sidenote>


Example 31.3 is important. Most applications of the displacement current


[ciscode|rev=1|tool=elmsmedia|item=4985|entity_type=node|render=display_mode|display_mode=h5p]