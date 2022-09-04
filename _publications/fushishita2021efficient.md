---
title: "Efficient training for future video generation based on hierarchical disentangled representation of latent variables"
collection: publications
permalink: /publication/fushishita2021efficient
date: 2021-04-01
venue: 'arXiv preprint'
citation: 'Fushishita, N., Tejero-de-Pablos, A., Mukuta, Y., & Harada, T. (2021). Efficient training for future video generation based on hierarchical disentangled representation of latent variables. arXiv preprint arXiv:2106.03502.'
excerpt: ''
---
Generating videos predicting the future of a given sequence has been an area of active research in recent years. However, an essential problem remains unsolved: most of the methods require large computational cost and memory usage for training. In this paper, we propose a novel method for generating future prediction videos with less memory usage than the conventional methods. This is a critical stepping stone in the path towards generating videos with high image quality, similar to that of generated images in the latest works in the field of image generation. We achieve high-efficiency by training our method in two stages: (1) image reconstruction to encode video frames into latent variables, and (2) latent variable prediction to generate the future sequence. Our method achieves an efficient compression of video into low-dimensional latent variables by decomposing each frame according to its hierarchical structure. That is, we consider that video can be separated into background and foreground objects, and that each object holds time-varying and time-independent information independently. Our experiments show that the proposed method can efficiently generate future prediction videos, even for complex datasets that cannot be handled by previous methods.

[Download here](https://arxiv.org/pdf/2106.03502.pdf)

Bibtex:
```
@article{fushishita2021efficient,
  title={Efficient training for future video generation based on hierarchical disentangled representation of latent variables},
  author={Fushishita, Naoya and Tejero-de-Pablos, Antonio and Mukuta, Yusuke and Harada, Tatsuya},
  journal={arXiv preprint arXiv:2106.03502},
  year={2021}
}
```
