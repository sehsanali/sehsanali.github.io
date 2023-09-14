---
title: "Aggregating sets of judgements: An impossibility result"
tags:
  - ooo
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
draft: "false"
---

---
Christian List, Philip Pettit

### Abstract
Suppose that the members of a certain group each hold a rational set of judgments on some interconnected questions. And imagine that the group itself now has to form a collective, rational set of judgments on those questions. How should it go about dealing with this task? We argue that the question raised is subject to a difficulty that has recently been noticed in discussion of the doctrinal paradox in jurisprudence. And we show that there is a general impossibility theorem that that difficulty illustrates. Our paper describes this impossibility result and provides an exploration of its significance. The result naturally invites comparison with Kenneth Arrow's famous theorem (Arrow, 1963 and 1984; Sen, 1970) and we elaborate that comparison in a companion paper (List and Pettit, 2002). 

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
> Under the minimal assumptions of Universal Domain, Anonymity and Systematicity there does not exist a judgement aggregation function which is complete, consistent and deductively closed.

Importantly, Arrow's impossibility theorem can be seen as a special case of Judgement impossibility result when preferences are expressed as propositions of the form: $x$ is preferable to $y$.

>[!question] Questions 
> - Preference aggregation under limited attention?




> [!cite] Reference
> List, Christian, and Philip Pettit. "Aggregating sets of judgments: An impossibility result." _Economics & Philosophy_ 18.1 (2002): 89-110.

