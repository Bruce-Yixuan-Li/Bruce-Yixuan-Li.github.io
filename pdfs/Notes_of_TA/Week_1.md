# 2 Books

*Theoretical Neuroscience*: How questions?

* How to generate spikes as a single neuron?
* How to build SNN?

*Principles of Neural Design*: Why questions?

* Why do we have a brain?
* Why do we have a bigger brain?
* Why do we have different neuron types?

# History Before 1988

[Sejnowski et al., 1988](https://www.science.org/doi/abs/10.1126/science.3045969): a famous review paper by 3 notable scientists. 

In 2022 Fall, we covered 8 topics of these 10: except for cable theory and Wilson-Cowan model. You can read these on *Theoretical Neuroscience*

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907101612717.png" alt="image-20230907101612717" style="zoom: 50%;" />

<center>(figure from class slides)</center>

There has been a lot progress after 1988.

In exactly 1988, Hinton and colleagues developed error-back-propagation.

# Principles/Axioms of Neuroscience?

In physics, we always have some principles, like Newton-3-laws, thermodynamics-3-laws, Maxwell equations, Schrodinger equation, equal probability principle.

But in biology, we don't have such things. Maybe the only thing can be called principle in biology is Darwin's **Nature Selection**.

# Goals of Neuroscience?

1. Understand how the brain works
2. Inspire AI

# More Is Different

[*More Is Different: Broken symmetry and the nature of the hierarchical structure of science*](https://www.science.org/doi/abs/10.1126/science.177.4047.393): a famous paper by Philip Anderson in 1972

This "More Is Different" thing also plays important role in Neuroscience.

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907101810314.png" alt="image-20230907101810314" style="zoom: 33%;" />

<center>(figure from class slides)</center>

# David Marr vs Henry Markram

## Marr

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907102613835.png" alt="image-20230907102613835" style="zoom: 33%;" />

<center>(figure from Vision)</center>

In the past, algorithm needs a lot math. But now, just 炼丹。

## Markram

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907102855583.png" alt="image-20230907102855583" style="zoom: 33%;" />

This approach **succeeds** in physics (mechanics, thermodynamics, electrodynamics), but it **seems** to fail in neuroscience. 

> Think about the AlexNet, the ResNet or the transformer. You know every connection between each pair of artificial neurons. But can you tell me how the transformer works?



PS: In 2009, Henry Markram claimed that he could build human brain in ten years. But he failed, along with the blue brain project. Blue Brain Project and Human Brain Project were highly related to each other and both got a lot of criticism. See [this paper](https://www.nature.com/articles/513027a) for the controversy.



## Think

A friend of mine said that: both Marr's and Markram's theory has the biggest difficulty from the 2nd level to the 3rd level (from algorithm to hardware and from cell to system), do you agree with him?



# Example: Vision of Fruit-fly

## An experiment

[Original paper](https://journals.biologists.com/jeb/article/210/18/3218/17032/The-spatial-temporal-and-contrast-properties-of) in 2007.

PS: we want to use dragon-fly one day!

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907104046440.png" alt="image-20230907104046440" style="zoom:50%;" />

The stimulus is:
$$
s(t) = sin(wt-kx)
$$
The response is wing beat.

The response-stimulus plot is:

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907104412591.png" alt="image-20230907104412591" style="zoom:50%;" />

## A theory 

[Original paper](https://www.degruyter.com/document/doi/10.1515/znb-1956-9-1004/html) in 1956.

Attention: this model is for 2 near photo receptors in the retina, not for left eye and right eye!!!  

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907213604984.png" alt="image-20230907213604984" style="zoom:50%;" />

Use ReLU instead of multiplication.

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907213710611.png" alt="image-20230907213710611" style="zoom:50%;" />



## Open the black box

Try to open the black box in Drosophila.

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20230907111313418.png" alt="image-20230907111313418" style="zoom:50%;" />

## Think

**Does this example have David Marr's 3 levels?**
