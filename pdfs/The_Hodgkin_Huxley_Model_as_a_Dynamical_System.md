# Outline

* HH Model Revisited
* Nonlinear Dynamics in HH Model



# HH Model Revisited

## Introduction

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230921111035344.png" alt="image-20230921111035344" style="zoom: 25%;" />

<center>(figure from Internet)</center>

In HH model, we use 3 additional ODEs to replace the 2 imposed eqs of IF model. And its first ODE is also gotten from its circuit diagram.

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230921111212173.png" alt="image-20230921111212173" style="zoom: 33%;" />

<center>(figure from Internet)</center>



## Physical Perspective

* What is the meaning of $\alpha$ and $\beta$ ?
  * Transition probability in the 2 state Markov chain.

* Why the exponent is $4, 3, 1$ for $n, m, h$ in the first ODE?
  * They come from fitting the experiment data.




## Biological Perspective

There are a few things you need to know:

* How to calculate the $V_K$ and $V_{Na}$? (Sometimes they are called Nernst Equilibrium Potential)
  * Method 1: using diffusion equation
    * ![image-20231006165705010](C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006165705010.png)
  * Method 2: using Boltzmann distribution

* What is the quantity of Nernst Equilibrium Potential of typical ions?

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006165440910.png" alt="image-20231006165440910" style="zoom:50%;" />

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006170431865.png" alt="image-20231006170431865" style="zoom:50%;" />

* What are the concentration of $Na^{+}, K^{+}, Cl^{-}, Ca^{2+}$ inside the neuron and outside the neuron?
  * see above.
* How much will they change during the action potential?
  * $K^{+}$
    * <img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006173130671.png" alt="image-20231006173130671" style="zoom:50%;" />
  
  * $Ca^{2+}$: ???
  


* What does the $Na^{+}-K^{+} \ pump$ do in the action potential? Is it the same thing as the ion channel?
  * hyper-polarization.
  * no.
* 3 ways for $Na^{+}, K^{+}$ to pass the membrane
  * leaky
  * ion channel
  * ion exchanger/ion pump
* Why HH only used $Na^{+}$ and $K^{+}$?

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006174553649.png" alt="image-20231006174553649" style="zoom:50%;" />

<center>(Figure 12.7 of <i> Biological Physics </i>)</center>

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006174821839.png" alt="image-20231006174821839" style="zoom: 33%;" />

left panel: an axon filled with potassium sulfate solution. 

right panel: an normal axon.

<center>(Figure 12.13 of <i> Biological Physics </i>)</center>



# Nonlinear Dynamics in HH Model

## Introduction

Eg1: harmonic oscillator

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006185341460.png" alt="image-20231006185341460" style="zoom:33%;" />

Eg2: simple pendulum

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006190056728.png" alt="image-20231006190056728" style="zoom:33%;" />

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006184442605.png" alt="image-20231006184442605" style="zoom:50%;" />

## Fixed Point

* nullcline
* vector field


## Limit Cycle

* Poincare-Bendixson TH

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231006192837264.png" alt="image-20231006192837264" style="zoom:50%;" />



