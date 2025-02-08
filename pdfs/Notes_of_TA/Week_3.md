# Model of Single Neuron

Below, I will introduce 3 types of single neuron models, from the simple to the complex.

McCulloch-Pitts Model will be used in the Part 2 and Part 3 of the class, Integrate-and-Fire Model will be used in Part 1 and Part 3 and Hodgkin-Huxley Model will only be use in Part 1.

All in all, you must **master** (not just know) these 3 models during this course.

## McCulloch-Pitts Model

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230921104103895.png" alt="image-20230921104103895" style="zoom:50%;" />

<center>(figure from 《机器学习》周志华)</center>

$$
y = f(\sum_{i=1}^{n} w_i x_i - \theta) \\
where \ f(x) \ can \ be \ Heaviside \ or \ Sigmoid \ or \ ReLU
$$

M-P model is usually used everywhere in ML and DL, only seldom will they use Integrate-and-Fire Model. When they say they are going to simulate an SNN (Spiking Neural Network), mostly they use IF Model or its variant (see them in 吴思's BrainPy book). They almost never use HH Model because its computational expansivity.

M-P model is also used in Comp Neuro, like the head direction model by Haim Sompolinsky and Kechen Zhang. [(Ben-Yishai, 1995)](https://www.pnas.org/doi/abs/10.1073/pnas.92.9.3844) [(Kechen Zhang, 1996)](https://www.jneurosci.org/content/16/6/2112.short)



## Lapique-Lapique Model (Integrate-and-Fire Model)

Integrate-and-Fire Model was proposed by Louis Lapique and his wife (as he insisted), this is why I call it Lapique-Lapique Model.

All IF Models has 2 imposed equation:
$$
\left\{\begin{matrix}
V(t_{spike}^{-}) = V_{threshold}  &  & \\
V(t_{spike}^{+}) = V_{resting}  &  &
\end{matrix}\right.
$$


### Perfect IF Model

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230921105955743.png" alt="image-20230921105955743" style="zoom:33%;" />

Looking at its circuit diagram, you can easily write an ODE:
$$
C \frac{dV}{dt} = I(t)
$$

### Leaky IF Model

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230921110032718.png" alt="image-20230921110032718" style="zoom:33%;" />

Looking at its circuit diagram, you can easily write an ODE:
$$
C \frac{dV}{dt} = I(t) + (-g_L(V-E_L))
$$



### Variant

In this class, we will only use perfect IF and leaky IF.

But why always within the class? Why always wait the teacher to teach you? See adaptive, fractional derivative, exponential IF Model [here](https://en.wikipedia.org/wiki/Biological_neuron_model).




## Hodgkin-Huxley Model

I will call HH model the most beautiful model in neuroscience.

HH model is a biological plausible model, so, you need to know some biology knowledge about it.

### Physical Perspective

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230921111035344.png" alt="image-20230921111035344" style="zoom: 25%;" />

<center>(figure from Internet)</center>

In HH model, we use 3 additional ODEs to replace the 2 imposed eqs of IF model. And its first ODE is also gotten from its circuit diagram.

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230921111212173.png" alt="image-20230921111212173" style="zoom: 33%;" />

<center>(figure from Internet)</center>

There are a few things you need to think:

* What is the meaning of $\alpha$ and $\beta$ ?
* Why the exponent is $4, 3, 1$ for $n, m, h$ in the first ODE?



### Biological Perspective

There are a few things you need to know:

* How to calculate the $V_K$ and $V_{Na}$? (Sometimes they are called Nernst Equilibrium Potential)
* What are the concentration of $Na^{+}, K^{+}, Cl^{-}, Ca^{2+}$ inside the neuron and outside the neuron? How will they change during the action potential? How much will they change during the action potential?
* What does the $Na^{+}-K^{+} \ pump$ do in the action potential? Is it the same thing as the ion channel?



# THINK

Isaac Newton used mass-point-model when he studied the movement of the sun and the earth.

Charles-Augustin de Coulomb used charge-point-model when he studied the force of 2 small balls.

Mr. & Mrs. Lapique, Alan Hodgkin and Andrew Huxley used circuit diagram to model the neuron.

Do you think these three methods are from the same vein?	
