# The Debate between Cajal and Golgi: the Start of Neuroscience

Golgi: axons form a big net. (A)

Cajal: axons belongs to each neuron. (B)

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907112410014.png" alt="image-20230907112410014" style="zoom: 33%;" />

<center>(figure from class slides)</center>

PS: Golgi didn't mean neurons form a big net, he meant axons form a big net.

PPS: in recent years, jellyfish's axons are found to be like Golgi's theory.



# Outline

Here, you already know the basic structure of a neuron. Below we will talk about the brain through a top-down approach, which is adapted from CH1-CH3 of *Principles of Neural Design*.

* Why do we need a brain?
* Why do we need columns (similar neurons located together)?
* Why do we need axons and dendrites?



# Why Do We Need a Brain?

## E.coli

E.coli has no brain, but it can do biased random walk and it has memory. (This is real memory! not like "memory" of Hopfield Network)

But no brain has some drawbacks:

* only very short memory
* can't sense more chemicals
* can't control motor more precisely

## C.elegans

### motor

100 muscles, distributed evenly, generating oscillations.

This oscillation needs a brain.

This oscillation is preserve in many animals. Walk, run is also generated by oscillations.

### sensory

They can sense much more things than E.coli or other no-brain-creature, including T, light, chemistry compounds.

### PS: some design aspects of their brains

* each single neuron is important
* chemistry > electrical
* favor analogue over digital: digital signals need more energy.
* use stereotype things: they don't want to reinvent wheels too.



## Why Do We Need a Bigger Brain?

see CH3 of *Principles of Neural Design*



# Why Do We Need Columns?

## Minimize Wire

compute locally if you can?

neurons that fire together should locate together?

Some scientists believe these two statements.

Personally, I am not sure, although we have some evidence:



## eg1: Map of Penfield (human cortex)

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230914101639914.png" alt="image-20230914101639914" style="zoom: 50%;" />

<center>(figure from class slides)</center>

This map is first discovered by [Wilder Penfield](https://en.wikipedia.org/wiki/Wilder_Penfield).



## eg2: Map of Hubel and Wiesel (cat V1)

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230914101800690.png" alt="image-20230914101800690" style="zoom:50%;" />

<center>(figure from class slides)</center>

## eg3: Map of Hubel and Wiesel (Column)

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230914102159438.png" alt="image-20230914102159438" style="zoom:50%;" />

<center>(figure from class slides)</center>

## eg4: uniform distribution vs Gaussian distribution

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230914103006720.png" alt="image-20230914103006720" style="zoom:50%;" />

<center>(figure from class slides)</center>

It will to a homework to discuss that which is better, uniform distribution (salt-and-pepper) or Gaussian distribution (pin-wheel).



# Why Do We Need Axons and Dendrites?

Cajal thought that the neurons, the brain can save time, space, and material.

Alan Turing also had similar opinions.

We make 2 assumption

* every 2 neuron must have connection
* minimize the wire

We will see, under the 2 assumptions, we can get results that are in line with reality, so these 2 assumptions are reasonable. If not, we must change our assumptions. (This approach is similar to Newton's, Maxwell's and Schrodinger's).



Under these 2 assumptions, we can make 4 designs

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230914111621522.png" alt="image-20230914111621522" style="zoom: 50%;" />

<center>(figure adapted from <a href="https://www.cell.com/fulltext/S0896-6273(04)00498-2"> Chklovskii, 2004 </a>)</center>



# Think

## Is it right to think brain as being designed?

Personally, I think it is not right, although it can give us some ideas and insights for designing an artificial neural network.

The brain is not designed, it just evolved.

This is like "能存活的生物不是最聪明的，也不是最强壮的，也不是最节能的，而是最适合环境的。"

It is true that more clever, strong, efficient creatures are more likely to survive, but not always the case.

Quote from Francis Crick

>Biologists must constantly keep in mind that what they see was not designed, but rather evolved. It might be thought, therefore, that evolutionary arguments would play a large part in guiding biological research, but this is far from the case. It is difficult enough to study what is happening now. To try to figure out exactly what happened in evolution is even more difficult. Thus evolutionary arguments can usefully be used as hints to suggest possible lines of research, but it is highly dangerous to trust them too much. It is all too easy to make mistaken inferences unless the process involved is already very well understood.



## Is it right to use Occam’s Razor in biology?

Personally, I think it is not right.

Unlike the above question, we have some experimental evidences indicating that the brain has a lot redundancy, which means that Occam’s Razor is wrong in biology.

Quote from Francis Crick

> While Occam’s razor is a useful tool in the physical sciences, it can be a very dangerous implement in biology. It is thus very rash to use simplicity and elegance as a guide in biological research. While DNA could be claimed to be both simple and elegant, it must be remembered that DNA almost certainly originated fairly close to the origin of life when things were necessarily simple or they could not have got going.