---
title: "Training-free Conditional Image Embedding Framework from Large Vision Language Models"
collection: publications
permalink: /publication/kawarada2026training
date: 2026-03-06
venue: 'Winter Conference on Applications of Computer Vision'
citation: 'Kawarada, M., Yamada, K., Tejero-de-Pablos, A., & Inoue, N. (2026, March). Training-free Conditional Image Embedding Framework Leveraging Large Vision Language Models. In Proc. Winter Conference on Applications of Computer Vision (pp. 7636-7646).'
excerpt: ''
---
Conditional image embeddings are feature representations that focus on specific aspects of an image indicated by a given textual condition (eg, color, genre), which has been a challenging problem. Although recent vision foundation models, such as CLIP, offer rich representations of images, they are not designed to focus on a specified condition. In this paper, we propose DIOR, a method that leverages a large vision-language model (LVLM) to generate conditional image embeddings. DIOR is a training-free approach that prompts the LVLM to describe an image with a single word related to a given condition. The hidden state vector of the LVLM's last token is then extracted as the conditional image embedding. DIOR provides a versatile solution that can be applied to any image and condition without additional training or task-specific priors. Comprehensive experimental results on conditional image similarity tasks demonstrate that DIOR outperforms existing training-free baselines, including CLIP. Furthermore, DIOR achieves superior performance compared to methods that require additional training across multiple settings.

[Download here](https://openaccess.thecvf.com/content/WACV2026/papers/Kawarada_Training-free_Conditional_Image_Embedding_Framework_Leveraging_Large_Vision_Language_Models_WACV_2026_paper.pdf)

Bibtex:
```
@inproceedings{kawarada2026training,
  title={Training-free Conditional Image Embedding Framework Leveraging Large Vision Language Models},
  author={Kawarada, Masayuki and Yamada, Kosuke and Tejero-de-Pablos, Antonio and Inoue, Naoto},
  booktitle={Proc. Winter Conference on Applications of Computer Vision},
  pages={7636--7646},
  year={2026}
}
```
