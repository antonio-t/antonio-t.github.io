---
title: "Beam Stack Search-based reconstruction of unhealthy coronary artery wall segmentations in CCTA-CPR scans"
collection: publications
permalink: /publication/tejero2021beam
date: 2021-04-12
venue: 'IEEE International Symposium on Biomedical Imaging'
citation: 'Tejero-de-Pablos, A., Yamane, H., Kurose, Y., Iho, J., Tokunaga, Y., Horie, M., M., Nishizawa, K., Hayashi, Y., Koyama, Y., & Harada, T. (2021, April). Beam Stack Search-Based Reconstruction Of Unhealthy Coronary Artery Wall Segmentations In CCTA-CPR Scans. In 2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI) (pp. 86-90).'
excerpt: ''
---
The estimation of the coronary artery wall boundaries in CCTA scans is a costly but essential task in the diagnosis of cardiac diseases. To automatize this task, deep learning-based image segmentation methods are commonly used. However, in the case of coronary artery wall, even state-of-the-art segmentation methods fail to produce an accurate boundary in the presence of plaques and bifurcations. Post-processing reconstruction methods have been proposed to further refine segmentation results, but when applying general-purpose reconstruction to artery wall segmentations, they fail to reproduce the wide variety of boundary shapes. In this paper, we propose a novel method for reconstructing coronary artery wall segmentations, the Tube Beam Stack Search (TBSS). By leveraging the voxel shape of adjacent slices in a CPR volume, our TBSS is capable of finding the most plausible path of the artery wall. Similarly to the original Beam Stack Search, TBSS navigates along the voxel probabilities output by the segmentation method, reconstructing the inner and outer artery walls. Finally, skeletonization is applied on the TBSS reconstructions to eliminate noise and produce more refined segmentations. Also, since our method does not require learning a model, the lack of annotated data is not a limitation. We evaluated our method on a dataset of coronary CT angiography with curved planar reconstruction (CCTA-CPR) of 92 arteries. Experimental results show that our method outperforms the state-of-the-art work in reconstruction.

[Download here](https://arxiv.org/pdf/1812.01261.pdf)

Bibtex:
```
@inproceedings{tejero2021beam,
  title={Beam Stack Search-Based Reconstruction Of Unhealthy Coronary Artery Wall Segmentations In CCTA-CPR Scans},
  author={Tejero-de-Pablos, Antonio and Yamane, Hiroaki and Kurose, Yusuke and Iho, Junichi and Tokunaga, Youji and Horie, Makoto and Nishizawa, Keisuke and Hayashi, Yusaku and Koyama, Yasushi and Harada, Tatsuya},
  booktitle={2021 IEEE 18th International Symposium on Biomedical Imaging (ISBI)},
  pages={86--90},
  year={2021},
  organization={IEEE}
}
```
