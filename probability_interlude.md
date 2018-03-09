To understand how photons behave, we need to take a pause and talk about probability.

Imagine the following situation: You are blindfolded and throwing darts at a dartboard as shown in the image below. You roughly know where the dartboard is and most of your shots are near the center. After a 100 shots, you get this pattern (see fig):

[ciscode|rev=1|tool=elmsmedia|item=2237|entity_type=node|render=display_mode|display_mode=image__left]

<iframe src="https://h5p.org/h5p/embed/88836" width="1090" height="319" frameborder="0" allowfullscreen="allowfullscreen"></iframe><script src="https://h5p.org/sites/all/modules/h5p/library/js/h5p-resizer.js" charset="UTF-8"></script>

## Defining Probability

Because 45 out of 100 throws ended up in region A, we could say that the chance of hitting region A is 45%. In general we can say that the probability of hitting region A is just the number of hits in A divided by the total.

<lrn-math>P_A = \frac{N_A}{N_{tot}}</lrn-math>

This probability is more and more accurate as the total number of throws gets really large. Similarly, we can define the probability of throwing in region B and C (<lrn-math>P_B</lrn-math> and <lrn-math>P_C</lrn-math>) by counting the number of throws in region B or C (<lrn-math>N_B</lrn-math> or <lrn-math>N_C</lrn-math>) and dividing it by the total number of throws (<lrn-math>N_{TOT}</lrn-math>). The bigger the total number of throws, the more accurate the probability becomes.

## The Word OR

Let's say you want to know the probability that the dart was in region A **OR** region B. What do you do?

Since it does not matter which one, you just count all throws that landed in A or B.

<lrn-math>P_{A\; or \; B} = \frac{N_A + N_B}{N_{tot}} = P_A+P_B</lrn-math>

So, the probability of hitting A or B is the sum of the probability of hitting A and probability of hitting B. So in our example this would be 35% + 45% = 80%.

Note that the chance of hitting anything at all (A OR B OR C) should be 1 or 100%.

<lrn-math>P_A+P_B+P_C =1</lrn-math>

> As we will see, quantum mechanics is special when it comes to adding probability because of interference which happens.

> Note: A probability must be a pure number (no units) between 0 (impossible) and 1 (certain). Often the number is represented as a percentage or as a fraction. For example a probability of p = 0.25 can be represented as 25% ,25/100 or as 1/4. One chance out of 4 is a probability p=0.25.