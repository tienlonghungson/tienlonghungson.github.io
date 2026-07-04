---
title: "Towards Fair Representation: Clustering and Consensus"
collection: publications
category: conferences
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025
venue: 'COLT 2025'
paperurl: 'https://arxiv.org/abs/2506.08673'
---
Consensus clustering, a fundamental task in machine learning and data analysis, aims to aggregate multiple input clusterings of a dataset, potentially based on different non-sensitive attributes, into a single clustering that best represents the collective structure of the data. In this work, we study this fundamental problem through the lens of fair clustering, as introduced by Chierichetti et al. [NeurIPS'17], which incorporates the disparate impact doctrine to ensure proportional representation of each protected group in the dataset within every cluster. Our objective is to find a consensus clustering that is not only representative but also fair with respect to specific protected attributes. To the best of our knowledge, we are the first to address this problem and provide a constant-factor approximation.

As part of our investigation, we examine how to minimally modify an existing clustering to enforce fairness -- an essential postprocessing step in many clustering applications that require fair representation. We develop an optimal algorithm for datasets with equal group representation and near-linear time constant factor approximation algorithms for more general scenarios with different proportions of two group sizes. We complement our approximation result by showing that the problem is \texttt{NP}-hard for two unequal-sized groups. Given the fundamental nature of this problem, we believe our results on Closest Fair Clustering could have broader implications for other clustering problems, particularly those for which no prior approximation guarantees exist for their fair variants.