---
title: "Curriculum Learning"
excerpt: "Short description of portfolio item number 1"
collection: portfolio
permalink: /portfolio/portfolio-1
---

In a typical educational system, learning relies on a **curriculum** that introduces new concepts building upon previously acquired ones. The rationale behind, is that humans and animals learn better when information is presented in a meaningful way rather than randomly. We follow this starting small concept to design our approaches with convolutional neural networks for medical image classification tasks.

In our novel formulation we reunite three **curriculum learning strategies**: individually **weighting** training samples, **reordering** the training set, and **sampling subsets** of data into a **data scheduler**. The core of these strategies is a **scoring function** ranking the training samples. We define two novel scoring functions: one from **domain-specific prior knowledge** and an original **self-paced uncertainty score**. 

Another approach to deal with class-imbalance and restricted-size datasets is to join forces across multiple institutions. Recently, **federated learning** has emerged as an effective tool for collaborative learning. In this setting, local models perform computation on their private data to update the global model. The order and the frequency of local updates influence the final global model. Hence, the order in which samples are locally presented to the optimizers plays an important role. In this work, we define a **memory-aware curriculum learning method for the federated setting**. Our curriculum controls the order of the training samples paying special **attention to those that are forgotten after the deployment of the global model**. Our approach is **combined with unsupervised domain adaptation** to deal with domain shift while preserving data privacy.   

## Publications
**Medical-based Deep Curriculum Learning for Improved Fracture Classification**. MICCAI 2019.   
**[arXiv](https://arxiv.org/abs/2004.00482)** / **[Paper](https://link.springer.com/chapter/10.1007%2F978-3-030-32226-7_77)** / **[Slides](https://www.upf.edu/documents/227877672/228393595/miccai19_slides.pdf/f2a2e245-e61a-8938-8c16-7ce754c8685f)** / **[Poster](https://www.upf.edu/documents/227877672/228393595/miccai19_poster.pdf/4a06d02d-b138-8ebc-cd4f-ca875c5c46ac)**   

**Curriculum Learning for Improved Femur Fracture Classification: Scheduling Data with Prior Knowledge and Uncertainty**. Medical Image Analysis 2021.   
**[arXiv](https://arxiv.org/abs/2007.16102)** / **[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1361841521003182)** / **[Code](https://github.com/ameliajimenez/curriculum-learning-prior-uncertainty)**    

**Memory-aware curriculum federated learning for breast cancer classification**     
Resources: **[arXiv](https://arxiv.org/abs/2107.02504) 2021** (under review)   