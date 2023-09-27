---
title: Random Attention Model
tags:
- oo
draft:
aliases:
- limited attention
- stochastic
- revealed preference
- attention overload
- RAM
date: '2023-09-18'
---
---
Matias D. Cattaneo, Xinwei Ma, Yusufcan Masatlioglu, Elchin Suleymanov
### Notes

The key contribution of this paper, besides formulating econometric methods for identification, estimation and inference of a revealed preference theory, is the introduction of assumption of monotonic attention rule in the theoretical model of _two-step decision process_. This assumption relies on the intuitive idea of consideration sets competing for DM's[^1] attention i.e. $\forall a \in S \setminus T$, $\mu(T|S) \leq \mu(T|S \setminus \{a\})$ where $T \subseteq S$ is a consideration set in some choice problem (or menu) $S$. In other words, removing an alternative outside of a consideration set $T$ weakly increases the probability of paying attention to $T$. Moreover, $\mu(\cdot|S)$ here is the attention rule that assigns some frequency to each possible consideration set $T \subseteq S$ such that they add up to one. This formulation is different than the one in [[Stochastic Choice and Consideration Sets|stochastic choice and consideration sets]] where a fixed attention parameter gave some positive probability for each element of $S$ to be in the only consideration set $C(S)$.

Below is the illustration of RAM[^2], reproduced from the original paper.
![[Pasted image 20230925150631.png]]


- RAM nests most random limited attention models but not [[Attention Overload|AOM]]. 
- Encompasses non-parametric attention rules.
- Monotonic attention assumption allows for a partial identification of the primitives of the model from choice data.


[^1]: Acronym widely used in this website for a decision maker.
[^2]: Random Attention Model.

> [!cite] Reference
> Cattaneo Matias D., Xinwei Ma, Yusufcan Masatlioglu, and Elchin Suleymanov. "A random attention model." _Journal of Political Economy_ 128, no. 7 (2020): 2796-2836.

