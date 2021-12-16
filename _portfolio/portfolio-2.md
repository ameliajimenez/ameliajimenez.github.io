---
title: "Capsule Networks"
excerpt: "Short description of portfolio item number 2"
collection: portfolio
permalink: /portfolio/portfolio-2
---

Currently, numerous state of the art solutions for medical image analysis tasks such as computer-aided detection or diagnosis rely on **Convolutional Neural Networks (CNNs)**. The popularity of CNNs relies on their capability to **learn meaningful and hierarchical image representations** directly from examples, resulting in a feature extraction approach that is flexible, general and capable of encoding complex patterns.

CNNs **requirement for big amounts of data** is commonly justified by a large number of network parameters to train under a non-convex optimization scheme. We argue, however, that part of these data requirements is there to cope with their **poor modeling of spatial invariance**. As it is known, purely convolutional networks are not natively spatially invariant. Instead, they **rely on pooling layers to achieve translation invariance**, and on **data-augmentation to handle rotation invariance**. With pooling, the convolution filters learn the distinctive features of the object of interest irrespective of their location. Thereby **losing the spatial relationship among features** which might be essential to determine their class (e.g. the presence of plane parts in an image does not ensure that it contains a plane).

**Capsule Networks** were introduced as an alternative deep learning architecture and training approach **to model the spatial/viewpoint variability of an object in the image**. Inspired by computer graphics, capsule networks not only learn good weights for feature extraction and image classification but also **learn how to infer pose parameters** from the image. Poses are modeled as multidimensional vectors whose entries parametrize spatial variations such as rotation, thickness, skewness, etc. As an example, a capsule network learns to determine whether a plane is in the image, but also if the plane is located to the left or right or if it is rotated. This is known as ***equivariance*** and it is a property of human one-shot learning type of vision.


### Publications
**Capsule Networks against Medical Imaging Data Challenges**. LABELS -- MICCAI 2018  
**[arXiv](https://arxiv.org/abs/1807.07559)** / **[Paper](https://link.springer.com/chapter/10.1007%2F978-3-030-01364-6_17)** / **[Slides](https://www.upf.edu/documents/227877672/228393595/labels18_slides.pdf/82bdbff1-99e3-f538-bef4-aba78253c548)** / **[Poster](https://www.upf.edu/documents/227877672/228393595/labels18_poster.pdf/e38c8fbf-fe25-1240-9756-f5899f86f957)** / **[Code](https://github.com/ameliajimenez/capsule-networks-medical-data-challenges)**