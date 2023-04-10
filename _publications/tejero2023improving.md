---
title: "Improving segmentation of calcified and non-calcified plaques on CCTA-CPR scans via masking of the artery wall"
collection: publications
permalink: /publication/tejero2023improving
date: 2023-04-07
venue: 'SPIE Medical Imaging'
citation: 'Tejero-de-Pablos, A., Yamane, H., Kurose, Y., Iho, J., Tokunaga, Y., Horie, M., Nishizawa, K., Hayashi, Y., Koyama, Y. &, Harada, T. (2023, April). Improving segmentation of calcified and non-calcified plaques on CCTA-CPR scans via masking of the artery wall. In Proc. SPIE 12465, Medical Imaging 2023: Computer-Aided Diagnosis.'
excerpt: ''
---
The presence of plaques in the coronary arteries is a major risk to the patients' life. In particular, non-calcified plaques pose a great challenge, as they are harder to detect and more likely to rupture than calcified plaques. While current deep learning techniques allow precise segmentation of real-life images, the performance in medical images is still low. This is caused mostly by blurriness and ambiguous voxel intensities of unrelated parts that fall on the same value range. In this paper, we propose a novel methodology for segmenting calcified and non-calcified plaques in CCTA-CPR scans of coronary arteries. The input slices are masked so only the voxels within the wall vessel are considered for segmentation, thus, reducing ambiguity. This mask can be automatically generated via a deep learning-based vessel detector, that provides not only the contour of the outer artery wall, but also the inner contour. For evaluation, we utilized a dataset in which each voxel is carefully annotated as one of five classes: background, lumen, artery wall, calcified plaque, or non-calcified plaque. We also provide an exhaustive evaluation by applying different types of masks, in order to validate the potential of vessel masking for plaque segmentation. Our methodology results in a prominent boost in segmentation performance, in both quantitative and qualitative evaluation, achieving accurate plaque shapes even for the challenging non-calcified plaques. Furthermore, when using highly accurate masks, difficult cases such as stenosis become segmentable. We believe our findings can lead the future research for high-performance plaque segmentation.

[Download here](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12465/124651X/Improving-segmentation-of-calcified-and-non-calcified-plaques-on-CCTA/10.1117/12.2652895.short?SSO=1)

Bibtex:
```
@inproceedings{tejero2023improving,
  title={Improving segmentation of calcified and non-calcified plaques on CCTA-CPR scans via masking of the artery wall},
  author={Tejero-de-Pablos, Antonio and Yamane, Hiroaki and Kurose, Yusuke and Iho, Junichi and Tokunaga, Youji and Horie, Makoto and Nishizawa, Keisuke and Hayashi, Yusaku and Koyama, Yasushi and Harada, Tatsuya},
  booktitle={Proc. SPIE 12465, Medical Imaging 2023: Computer-Aided Diagnosis},
  volume={12465},
  year={2023}
}
```
