# Introduction

In the last two lectures, we discussed encoding. Today, we will talk about decoding. Here, encoding refers to how animals use neurons to represent external information (including vision, hearing, smell, taste, touch, and pain, although we only covered vision in our lectures). Decoding refers to how information from neurons is reconstructed into external information.

First, it's important to note: scientists need to decode, Elon Musk's Neuralink needs to decode, but animals may not necessarily need to decode. At least, there is no conclusive evidence yet that animals must decode.

In one experimental paradigm, scientists show monkeys some dots.

Today's lecture will only cover this paradigm.

What we discuss does not go beyond Chapter 3 of Peter Dayan's book.



# Moving Dots Experiment

## Definition of Coherence

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231019101433018.png" alt="image-20231019101433018" style="zoom:50%;" />

## A single neuron?

You have to find the right neuron. 

Professor Wen mentioned in the lecture that a single neuron can achieve the level of population coding, but this comes with a prerequisite: you must find the right single neuron. An experiment in 1992 recorded the activity of a neuron in the MT (middle temporal) area. Obviously, if you record a neuron from a brain area that has nothing to do with vision, you won't see this effect.



## Two-alternative force-choice

The experiment conducted in 1992 utilized a two-alternative forced-choice (2AFC) experimental paradigm. In such cases, we can make some mathematical derivations, as seen in Sections 3.1 and 3.2 of Peter Dayan's book.



## $\alpha$ and $\beta$

The concepts of $\alpha$ and $\beta$ originate from hypothesis testing and are frequently used tools in computational neuroscience and machine learning.

$\alpha$, often referred to as the significance level, is the probability of rejecting the null hypothesis when it is true (Type I error). $\beta$, on the other hand, is the probability of failing to reject the null hypothesis when it is false (Type II error).

Remember:
$$
\alpha := P(reject \ H_0|H_0) = P(current \ or \ more \ extreme \ data|H_0) = p-value
$$


## Receiver Operating Characteristic

ROC说白了无非就是$\beta \sim \alpha$的这张图，计算神经科学和ML也都经常使用此工具。

<img src="C:\Users\11097\AppData\Roaming\Typora\typora-user-images\image-20231019115501417.png" alt="image-20231019115501417" style="zoom:50%;" />

在理想情况下，ROC下的面积为1

在瞎选情况下，ROC下的面积为0.5




## d

我们定义了$d = \frac{<r_{+}> - <r->}{\sigma}$来区分两个峰是否能够分开，这种思想和物理上的Rayleigh Criterion是师出同源的。



# Answer some questions

## Q1: Why do you think the two $\sigma$ are equal?

Answer: You can calculate the standard deviation of the experimental data. If there is a significant difference, you should use different $\sigma$ to model it. If the difference is small, you can use the same $\sigma$.



## Q2: What is Noise Correlation?

Answer: To deeply understand, you need to manually work through the formulas in Sections 3.1 and 3.2 of Peter Dayan's book. You will find that Noise Correlation is just one term in the equation.
