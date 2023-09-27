---
title: Opinion pooling on general agendas
tags: ooo

draft:
aliases:
- probabilistic aggregation
- linear pooling
- neutral pooling
- subjective probability
- opinion pooling
- probabilistic preference aggregation
date: '2023-09-15'
---
---
Franz Dietrich, Christian List
### Notes
- Problem of aggregating individual probabilities of an event into a collective probability whilst preserving probabilistic coherence.
- Provide _agenda[^1] characterisation_ for reasonable opinion pooling functions satisfying minimal conditions namely independence and conditional zero-preservation.
	- Traditionally $\sigma$-algebra are considered as agenda, but every event in it may not be realistically relevant. So, the authors relax this assumption to any general agenda $X$.
	- **Independence** is when the collective probability of $E \subset X$ depend only on individual probabilities.
	- **Conditional zero-preservation** says when everybody assigns zero conditional probability to an event then so is the conditional collective probability. (Implies the standard **zero-preservation** of probabilities.)

Main results of the paper are summarized in the chart below:
![[Pasted image 20230924132912.png]]


<!-- - Unions or intersections of every event in a $\sigma$-algebra may not always be realistically relevant, as well as, such artificial events need satisfy independence and conditional zero-preservation 
	- e.g. a group leader would reasonably consider what's concerning and priority than every imaginable action plan in the $\sigma$-algebra. -->

- See the paper for application on probabilistic preference[^2] aggregation with implications to avoid [[Arrow’s theorem in judgment aggregation|Arrow's dictatorship]] conclusion in this richer framework from the possibility that a linear pooling function would satisfy both independence and conditional zero-preservation.

[^1]: An agenda $X$, analogous to the one in [[Aggregating sets of judgements-An impossibility result|judgement]] aggregation, is the set of **only relevant events** i.e. $X \subseteq \Sigma$ where $\Sigma$ is a $\sigma$-algebra over states in $\Omega$. It is only required to be closed under complement and trivially non-empty.
[^2]: Preferences are fuzzy/vague or express agents' degree of belief about correct preference ordering.



> [!cite] Reference
> Dietrich, Franz, and Christian List. "Opinion pooling on general agendas." (2008).

