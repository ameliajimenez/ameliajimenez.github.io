---
title: "Curriculum Learning"
collection: portfolio
permalink: /portfolio/2009-10-01-paper-title-number-1
date: 2009-10-01
venue: 'Journal 1'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

In a typical educational system, learning relies on a **curriculum** that introduces new concepts building upon previously acquired ones. The rationale behind, is that humans and animals learn better when information is presented in a meaningful way rather than randomly. We follow this starting small concept to design our approaches with convolutional neural networks for medical image classification tasks.

In our novel formulation we reunite three **curriculum learning strategies**: individually **weighting** training samples, **reordering** the training set, and **sampling subsets** of data into a **data scheduler**. The core of these strategies is a **scoring function** ranking the training samples. We define two novel scoring functions: one from **domain-specific prior knowledge** and an original **self-paced uncertainty score**. We perform experiments on a clinical dataset of proximal femur radiographs. The curriculum improves **proximal femur fracture classification** up to the performance of experienced trauma surgeons. The best curriculum method reorders the training set based on prior knowledge resulting into a classification improvement of 15\%. Using the publicly available **MNIST** dataset, we further discuss and demonstrate the benefits of our unified curriculum learning formulation for three controlled and challenging digit recognition scenarios: **with limited amounts of data, under class-imbalance, and in the presence of label noise.**

Another approach to deal with class-imbalance and restricted-size datasets is to join forces across multiple institutions. Recently, **federated learning** has emerged as an effective tool for collaborative learning. In this setting, local models perform computation on their private data to update the global model. The order and the frequency of local updates influence the final global model. Hence, the order in which samples are locally presented to the optimizers plays an important role. In this work, we define a **memory-aware curriculum learning method for the federated setting**. Our curriculum controls the order of the training samples paying special **attention to those that are forgotten after the deployment of the global model**. Our approach is **combined with unsupervised domain adaptation** to deal with domain shift while preserving data privacy. We evaluate our method with **three clinical datasets from different vendors**. Our results verify the effectiveness of **federated adversarial learning** for the **multi-site breast cancer classification**.
