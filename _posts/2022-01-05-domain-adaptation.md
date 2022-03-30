---
title: 'What is domain adaptation? (In Japanese)'
date: 2022-01-05
permalink: /posts/2022/01/domain-adaptation/
tags:
  - domain adaptation
  - transfer learning
  - out-of-distribution generalization
  - computer vision
  - machine learning
---

A big majority of the machine learning systems existing in society assume that the data used for training and the data used after deployment follow the same distribution. However, in reality, these systems suffer a drop in performance due to the differences between training and test data. Multiple methods have been proposed in order to transfer the knowledge learned from a set of data to another set belonging to a different domain, but it is hard to achieve good generalization depending on the ``gap'' between these domains. This blog post introduces an overview of domain adaptation (DA) techniques, why they are necessary, and different types and scenarios they can be applied to. I hope that, once readers understand these points, this blog post may serve as a starting-guide for surveying more specific methods (multimodal DA, etc.) that adapt to their needs.

- [Link to blog](https://cyberagent.ai/blog/research/computervision/15768/)
