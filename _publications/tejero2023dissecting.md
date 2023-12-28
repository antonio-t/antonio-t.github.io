---
title: "Dissecting multimodal learning via regularized masking of multimodal features"
collection: publications
permalink: /publication/tejero2023dissecting
date: 2023-07-25
venue: 'Meeting on Image Recognition and Understanding'
citation: 'Tejero-de-Pablos, A. (2023, July). Dissecting multimodal learning via regularized masking of multimodal features. Meeting on Image Recognition and Understanding.'
excerpt: ''
---
Multimodal learning is not trivial, as adding new modalities (image, audio, etc.) does not always result in a significant improvement in performance. Recently, several works have proposed tweaking the learning rate in order to avoid overfitting one modality over the other. However, these methods do not clarify why the performance increases/decreases on the first place. We hypothesize that, besides controlling overfitting, constraining the features learned from each modality further prevents including features that interfere with the given task (e.g., skin color in human emotion recognition). We propose CM-VQVAE (Complementary Multimodal VQVAE), which distinguishes "complementary" and "contradictory" features for a given multimodal input and task. This is done via a masking operation on the multimodal latent space, so the size of the complementary-contradictory spaces becomes learnable, allowing the estimation of a modal complementarity measure. In our experiments, CM-VQVAE successfully improves the multimodal performance of datasets with different modalities and tasks, providing insight into "what" and "how much" is learned from each modality. Furthermore, it facilitates transfer learning to new datasets.
