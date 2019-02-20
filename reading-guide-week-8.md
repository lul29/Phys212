## Reading Guide Week 8 Fundamental of Circuits. 

<stop-note title="Read Knight 4ed" icon="stopnoteicons:book-icon">
<span slot="message">Sec 28.1-28.8</span>
</stop-note>

This week we read Chap 28 except for the last section on RC circuits which we keep for next week. We will start by analyzing fundamental circuits this week with only resistors and batteries (and bulbs which act like resistor to a good approximation). !

One of the main first task in circuit is to write a "circuit diagram" drawing of real circuits with multiple wire. It does require practice to go from an actual real circuit to a circuit diagram. 
Here are the various circuits symbols that we will use. 

[ciscode|rev=1|tool=elmsmedia|item=4873|entity_type=node|render=display_mode|display_mode=image]

<lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
Notice how the lightbulb has 2 wires inside connected to two different outside metal conductors. As you should have discovered in your lab 3, a lightbulb has two ends like the other circuit elements we will learn in this class. 
</lrndesign-sidenote>

Section 28.2 is the crucial section from a physics point of view. The master equations for circuits are Kirchhoff's laws Eq 28.1 and Eq 28.2. Tactics box 28.1 is super important in explaining how to use those laws. 
 
<lrndesign-sidenote label="Definition" icon="bookmark" bg-color="#c2c2a3">
The sign conventions for the change in potential across a battery and resistor are crucial to learn. 
</lrndesign-sidenote>

Section 28.3 define the notion of power as the rate of thermal energy dissipated in a resistor. The general formula is 

<lrn-math> P_R=I\Delta V_R </lrn-math> which just comes from taking the derivative with respect to time of the potential energy U=qV where dq/dt becomes the current. 

There are two reformulations of this equation using Ohm's law and both are important in this context (see the check your understanding for good examples of where one formula is needed compared to the other). 

<lrn-math> P_R = I^2 R=\frac{(\Delta V_R)^2}{R} </lrn-math>

We then analyze resistor in series, resistors in parallels and real batteries with internal resistance. 

 <lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
 This chapter explains how a voltmeter (such as the IOLab) is used in parallel and how it needs to have a high resistance in order not to disturb the circuit. A ammeter needs to be in series in the circuit and needs to have a small resistance. The compass is our ammeter (and it has a very small resistance!). 
</lrndesign-sidenote>

Section 27.7 introduces the case of multi-loop circuits where one needs to be more methodical. Look carefully at problem solving strategy 28.1 and the two worked out examples 28.9, 28.10. The idea is to use Kirchhoff's two laws (Eq 28.1 and 28.2) for the whole circuit. Kirchhoff's loop law applies to any loop in the circuits. You will get multiple equations (one for each loop) allowing you to solve for multiple unknowns. 
 
 <lrndesign-sidenote label="Instructor Note" icon="bookmark" bg-color="#c2e5f2">
We keep section 28.9 for next week while section 28.8 explains the concept of grounding. 
</lrndesign-sidenote>

[ciscode|rev=1|tool=elmsmedia|item=4874|entity_type=node|render=display_mode|display_mode=mediavideo]

### Doing the worked out example problems. 
 
 
For the more complicated examples, do not just read the solutions in the book right away. I recommend the following procedure.  

1. First, you read the example question ONLY.
2. You take a piece of paper and try to solve it, without looking at the solution. 
3. You may need to study the material, read the text before the example. Pay particular attention to problem solving strategies or tactic boxes. 
4. You may need to struggle, abandon one way and try another. This is good. This is learning. 
4. If you get the answer, compare just the solutions to the one in the book. If its the same, great, now look at what the author did. If its not the same, look back at your process first and try to find where you could have gone wrong. 
5. If after 2 attempts (say 1/2 hour at least), it does not work look at the solution provided by the author. You will need to try a similar problem again later to make sure you can do it without help.  


All the worked example in this chapter are worth doing with many of them being very simple (just one equation). Example 28.6 shows you why car battery are dangerous.