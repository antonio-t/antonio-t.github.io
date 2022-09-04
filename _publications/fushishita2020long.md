---
title: "Long-term human video generation of multiple futures using poses"
collection: publications
permalink: /publication/fushishita2020long
date: 2020-08-01
venue: 'European Conference on Computer Vision'
citation: 'Fushishita, N., Tejero-de-Pablos, A., Mukuta, Y., & Harada, T. (2020, August). Long-Term Human Video Generation of Multiple Futures Using Poses. In European Conference on Computer Vision (pp. 596-612).'
excerpt: ''
---
Generating future video from an input video is a useful task for applications such as content creation and autonomous agents. Especially, prediction of human video is highly important. While most previous works predict a single future, multiple futures with different behavior can potentially occur. Moreover, if the predicted future is too short (e.g., less than one second), it may not be fully usable by a human or other systems. In this paper, we propose a novel method for future human pose prediction capable of predicting multiple long-term futures. This makes the predictions more suitable for real applications. After predicting future human motion, we generate future videos based on predicted poses. First, from an input human video, we generate sequences of future human poses (i.e., the image coordinates of their body-joints) via adversarial learning. Adversarial learning suers from mode collapse, which
makes it dicult to generate a variety of multiple poses. We solve this problem by utilizing two additional inputs to the generator to make the outputs diverse, namely, a latent code (to reflect various behaviors) and an attraction point (to reflect various trajectories). In addition, we generate long-term future human poses using a novel approach based on unidimensional convolutional neural networks. Last, we generate an output video based on the generated poses for visualization. We evaluate the generated future poses and videos using three criteria (i.e., realism, diversity and accuracy), and show that our proposed method outperforms other state-of-the-art works.

[Download here](https://arxiv.org/pdf/1904.07538.pdf)

Bibtex:
```
@inproceedings{fushishita2020long,
  title={Long-Term Human Video Generation of Multiple Futures Using Poses},
  author={Fushishita, Naoya and Tejero-de-Pablos, Antonio and Mukuta, Yusuke and Harada, Tatsuya},
  booktitle={European Conference on Computer Vision},
  pages={596--612},
  year={2020},
  organization={Springer}
}
```
