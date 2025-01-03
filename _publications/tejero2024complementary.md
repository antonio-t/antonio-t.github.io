---
title: "Complementary-Contradictory Feature Regularization against Multimodal Overfitting"
collection: publications
permalink: /publication/tejero2024complementary
date: 2024-01-04
venue: 'Winter Conference on Applications of Computer Vision'
citation: 'Tejero-de-Pablos, A. (2024, January). Complementary-Contradictory Feature Regularization against Multimodal Overfitting. In Proc. Winter Conference on Applications of Computer Vision.'
excerpt: ''
---
Understanding multimodal learning is essential to design intelligent systems that can effectively combine various data types (visual, audio, etc.). Multimodal learning is not trivial, as adding new modalities does not always result in a significant improvement in performance, i.e., multimodal overfitting. To tackle this, several works proposed regularizing each modality's learning speed and feature distribution. However, in these methods, characterizing quantitatively and qualitatively multimodal overfitting is not intuitive. We hypothesize that, rather than regularizing abstract hyperparameters, regularizing the features learned is a more straightforward methodology against multimodal overfitting. For the given input modalities and task, we constrain "complementary" (useful) and "contradictory" (obstacle) features via a masking operation on the multimodal latent space. In addition, we leverage latent discretization so the size of the complementary-contradictory spaces becomes learnable, allowing the estimation of a modal complementarity measure. Our method successfully improves the performance of datasets with modality overfitting in different tasks, providing insight into "what" and "how much" is learned from each modality. Furthermore, it facilitates transfer learning to new datasets. Our code and a detailed manual are available [here](https://github.com/CyberAgentAILab/CM-VQVAE).

[Download here](https://openaccess.thecvf.com/content/WACV2024/papers/Tejero-de-Pablos_Complementary-Contradictory_Feature_Regularization_Against_Multimodal_Overfitting_WACV_2024_paper.pdf)

Bibtex:
```
@inproceedings{tejero2024complementary,
    title     = {Complementary-contradictory feature regularization against multimodal overfitting},
    author    = {Tejero-de-Pablos, Antonio},
    booktitle = {In Proc. Winter Conference on Applications of Computer Vision},
    pages     = {5679-5688},
    year={2024}
}
```
