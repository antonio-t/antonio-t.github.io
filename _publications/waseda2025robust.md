---
title: "Robust Vision-Language Models via Multimodal Adversarial Training with One-to-Many Augmentations"
collection: publications
permalink: /publication/waseda2025robust
date: 2025-07-29
venue: 'Meeting on Image Recognition and Understanding'
citation: 'Waseda, F., Tejero-de-Pablos, A., Echizen, I., (2025, July). Robust Vision-Language Models via Multimodal Adversarial Training with One-to-Many Augmentations. In Meeting on Image Recognition and Understanding.'
excerpt: ''
---
Defending vision-language (VL) models against adversarial attacks is not trivial when applied to a multimodal setting. First, (i) multimodal VL tasks allow attackers to manipulate either the image or text input. Then, (ii) image-text pairs are naturally not deterministic, that is, a single image can be matched to multiple textual descriptions, and vice versa. However, previous defense methods for VL models mainly address image classification tasks, which do not meet the setting above. We propose the first defense strategy for VL models against multimodal attacks, multimodal adversarial training (MAT), by introducing adversarial perturbations in both images and texts. In addition, since traditional adversarial training is prone to deterministic pairing of a single image and text (1:1), we study different augmentation strategies to leverage one-to-many relationships (1:N) for enhanced robustness. We discover that augmentations that meet the alignment, diversity and distribution gap criteria allow for a more optimal defense, outperforming all previous efforts in adversarial defense for VL models.