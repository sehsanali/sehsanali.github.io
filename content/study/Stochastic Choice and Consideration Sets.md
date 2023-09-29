---
title: Stochastic Choice and Consideration Sets
tags:
- oo
- bulb
draft:
aliases: 
- stochastic choice and consideration sets
- consideration set
- stochastic choice
- random utility
date: '2023-09-17'
---
---
Paola Manzini, Marco Mariotti
### Notes
This paper presents a model of two-step choice process. First, a DM consider a subset of alternatives from a menu and then maximizes over that considered set of alternatives. The novelty is to assume a consideration set , for a menu  in the set of all alternatives . Notably the alternatives in  are stochastically determined, in that, any $a$ has a probability[^1] $\gamma(a) \in (0,1)$ to be in the consideration set. Then for primitives[^2] $(\succ, \gamma)$, a random consideration set choice rule is defined as: 

$$\quad \quad \quad \quad \quad p_{\succ, \gamma}(a, A) = \gamma(a) \prod_{b \in A: b \succ a}(1-\gamma(b)) \quad \forall A \in \mathcal{D}, \forall a \in A $$

where $p_{\succ, \gamma}(a, A)$ denotes the probability that $a$ is chosen when the individual faces choice in the menu $A$ along with some default option.

- This model can be seen as a special type of RUM[^3] which is compatible with choice reversals of a special kind. 

*Identification* of the primitives from observed choice data exploits the feature of  _impact_ in the model which measures change in probability when an alternative from the menu is removed. If removing an alternative increases the choice probability of another, it implies that the latter alternative must be ranked lower in the strict order $\succ$. 

> 💡 Forming consideration sets from learning and [[Memory and Probability|memory]]/experience?
> - Is stochastic consideration set necessary for stochastic choice? Are some alternatives permanently included in all the possible consideration sets due to learning and memory?

[^1]: Where $\gamma(a)$ is also termed attention parameter and importantly it is **fixed** even when alternatives are removed/added to the menu. See [[Attention Overload]] and [[Random Attention Model]] when alternatives and consideration sets are competing for attention.
[^2]: Where $\succ$ is strict total order on $X$, and $\gamma : X \rightarrow (0,1)$.
[^3]: Random utility maximization.

> [!cite] Reference
> Manzini, Paola, and Marco Mariotti. "Stochastic choice and consideration sets." _Econometrica_ 82, no. 3 (2014): 1153-1176.

