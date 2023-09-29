---
date: 2023-09-11
title: "Aggregating sets of judgements: An impossibility result"
tags:
  - ooo
  - bulb
aliases:
  - impossibility
  - consistent
  - deductive closure
  - propositional
  - majoritarian
  - collective rationality
  - discursive
  - doctrinal
  - dilemma
  - paradox
  - judgement
  - universal domain
  - anonymity
  - systematicity
  - judgement aggregation function
  - aggregation
draft:
---

---
Christian List, Philip Pettit
### Notes
- Judgment is binary on propositions $\phi$ in the agenda $X$.
- Rationality constraints on the set of judgements (personal or collective) $\Phi \subseteq X$:
	- Completeness: $\forall \phi \in X  \Rightarrow (\phi \in \Phi) \vee (\neg \phi \in \Phi)$
	- Consistency: $\nexists \phi \in \Phi$ such that $(\phi \in \Phi) \wedge (\neg \phi \in \Phi)$ 
	- Deductive closure: $\forall \phi \in \Phi$, if $\phi \Rightarrow \psi \in X$ then $\psi \in \Phi$
- Judgement aggregation function $F: \mathcal{P}(X^n) \rightarrow \mathcal{P}(X)$ maps profile of personal judgements $\{ \Phi_i \}_{i \in N}$, where $\Phi_i \subseteq X$, to a collective set of judgements $\Phi \subseteq X$. 
	- If domain is all possible profiles of complete, consistent and deductively closed personal set of judgements then $F$ satisfies Universal Domain.
	- If $F$ is unique up-to permutations of personal sets of judgements $\Phi_i$ then it satisfies Anonymity.
	- If $F$ treats all propositions in an even-handed way (i.e. independence and neutrality of individual judgements) then it satisfies Systematicity.


>[!info] Impossibility result
> No judgement aggregation function generates a complete, consistent and deductively closed set of collective judgements which satisfies universal domain, anonymity and systematicity. 

Importantly, Arrow's preference aggregation can be seen as a [[Arrow’s theorem in judgment aggregation|special case of judgement aggregation]] when preferences are expressed as propositions of the form, $x$ is _strictly_ preferable to $y$. There are contributions towards generalizing aggregation of various propositional attitudes (e.g preferences, judgement, [[Opinion pooling on general agendas|subjective probabilities]]) in a [[The aggregation of propositional attitudes-towards a general theory|unified framework]]. 

> 💡 Aggregation rules under [[Stochastic Choice and Consideration Sets|stochastic choice and consideration sets]]?

> [!cite] Reference
> List, Christian, and Philip Pettit. "Aggregating sets of judgments: An impossibility result." _Economics & Philosophy_ 18.1 (2002): 89-110.