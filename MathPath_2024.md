# MathPath 2024 Breakout Classes

## Special Relativity: Week 3 Afternoon
Theorem: (Invariance Principle) All non-accelerating observers agree on the laws of physics. The speed of light is a law of physics. Therefore, all non-accelerating observers see light moving at the same speed. This speed is called $c$, and it's about $3 \cdot 10^8$ meters per second. 

Creation: Light clock, a device with a light bulb, a mirror, and a detector that detects when light reaches it. The distance between the light bulb and the mirror is 3 meters, and the light travels a total distance of 6 meters when it reaches the detector. We define a tick as the time it takes for the light to travel from the source to the detector. To a motionless observer, the time it takes for one tick is $\frac{6}{c}$.

### Time Dialation

Thought experiment: Imagine two astronauts, Alice and Bob, way out in space where there is no gravity. Bob is stationary in the space station while Alice is flying outside to the right of Bob at a constant speed in one direction. Both astronauts are holding a light clock, and Alice holds hers vertically with the mirror parallel to her direction of travel. Set Alice's speed to $v$ and the time for one tick equal to $t$. Now, relative to Bob, find $t$ according to $v$ and the speed of light, $c$. First, know that the distance the light travels is not 6 meters because Alice is moving. The path of the light happens to form two congruent right triangles with the distance that Alice travels. We can calculate the hypotenuses of these right triangles to get the distance the light travels which turns out to be $2\sqrt{\frac{v^2t^2}{4} + 3^2}$. We also know that the distance is equal to $ct$, setting up the equation: $ct=2\sqrt{\frac{v^2t^2}{4} + 3^2}$. This simplifies down to $t=\frac{6}{\sqrt{c^2-v^2}}$. Recall from earlier that to a motionless observer, $t=\frac{6}{c}$. It seems that, to an observer in motion, time seems to be moving slower. We can generalize this hypothesis by setting the length from the light source to the mirror equal to $l$ and Alice's relative tick time to $t'$. Using the same method by the Pythagorean Theorem of before, we get $(\frac{ct'}{2})^2=(\frac{vt'}{2})^2+l^2$. We isolate $l^2$ to get $l^2=\frac{t'^2(c^2-v^2)}{4}$. Recall that $l$ is equal to Bob's tick times $c$. We replace $l$: $\frac{(ct)^2}{2}=\frac{t'^2(c^2-v^2)}{4}$. From here, we retrieve the result $\frac{t'}{t}=\frac{1}{\sqrt{1-\frac{v^2}{c^2}}}$, which shows the relation between the time interval of a motionless observer and a moving observer.

## To Infinity and Beyond: Week 4 Morning
### Vocabulary: 
An **injection** between sets A and B is when every element of set A can be mapped to a unique element in set B. <br>
A **surjection** between sets A and B is when every element of set B has at least one unique correspondance to an element in set A.
A **bijection** between sets A and B is when there is both an **injection** and a **surjection** between A and B.

In general, we compare sets of infinities using these terms. For example, we can say that there are the same number of natural numbers and positive even numbers. To do this, we create a bijection between the two sets by pairing $1$ to $2$, $2$ to $4$, $3$ to $6$, and so on and so forth. Every element of the set of natural numbers $(\mathbb{N})$ is paired with exactly one element in the set of positive even numbers, so we say that there are an equal number of elements in both sets. <br>
*Note: If a pairing between two sets does not result in a bijection it still does not prove that there does not exist a bijection between them.*

### Different types of infinity
