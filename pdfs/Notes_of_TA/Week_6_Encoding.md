# Sensory Neuron in Visual System

We will use visual system to talk about encoding.

We want to investigate the sensory neuron, like Hubel and Wiesel in 1970s.

We will present some stimulus and see the response.

One of the most simple stimulus is white noise. (PS: white noise can be any distribution, i.e., can be Gaussian or not. I will talk about it from the point of stochastic process in the TA class).

We ask 2 questions:

* Q1: What does the stimulus before the spike of a sensory neuron look like?
* Q2: Can we predict the response of a sensory neuron?



# Answer Q1: The Stimulus Before the Spike

See Peter's book.




# Answer Q2

## Functional Derivative

Why using functional derivative? We just want to investigate sensory neurons.

If $r[s(t)] = s(t)$, then...



## Calculate Derivative

Just like what we do in physics and ML.



## Finally

If we present white noise $s(t)$ with variance of $\sigma^2$, we just need to measure $r(t)$ and calculate $\frac{Q_{rs}(-\tau)}{\sigma^2}$, it will be the optimal kernel.

After that, when we present a new stimulus $s_{new}(t)$, we can calculate $ r_{new-predicted} (t)$ for it.



# D in visual system

* Earlier than Yann LeCun?
  * yes
* Do we have translational invariant $D$ of biological neurons?
  * yes
* D of retinal ganglion cell
  * use the exp data to fit the parameters.
  * you can also use other function besides the Mexican hat.
* D of simple cell in V1
  * $exp \cdot cos$
  * first layer of CNN like this, black-white-black..., oriented (still a puzzle)



# Use constant stimulus

integral of D should be 0.



# THINK

* Do we have figs of $r(t)$ vs $r_{est}(t)$
* Seems this $D$ only works for white noise. i.e. we can only use it to predict $r$ for white noise $s$



# From Linear to Non-linear

Method 1: add an activation function. (the same vain as in DL)

Method 2: use more terms in Wiener Series.
