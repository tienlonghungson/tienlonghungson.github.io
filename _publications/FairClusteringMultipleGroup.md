---
title: "Generalizing fair clustering to multiple groups: algorithms and applications"
collection: publications
category: conferences
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2026
venue: 'AAAI 2026 (Oral Presentation)'
paperurl: 'https://arxiv.org/abs/2511.11539'
---
Clustering is a fundamental task in machine learning and data analysis, but it frequently fails to provide fair representation for various marginalized communities defined by multiple protected attributes -- a shortcoming often caused by biases in the training data. As a result, there is a growing need to enhance the fairness of clustering outcomes, ideally by making minimal modifications, possibly as a post-processing step after conventional clustering. A recent work initiated the study of \emph{closest fair clustering}, though in a restricted scenario where data points belong to only two groups. In practice, however, data points are typically characterized by many groups, reflecting diverse protected attributes such as age, ethnicity, gender, etc.

In this work, we generalize the study of the \emph{closest fair clustering} problem to settings with an arbitrary number (more than two) of groups. We begin by showing that the problem is NP-hard even when all groups are of equal size -- a stark contrast with the two-group case, for which an exact algorithm exists. Next, we propose near-linear time approximation algorithms that efficiently handle arbitrary-sized multiple groups.

Leveraging our closest fair clustering algorithms, we further achieve improved approximation guarantees for the \emph{fair correlation clustering} problem, advancing the state-of-the-art results. Additionally, we are the first to provide approximation algorithms for the \emph{fair consensus clustering} problem involving multiple (more than two) groups.
