# Photon Qbit system.

We can be concrete and look at a very specific example of a Qbit.

Image that we have a beam of photons where we can send one photon at a time on a straight line. This is possible to do using lasers. Let us say that there is an upper path for the photon and a lower path. There are two detectors D\_0&lt;/lrn-math&gt; and D\_1&lt;/lrn-math&gt; that can tell us whether the photon was in the upper beam or lower beam. If the photon is in the upper beam we will call that "0" and if it is in the lower beam we call it "1".

> the messenger will decide where to put the photon, up or down, to transmit the message 0 or 1.

In quantum mechanics, we will be able to do a superposition such that the photon is in a superposition of up and down beams. It is useful to introduce a new notation to distinguish the two states better..

\lvert 0\rangle&lt;/lrn-math&gt; is a upper beam photon and

\lvert 1\rangle&lt;/lrn-math&gt; is a lower beam photon

> The strange \|&gt; symbol was invented by Paul Dirac and it is called the "ket". It means "a quantum state" and whatever is inside the \|&gt; is the name of the quantum state.

The basic idea for the Qbit is represent in the Fig. "Qbit".

\[ciscode\|rev=1\|tool=elmsmedia\|item=2247\|entity\_type=node\|render=display\_mode\|display\_mode=image\]

Now we can introduce a beam-splitter. In real life those are made with half-silvered mirror. They can be made such that when a photon is hits the beam-splitter, there is a 50% chance that it is reflected and 50% chance that it is transmitted.

If we start with a photon in the lower beam \(state \lvert 1\rangle&lt;/lrn-math&gt;\) and send it to a beam splitter, the photon will have 50% chance of being reflected back in the lower beam \(back to \lvert 1\rangle&lt;/lrn-math&gt;\) or 50% of passing thru and going to upper beam \(\lvert 0\rangle&lt;/lrn-math&gt;\).

The resulting quantum state after the beam splitter is a superposition of the two states. We can denote this by saying that the state after beam-splitter \(let us call it \psi&lt;/lrn-math&gt;, pronounced "psi"\) is

\lvert \psi \rangle=\frac{1}{\sqrt{2}}\lvert 0\rangle + \frac{1}{\sqrt{2}}\lvert 1\rangle&lt;/lrn-math&gt;

The factor of 1/\sqrt{2}&lt;/lrn-math&gt; are in fact just \phi&lt;/lrn-math&gt; \(pronounced "phi"\), the_probability amplitude_ associated with the photon wave. If you square the 1/\sqrt{2}&lt;/lrn-math&gt;, we get the probabilities.

Make sure you understand the notation, I know this is new and strange but the idea under the notation is simplest. A photon in the quantum state \psi&lt;/lrn-math&gt; is a photon whose probability is given by the superposition of two waves. The photon has probability of 1/2 \(50%\) of being in either state 0 or state 1.

See fig. "superposition"

\[ciscode\|rev=1\|tool=elmsmedia\|item=2249\|entity\_type=node\|render=display\_mode\|display\_mode=image\]

Note that when the photon is in a superposition, it is neither in the lower or upper beam. But we if detect it, it will be in one or the other \(with equal probability in this example\).

A beamsplitter can also reverse the sign of the coefficient depending on the direction you come from. This is because a wave often get its amplitude reversed upon reflection so the state:

\lvert \psi \rangle=\frac{1}{\sqrt{2}}\lvert 0\rangle - \frac{1}{\sqrt{2}}\lvert 1\rangle&lt;/lrn-math&gt;

with a minus sign in the lower beam can also be created. In fact, by using two different beam splitters \(the one that gives a minus sign is labeled "-" in figure\) we will get destructive interference in the lower beam such that the detected photons will always be in the upper beam.

\[ciscode\|rev=1\|tool=elmsmedia\|item=2251\|entity\_type=node\|render=display\_mode\|display\_mode=image\]

