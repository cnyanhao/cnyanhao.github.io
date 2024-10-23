---
title: "Context-Aware Self-Adaptation for Domain Generalization"
collection: publications
permalink: /publication/2023-ICMLW
excerpt: 
illustration: /images/2023-ICMLW.png
date: 2023-05-28
venue: '2nd ICML Workshop on New Frontiers in Adversarial Machine Learning'
paperurl: 'https://openreview.net/pdf?id=BXn1jUXGQd'
citation: Hao Yan, Yuhong Guo. Context-Aware Self-Adaptation for Domain Generalization. In 2nd Workshop on New Frontiers in Adversarial Machine Learning at ICML 2023.
---
Domain generalization aims at developing suitable learning algorithms in source training domains such that the model learned can generalize well on a different unseen testing domain.
We present a novel two-stage approach called
Context-Aware Self-Adaptation (CASA) for domain generalization. CASA simulates an approximate meta-generalization scenario and incorporates a self-adaptation module to adjust pretrained meta-source models to the meta-target domains while maintaining their predictive capability on the meta-source domains. The core concept of self-adaptation involves leveraging contextual information, such as the mean of mini-batch
features, as domain knowledge to automatically
adapt a model trained in the first stage to new
contexts in the second stage. Lastly, we utilize an
ensemble of multiple meta-source models to perform inference on the testing domain. Experimental results demonstrate that our proposed method
achieves state-of-the-art performance on standard
benchmarks.