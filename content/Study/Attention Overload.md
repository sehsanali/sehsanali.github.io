---
title: Attention Overload
tags:
- ooo
draft:
aliases:
- limited attention
- stochastic
- revealed preference
- attention overload
date: '2023-09-19'
---
---
Matias D. Cattaneo, Paul Cheung, Xinwei Ma, Yusufcan Masatlioglu

### Notes
The novelty of attention overload model for modelling two-step choice process--first paying attention to a consideration set and then maximizing over it-- with random and limited attention is by assuming _attention overload_ where the alternatives/options compete for the attention of the DM. Graphically it is depicted below.
![[Pasted image 20230925154835.png]]where $\phi(a|S)$ is the probability that $a$ "attracts" attention in $S$ and is defined as 


$$  \quad \quad \quad \quad \quad \quad \quad \quad \quad \quad  \phi_\mu (a |S) := \sum_{T \subseteq S: a \in T} \mu(T|S)$$


and $\mu(T|S)$ represents the probability of paying attention to some consideration set $T \subseteq S$ when the menu is $S$.

- The model in [[Stochastic Choice and Consideration Sets]] is a special type of AOM with fixed attention rule $\gamma(a)$ for all $a$ which is menu independent. (Observe the weak inequality in the figure above)

See the paper for econometric details of (partial) identification of the model.



> [!cite] Reference
> Cattaneo Matias D., Paul Cheung, Xinwei Ma, and Yusufcan Masatlioglu. "Attention Overload." _arXiv preprint arXiv:2110.10650_ (2021).

