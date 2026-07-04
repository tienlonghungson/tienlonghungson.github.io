---
title: "A Scalable and Unified Framework to Weighted Rank Aggregation"
collection: publications
category: conferences
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2026-04-20
venue: 'ICALP 2026'
paperurl: 'https://arxiv.org/html/2605.09653v1'
---
 The rank aggregation problem, seeks to combine multiple rank orderings of the same set of candidates into a single consensus ordering. Such problems arise in diverse domains, including web search, employment, college admissions, and voting. 
In this work we focus on the 1-median objective: given a set of $m$ rankings over $[n]$, the goal is to compute a ranking that minimizes the sum of its distances to all input rankings.
 
We study rank aggregation under several classical distance metrics: Ulam distance, Spearman’s footrule, Hamming distance, and Kendall-tau, as well as their weighted variants. Our contributions begin with a novel unified framework that identifies a key structural property: it suffices to focus on a small subset of rankings (of size three or five), where the corresponding local one-median provides a good approximation to the global median. This principle extends across these distance measures, yielding a general algorithmic framework for weighted rank aggregation.

Building on this, we present a new approximation algorithm for rank aggregation under the Ulam distance that scales in the Massively Parallel Computation (MPC) model. Our algorithm computes a $(2-\alpha)$-approximation, for a constant $\alpha>0$, to the $1$-median in a constant number of rounds, using local memory sublinear in $n$ (the size of a ranking) and total memory near linear in $n$.


We further design new MPC approximation algorithms for Spearman's footrule and for the \emph{element-weighted} variants of Hamming and Kendall-tau distances. For each metric, we obtain a $(2-\zeta)$-approximation, for a constant $\zeta>0$ (which may differ across metrics), to the $1$-median in a constant number of rounds, using local memory sublinear in $n$ and total memory linear or near-linear in $n$.


Moreover, for the Ulam distance, where computing the $1$-median is NP-hard 
[Fischer et al., ESA, 2025], we simplify and strengthen the analysis of Chakraborty et al. [ITCS 2023], obtaining an improved $1.968$-approximation 
that further extends to the weighted setting. 

