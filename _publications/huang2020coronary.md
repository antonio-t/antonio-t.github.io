---
title: "Coronary wall segmentation in CCTA scans via a hybrid net with contours regularization"
collection: publications
permalink: /publication/huang2020coronary
date: 2020-01-25
venue: 'IEEE International Symposium on Biomedical Imaging'
citation: 'Huang, K., Tejero-de-Pablos, A., Yamane, H., Kurose, Y., Iho, J., Tokunaga, Y., Horie, M., Nishizawa, K., Hayashi, Y., Koyama, Y., & Harada, T. (2020, April). Coronary Wall Segmentation in CCTA Scans via a Hybrid Net with Contours Regularization. In 2020 IEEE 17th International Symposium on Biomedical Imaging (ISBI) (pp. 1743-1747).'
excerpt: ''
---
Providing closed and well-connected boundaries of coronary artery is essential to assist cardiologists in the diagnosis of coronary artery disease (CAD). Recently, several deep learning-based methods have been proposed for boundary detection and segmentation in a medical image. However, when applied to coronary wall detection, they tend to produce disconnected and inaccurate boundaries. In this paper, we propose a novel boundary detection method for coronary arteries that focuses on the continuity and connectivity of the boundaries. In order to model the spatial continuity of consecutive images, our hybrid architecture takes a volume (i.e., a segment of the coronary artery) as input and detects the boundary of the target slice (i.e., the central slice of the segment). Then, to ensure closed boundaries, we propose a contour-constrained weighted Hausdorff distance loss. We evaluate our method on a dataset of 34 patients of coronary CT angiography scans with curved planar reconstruction (CCTA-CPR) of the arteries (i.e., cross-sections). Experiment results show that our method can produce smooth closed boundaries outperforming the state-of-the-art accuracy.

[Download here](https://arxiv.org/pdf/2002.12263.pdf)

Bibtex:
```
@inproceedings{huang2020coronary,
  title={Coronary Wall Segmentation in CCTA Scans Via a Hybrid Net with Contours Regularization},
  author={Huang, Kaikai and Tejero-de-Pablos, Antonio and Yamane, Hiroaki and Kurose, Yusuke and Iho, Junichi and Tokunaga, Youji and Horie, Makoto and Nishizawa, Keisuke and Hayashi, Yusaku and Koyama, Yasushi and others},
  booktitle={2020 IEEE 17th International Symposium on Biomedical Imaging (ISBI)},
  pages={1743--1747},
  year={2020},
  organization={IEEE}
}
```
