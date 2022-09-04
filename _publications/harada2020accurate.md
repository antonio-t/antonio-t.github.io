---
title: "Accurate parts visualization for explaining CNN reasoning via semantic segmentation"
collection: publications
permalink: /publication/harada2020accurate
date: 2020-09-20
venue: 'The British Machine Vision Conference'
citation: 'Harada, R., Tejero-de-Pablos, A., & Harada, T. (2020). Accurate Parts Visualization for Explaining CNN Reasoning via Semantic Segmentation. In BMVC.'
excerpt: ''
---
Nowadays, neural networks are often used for image classification, but the structure of their decisions is difficult to understand because of their "black-box" nature. Different visualization techniques have been proposed to provide additional information on the reason of the classification results. Existing methods provide quantitative explanations by calculating heatmaps and interpretable components in the image. While the latter provides semantics on the image parts that contribute for the classification, the component areas are blurry due to the use of linear layers, which do not consider surrounding information. This makes hard to point out the specific reason for the classification and to evaluate quantitatively. In this paper, we introduce a novel method for explaining classification in neural networks, the Parts Detection Module. Unlike previous methods, ours is capable of determining the accurate position of the interpretable components in the image by performing upsampling and convolution stepwise, similarly to semantic segmentation. In addition to providing quantitative visual explanations, we also proposed a method to verify the validity of the quantitative explanations themselves. The experimental results prove the effectivity of our explanations.

[Download here](https://www.bmvc2020-conference.com/assets/papers/0754.pdf)

Bibtex:
```
@inproceedings{harada2020accurate,
  title={Accurate Parts Visualization for Explaining CNN Reasoning via Semantic Segmentation.},
  author={Harada, Ren and Tejero-de-Pablos, Antonio and Harada, Tatsuya},
  booktitle={BMVC},
  year={2020}
}
```
