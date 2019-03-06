### Math Review: Exponentials

RC circuits are described via the exponential function <lrn-math>e^{-t/\tau} </lrn-math>. This is exponential decay as a function of time. The variable (time) is in the exponential and the physical quantity starts at some value say <lrn-math>Q_0 </lrn-math> and decreases very quickly, but asymptotically, to zero. For example, a capacitor with initial charge <lrn-math>Q_0 </lrn-math> will discharge when connected to a resistor R. The charge as a function of time is given by 

<lrn-math>Q(t)=Q_0e^{-t/tau} </lrn-math>

[ciscode|rev=1|tool=elmsmedia|item=4894|entity_type=node|render=display_mode|display_mode=image]


The constant <lrn-math>\tau </lrn-math> has units of time. It is called the time constant of the circuit. 

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
This will come back in multiple context in this class. Whenever a circuit element is discharging, we get exponential decay. 
</lrndesign-sidenote>

While it is possible to have exponential growth <lrn-math>e^{+t/\tau} </lrn-math> in physics, it usually applies to physical phenomena getting "out of hand" with unbounded values. In the case of a capacitor charging, the growth is bounded. The capacitor will charge to a final voltage/charge asymptotically. This is mathematically described as <lrn-math> 1-e^{-t/\tau} </lrn-math>, the charge grows to reach 1 as the exponential terms disappears. For example, the charge as a function of time on a charging capacitor is given by 

<lrn-math> Q(t)=Q_0\left(1-e^{-t/tau}\right) </lrn-math>

[ciscode|rev=1|tool=elmsmedia|item=4895|entity_type=node|render=display_mode|display_mode=image]

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
You may want to review Chap 15 on oscillations. The damped oscillator had an amplitude that was described by an exponential decay. 
</lrndesign-sidenote>


### Math Review: The vector cross-product. 

In the second part of this week's material, we study Biot-Savard law which involves the cross-product. 

The first time we saw the cross-product was in Phys 211 when we introduced the notion of torque. 

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">Review section 12.10</span>
</stop-note>

When applied to torque the cross-product was

 <lrn-math>\vec{\tau}=\vec{r}\times\vec{F} </lrn-math>
 
The magnitude of this product is <lrn-math>|\tau| =rF\sin\theta </lrn-math> where the angle is the angle between the two vectors. The order is important for the cross product and the direction is given by the right-hand rule. There are two ways to do the right-hand rule. I prefer the second (to the right) in this image.  

[ciscode|rev=1|tool=elmsmedia|item=4603|entity_type=node|render=display_mode|display_mode=image]

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
Make sure you differentiate the dot product (whose result is a number) from the cross product which results in a vector. 
</lrndesign-sidenote>

Try the right hand rule in the question below.  

[ciscode|rev=1|tool=elmsmedia|item=4605|entity_type=node|render=display_mode|display_mode=h5p]

There is also a way to do the cross-product using component notation and I will show this in one of the problem solving video. 
