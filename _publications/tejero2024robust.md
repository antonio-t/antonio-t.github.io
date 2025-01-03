---
title: "Robust Nearest Neighbors for Source-Free Domain Adaptation under Class Distribution Shift"
collection: publications
permalink: /publication/tejero2024robust
date: 2024-10-02
venue: 'European Conference on Computer Vision'
citation: 'Tejero-de-Pablos, A., Togashi, R., Otani, M., Satoh, S. (2024, October). Robust Nearest Neighbors for Source-Free Domain Adaptation under Class Distribution Shift. In Proc. European Conference on Computer Vision.'
excerpt: ''
---
The goal of source-free domain adaptation (SFDA) is retraining a model fit on data from a source domain (e.g. drawings) to classify data from a target domain (e.g. photos) employing only the target samples. In addition to the domain shift, in a realistic scenario, the number of samples per class on source and target would also differ (i.e. class distribution shift, or CDS). Dealing label-less with CDS via target data only is challenging, and thus previous methods assume no class imbalance in the source data. We study the SFDA pipeline and, for the first time, propose a SFDA method that can deal with class imbalance in both source and target data. While pseudolabeling is the core technique in SFDA to estimate the distribution of the target data, it relies on nearest neighbors, which makes it sensitive to class distribution shifts (CDS). We are able to calculate robust nearest neighbors by leveraging additional generic features free of the source model’s CDS bias. This provides a “second-opinion” regarding which nearest neighbors are more suitable for adaptation. We evaluate our method using various types of features, datasets and tasks, outperforming previous methods in SFDA under CDS. Our code is available at https://github.com/CyberAgentAILab/Robust_Nearest_Neighbors_SFDA-CDS.

[Download here](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/09049.pdf)

Bibtex:
```
@inproceedings{tejero2025robust,
    title   = {Robust Nearest Neighbors for Source-Free Domain Adaptation Under Class Distribution Shift},
  author    = {Tejero-de-Pablos, Antonio and Togashi, Riku and Otani, Mayu and Satoh, Shin’ichi},
  booktitle = {In Proc. European Conference on Computer Vision},
  pages     = {1--17},
  year      = {2024}
}
```
