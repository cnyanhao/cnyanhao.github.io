---
title: "Context-Aware Self-Adaptation for Domain Generalization"
collection: publications
permalink: /publication/2023-ICMLW
excerpt: 
illustration: /images/2023-ICMLW.pdf
date: 2023-05-28
venue: 'ICML workshop'
paperurl: 'https://openreview.net/pdf?id=BXn1jUXGQd'
citation: Hao Yan, Yuhong Guo. Context-Aware Self-Adaptation for Domain Generalization. In 2nd Workshop on New Frontiers in Adversarial Machine Learning at ICML 2023.
---
Federated learning aims to tackle the “isolated data island” problem, where it
trains a collective model from physically isolated clients while safeguarding the
privacy of users’ data. However, supervised federated learning necessitates that
each client labels their data for training, which can be both time-consuming and
resource-intensive, and may even be impractical for edge devices. Moreover,
the training and transmission of deep models present challenges to the computation and communication capabilities of the clients. To address these two inherent challenges in supervised federated learning, we propose a novel lightweight
unsupervised federated learning approach that leverages unlabeled data on each
client to perform lightweight model training and communication by harnessing
pretrained vision-language models, such as CLIP. By capitalizing on the zero-shot
prediction capability and the well-trained image encoder of the pre-trained CLIP
model, we have carefully crafted an efficient and resilient self-training approach.
This method refines the initial zero-shot predicted pseudo-labels of unlabeled instances through the sole training of a linear classifier on top of the fixed image encoder. Additionally, to address data heterogeneity within each client, we propose
a class-balanced text feature sampling strategy for generating synthetic instances
in the feature space to support local training. Experiments are conducted on multiple benchmark datasets. The experimental results demonstrate that our proposed
method greatly enhances model performance in comparison to CLIP’s zero-shot
predictions and even outperforms supervised federated learning benchmark methods given limited computational and communication overhead.
