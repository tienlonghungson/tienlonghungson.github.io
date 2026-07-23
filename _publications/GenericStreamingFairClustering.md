---
title: "A Generic Framework for Fair Consensus Clustering in Streams"
collection: publications
category: conferences
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2026-02-01
venue: '25th International Conference on Autonomous Agents and Multiagent Systems, AAMAS 2026 (Oral Presentation)'
paperurl: "https://dl.acm.org/doi/10.65109/TFHZ1924"
authors:
    - Diptarka Chakraborty
    - Kushagra Chatterjee
    - Debarati Das
    - Tien-Long Nguyen
arxiv_url: "https://arxiv.org/abs/2602.11500"
comments: ""
personal_comments: ""
---
Consensus clustering seeks to combine multiple clusterings of the same dataset, potentially derived by considering various non-sensitive attributes by different agents in a multi-agent environment, into a single partitioning that best reflects the overall structure of the underlying dataset. Recent work by Chakraborty et al. [COLT’25] introduced a fair variant under proportionate fairness and obtained a constant-factor approximation by naively selecting the best closest fair input clustering; however, their offline approach requires storing all input clusterings, which is prohibitively expensive for most large-scale applications.

In this paper, we initiate the study of fair consensus clustering in the streaming model, where input clusterings arrive sequentially and memory is limited. We design the first constant-factor algorithm that processes the stream while storing only a logarithmic number of inputs. 
En route, we introduce a new generic algorithmic framework that integrates closest fair clustering with cluster fitting, yielding improved approximation guarantees not only in the streaming setting but also when revisited offline.
Furthermore, the framework is fairness-agnostic: it applies to any fairness definition for which an approximately close fair clustering can be computed efficiently. Finally, we extend our methods to the more general $k$-median consensus clustering problem.
