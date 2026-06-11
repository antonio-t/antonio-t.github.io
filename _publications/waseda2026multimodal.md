---
title: "Multimodal Adversarial Defense for Vision-Language Models by Leveraging One-To-Many Relationships"
collection: publications
permalink: /publication/waseda2026multimodal
date: 2026-03-06
venue: 'Winter Conference on Applications of Computer Vision'
citation: 'Waseda, F., Tejero-de-Pablos, A., & Echizen, I. (2026, March). Multimodal Adversarial Defense for Vision-Language Models by Leveraging One-To-Many Relationships. In Proc. Winter Conference on Applications of Computer Vision (pp. 6968-6977).'
excerpt: ''
---
Pre-trained vision-language (VL) models are highly vulnerable to adversarial attacks. However, existing defense methods primarily focus on image classification, overlooking two key aspects of VL tasks: multimodal attacks, where both image and text can be perturbed, and the one-to-many relationship of images and texts, where a single image can correspond to multiple textual descriptions and vice versa (1:N and N:1). This work is the first to explore defense strategies against multimodal attacks in VL tasks, whereas prior VL defense methods focus on vision robustness. We propose multimodal adversarial training (MAT), which incorporates adversarial perturbations in both image and text modalities during training, significantly outperforming existing unimodal defenses. Furthermore, we discover that MAT is limited by deterministic one-to-one (1:1) image-text pairs in VL training data. To address this, we conduct a comprehensive study on leveraging one-to-many relationships to enhance robustness, investigating diverse augmentation techniques. Our analysis shows that, for a more effective defense, augmented image-text pairs should be well-aligned, diverse, yet avoid distribution shift—conditions overlooked by prior research. This work pioneers defense strategies against multimodal attacks, providing insights for building robust VLMs from both optimization and data perspectives. Our code is publicly available at https://github.com/CyberAgentAILab/multimodal-adversarial-training.

[Download here](https://openaccess.thecvf.com/content/WACV2026/papers/Waseda_Multimodal_Adversarial_Defense_for_Vision-Language_Models_by_Leveraging_One-To-Many_Relationships_WACV_2026_paper.pdf)

Bibtex:
```
@inproceedings{waseda2026multimodal,
  title={Multimodal Adversarial Defense for Vision-Language Models by Leveraging One-To-Many Relationships},
  author={Waseda, Futa and Tejero-de-Pablos, Antonio and Echizen, Isao},
  booktitle={Proc. Winter Conference on Applications of Computer Vision},
  pages={6968--6977},
  year={2026}
}
```
