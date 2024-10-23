---
title: "Lightweight Unsupervised Federated Learning with Pretrained Vision Language Model"
collection: publications
permalink: /publication/2024-IJCAIW
excerpt: 
illustration: /images/2024-IJCAIW.pdf
date: 2024-08-05
venue: 'IJCAIW'
paperurl: 'https://arxiv.org/pdf/2404.11046'
citation: Hao Yan, Yuhong Guo. Lightweight Unsupervised Federated Learning with Pretrained Vision Language Model. International Workshop on Federated Learning in the Age of Foundation Models at IJCAI 2024.
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
