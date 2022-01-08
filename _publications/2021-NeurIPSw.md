---
title: "Augmented Self-Labeling for Source-Free Unsupervised Domain Adaptation"
collection: publications
permalink: /publication/2021-NeurIPSw
expert: 
# illustration: /images/2021-NeurIPSw.png
date: 2021-09-01
venue: 'NeurIPS Workshop on Distribution Shifts'
paperurl: 'https://openreview.net/pdf?id=c_XaCsX3gtA'
citation: 'Hao Yan, Yuhong Guo, Chunsheng Yang. Augmented Self-Labeling for Source-Free Unsupervised Domain Adaptation. NeurIPS 2021 Workshop on Distribution Shifts'
---
Unsupervised domain adaptation aims to learn a prediction model that generalizes
well on a target domain given labeled source data and unlabeled target data. However, source data sometimes can be unavailable due to data privacy or decentralized
learning architectures. In this paper, we address the source-free unsupervised
domain adaptation problem where only the pretrained source model and unlabeled
target data are given. To this end, we propose an Augmented Self-Labeling (ASL)
method that jointly optimizes the prediction model and the pseudo-labels for the
target data starting from the initial source model. It involves two alternating steps:
augmented self-labeling improves pseudo-labels by solving an optimal transport
problem with the Sinkhorn-Knopp algorithm, and model re-training trains the
model with the supervision of improved pseudo-labels. We further introduce model
regularization terms to improve the model re-training. Experiments show that our
method achieves comparable or better results than the state-of-the-art methods on
the standard benchmarks.

[Download paper here](https://openreview.net/pdf?id=c_XaCsX3gtA)
