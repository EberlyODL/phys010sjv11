The wave that is "linked" to the photon is the electromagnetic wave which is a fairly complicated object with oscillating electric and magnetic fields. A full analysis is very technical. We can understand the concepts of quantum mechanics by using a simplified picture for the wave. 

Let us denote the photon wave by $\phi(x)$ where $\phi$ represents the amplitude of the wave and x is the position on the screen. The amplitude of the wave will vary for different position so we say $\phi$ is a function of $x$ or $\phi(x)$. Let us imagine that the wave oscillates between 1 and -1. 

> a wave oscillates in space (with a certain wavelength) and it oscillates also in time (with a certain frequency). In practice, the oscillation in time are so fast that we always detect average quantity. Therefore, we will only keep track of variation in space. 

Given our discussion from the last section, the probability of finding a photon at position x (denoted P(x)) will be 

$P(x) = \phi(x)^2$. 

Because we need to square, we say that $\phi$ is the **probability amplitude**. This is a strange object, the square root of probability!

> Again, I remind you that probabilities are just numbers with no units. The probability that a coin lands on head is 1/2. No units needed. The **probability amplitude** that a coin lands on head is $\frac{1}{\sqrt{2}}$. This is also just a number with no units. Once you square it, it gives the probability of 1/2.

Returning to the double slits. See the fig below that shows the intensity $\phi(x)^2$ of each wave from each slit and the combined result; more intense is darker. 

[ciscode|rev=1|tool=elmsmedia|item=2241|entity_type=node|render=display_mode|display_mode=image]

So let us denote the wave from slit 1, $\phi_1$ and the wave from slit 2, $\phi_2$. 

If only slit 1 is opened we get the pattern on uppermost left image. The probability is max at the center and goes to zero on either side. Same with slit 2, slightly shifted 

Now, if we open both slits, the wave that will reach the screen will be a superposition of wave 1 and wave 2. Superposition is the sum so 

$\phi(x) =\phi_1(x)+\phi_2(x)$

The probability of finding a photon at x is the square of $\phi$. 

$P = (\phi_1+\phi_2)^2$.

> I will drop the $(x)$ sometimes to make the equation less cluttered. The symbol $(x)$ is just to remind us that $p$ and $\phi$ depends on position on screen. They vary, they are function of horizontal position on screen. So the actual probability is written as $P(x) = (\phi_1(x)+\phi_2(x))^2$

## Classical Probability versus Quantum probability

We can now see the first really strange thing about quantum mechanics. Let us say that we want to know the probability of photons landing at a position $x$ where $\phi_1 = \frac{1}{\sqrt{4}}$ and $\phi_2=-
\frac{1}{\sqrt{4}}$. The two wave amplitudes are different because the waves travel different distances. The negative sign means that wave 2 is in a through. 

If only slit 1 is opened. The probability of finding a photon at x would be 1/4. 

If only slit 2 is opened. The probability of finding a photon at x would also be 1/4 (the minus sign does not matter when you square). 

Normal thinking human would say that the probability with both slits open together would be the sum. The probability that the photon from slit 1 **OR** the photon from slit 2 land at x **naively** should be 1/4+1/4 = 1/2 (the sum of the probabilities). 

But NO! The probability is $P = (\phi_1+\phi_2)^2 = \left(\frac{1}{\sqrt{4}}-\frac{1}{\sqrt{4}}\right)^2 =0$

> The probability of finding a photon in certain locations with two waves on screen is less than with a single wave! This is destructive interference.

Quantum probability does not use the addition rule! This is because probability are determined by a preliminary step of adding probability amplitudes. There can be interferences when adding those amplitudes!

