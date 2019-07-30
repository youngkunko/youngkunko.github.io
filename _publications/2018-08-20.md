---
title: "Semi-Direct Sum Theorem and Nearest Neighbor under l infinity"
collection: publications
permalink: /publication/2018-08-20
excerpt: 'with [Mark Braverman](http://www.cs.princeton.edu/~mbraverm/pmwiki/index.php?n=Site.Main?setview=display)'
date: 2018-08-20
venue: 'APPROX/RANDOM 2018'
paperurl: 'https://doi.org/10.4230/LIPIcs.APPROX-RANDOM.2018.6'
---

[Download paper here](https://doi.org/10.4230/LIPIcs.APPROX-RANDOM.2018.6)

We introduce semi-direct sum theorem as a framework for proving asymmetric communication lower bounds for the functions of the form $\bigvee_{i=1}^n f(x,y_i)$. Utilizing tools developed in proving direct sum theorem for information complexity, we show that if the function is of the form $\bigvee_{i=1}^n f(x,y_i)$ where Alice is given $x$ and Bob is given $y_i$'s, it suffices to prove a lower bound for a single $f(x,y_i)$. This opens a new avenue of attack other than the conventional combinatorial technique (i.e. ``richness lemma'' from [Miltersen1995]) for proving randomized lower bounds for asymmetric communication for functions of such form.

As the main technical result and an application of semi-direct sum framework, we prove an information lower bound on  $c$-approximate Nearest Neighbor (ANN) under $\ell_\infty$ which implies that the algorithm of [Indyk2001] for $c$-approximate Nearest Neighbor under $\ell_\infty$ is optimal even under randomization for both decision tree and cell probe data structure model (under certain parameter assumption for the latter). In particular, this shows that randomization cannot improve  [Indyk2001] under decision tree model. Previously only a deterministic lower bound was known by \cite{andoni2008hardness} and randomized lower bound for cell probe model by [Kapralov2012nns]. We suspect further applications of our framework in exhibiting randomized asymmetric communication lower bounds for big data applications.
