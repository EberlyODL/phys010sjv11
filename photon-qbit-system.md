Lets be more concrete and look at a very specific example of a Qbit. 

Image that we have beam of photons where we can send one photon at a time on a straight line. This is possible to do using lasers. Lets say that there is upper path for the photons and a lower path for the photons. There are two detectors $D_0$ and $D_1$ that can tell us whether the photon was in the upper beam or lower beam. If the photon is in the upper beam we will call that 0 and if it is in the lower beam we call it 1. 

In quantum mechanics, we will be able to take superposition so it is useful a notation to distinguish to the two states better. A notation was invited by Paul Dirac and it is called the ket. 

$\lvert 0\rangle$ is a upper beam photon and 
$\lvert 1\rangle$ is a lower beam photon

The basic idea for the qbit is represent in the Fig. "qbit". 

[ciscode|rev=1|tool=elmsmedia|item=2247|entity_type=node|render=display_mode|display_mode=image]

Now we can introduce a beam splitter. In real life those are made with half-silvered mirror. They can be made such that when a photon is incident, there is a 50% chance that it is reflected or 50% that it is transmitted. 

If we start with a photon in the lower beam (state $\lvert 1\rangle$) and send it to a beam splitter, the photon will have 50% chance of being reflected back in the lower beam (back to $\lvert 1\rangle$) or 50% of passing thru and going to upper beam ($\lvert 0\rangle$).  

The resulting quantum state after the beam splitter is a superposition of the two states. We can denote this by saying that the state after beamsplitter (lets call it $\psi$) is 

$\lvert \psi \rangle=\frac{1}{\sqrt{2}}\lvert 0\rangle + \frac{1}{\sqrt{2}}\lvert 1\rangle$

The factor of $1/\sqrt{2}$ are what we use to call $\phi$, the wave associated with the photon. If you square the coefficient, we get the probabilities. So this particular state $\psi$ has probability of 1/2 (50%) of being in either state 0 or state 1. 

See fig. "superposition"
