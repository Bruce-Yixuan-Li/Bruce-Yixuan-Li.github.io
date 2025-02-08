# Meaning of n, m, h

$$
g_{K+} = P \bar{g_{K+}}
$$

Here, $P$ is probability.

In HH model, $n, m, h$ are all probability, their range is $[0,1]$.



# ODE of n, m, h

$$
\frac{dn}{dt} = \alpha(V) (1-n) - \beta(V) n
$$

See open and close as 2 states in a Markov Chain, and $\alpha(V), \beta(V)$ are transfer probability.



## Resting State

When $\frac{dn}{dt} = 0$, $n = \frac{\alpha_n}{\alpha_n + \beta_n}$, denote it as $n_{\infty}$

Denote $\tau_n = \frac{1}{\alpha_n + \beta_n}$, we'll get
$$
\tau_n \frac{dn}{dt} = - n + n_{\infty}(V)
$$


## How to Get $\alpha$ and $\beta$ ?

Go back to experiments, HH found that the plot of $n_{\infty} \sim V$ was very like sigmoid.

So they use this function to model (This is straightforward that the don't use [other sigmoid function](https://en.wikipedia.org/wiki/Sigmoid_function), think of Boltzmann distribution!)
$$
n_{\infty} = \frac{1}{1+e^{F_0 - \beta V}}
$$
From $n_{\infty}$, you can get $\alpha$ and $\beta$.



## Exponent of n, m, h

 The plot of $n_{\infty} \sim V$ is more up-and-left in experiments.

They use exponent to model (This is not so straightforward like above).

They choose 4 for n, 3 for m, 1 for h.

In 1998, structure biologists found that each potassium channel is consist of 4 sub-modules and it will open if and only if all 4 sub-modules are open~



# Ion channels

In HH's paper, they only consider sodium and potassium.

Nowadays, some researchers consider more than 10 type of ions, including calcium and chloride.

By the way, C.elegans have potassium, calcium and chloride, but no sodium!