The wave that is "linked" to the photon is the electromagnetic wave which is a fairly complicated object with oscillating electric and magnetic fields. A full analysis is very technical. We can understand the concepts of quantum mechanics by using a simplified picture for the wave. 

Let us denote the photon wave by a function called <lrn-math>\phi(x)</lrn-math> where <lrn-math>\phi</lrn-math> represents the amplitude of the wave and x is the position on the screen. The amplitude of the wave will vary for different position so we say <lrn-math>\phi</lrn-math> is a function of <lrn-math>x</lrn-math> or <lrn-math>\phi(x)</lrn-math>. Let us imagine that the wave oscillates between 1 and -1. 

> Recall, a wave oscillates in space (with a certain wavelength) and it oscillates also in time (with a certain frequency). In practice, the oscillation in time are so fast that we always detect average quantity. Therefore, we will only keep track of variation in space. 

Given our discussion from the last section on double slits, the probability of finding a photon at position x (denoted P(x)) will be 

<lrn-math>P(x) = \phi(x)^2</lrn-math>. 

This is a definition. Because we need to square, we can actually call <lrn-math>\phi</lrn-math> the **probability amplitude**. This is a strange object, the square root of probability!

> Again, I remind you that probabilities are just numbers with no units. The probability that a coin lands on head is 1/2. No units needed. The **probability amplitude** that a coin lands on head is <lrn-math>\frac{1}{\sqrt{2}}</lrn-math>. This is also just a number with no units. Once you square it, it gives the probability of 1/2.

Returning to the double slits. See the figure below that shows the intensity of each wave from each slit and the combined result; more intense is darker. Remember, the **intensity** of a wave is equal to its amplitude squared, so in the language of quantum mechanics intensity= <lrn-math>\phi(x)^2</lrn-math>. 

[ciscode|rev=1|tool=elmsmedia|item=2241|entity_type=node|render=display_mode|display_mode=image]

So let us denote the wave from slit 1, <lrn-math>\phi_1</lrn-math> and the wave from slit 2, <lrn-math>\phi_2</lrn-math>. 

If only slit 1 is opened we get the pattern on uppermost left image. The probability is max at the center and goes to zero on either side. Same is true with slit 2, slightly shifted. 

Now, if we open both slits, the combined wave that will reach the screen will be a superposition of wave 1 and wave 2. Superposition is a sum, so <lrn-math>phi(x)</lrn-math> along the screen is: 

<lrn-math>\phi(x) =\phi_1(x)+\phi_2(x)</lrn-math>

The probability of finding a photon at x is the square of <lrn-math>\phi(x)</lrn-math>. 

<lrn-math>P = (\phi_1+\phi_2)^2</lrn-math>.

> Notice, I will drop the <lrn-math>(x)</lrn-math> sometimes to make the equation less cluttered; it is a short-hand notation. This is OK because the symbol <lrn-math>(x)</lrn-math> is just to remind us that <lrn-math>P</lrn-math> and <lrn-math>\phi</lrn-math> depend on the position on screen. They vary, they are function of horizontal position on the screen. So the actual probability is written (in long-hand) as <lrn-math>P(x) = (\phi_1(x)+\phi_2(x))^2</lrn-math>

## Classical Probability versus Quantum probability

We can now see the first really strange thing about quantum mechanics. Let us say that we want to know the probability of photons landing at a position <lrn-math>x</lrn-math> where <lrn-math>\phi_1 = \frac{1}{\sqrt{4}}</lrn-math> and <lrn-math>\phi_2=- \frac{1}{\sqrt{4}}</lrn-math>. The two wave amplitudes are different because the waves travel different distances. The negative sign means that wave 2 is in a trough. 

If only slit 1 is opened. The probability of finding a photon at x would be 1/4. 

If only slit 2 is opened. The probability of finding a photon at x would also be 1/4 (the minus sign does not matter when you square). 

Normal thinking human would say that the probability with both slits open together would be the sum. The probability that the photon from slit 1 **OR** the photon from slit 2 land at x **naively** should be 1/4+1/4 = 1/2 (the sum of the probabilities). 

But NO! The probability is <lrn-math>P = (\phi_1+\phi_2)^2 = \left(\frac{1}{\sqrt{4}}-\frac{1}{\sqrt{4}}\right)^2 =0</lrn-math>

> The probability of finding a photon in certain locations with two waves on screen is less than with a single wave! This is destructive interference (this should make sense to you if one wave is in a crest and one is in a trough at the same spot).

Quantum probability does not use the addition rule! This is because probability are determined by a preliminary step of adding probability amplitudes. There can be interferences when adding those amplitudes!

