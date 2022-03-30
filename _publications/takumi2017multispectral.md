---
title: "Multispectral object detection for autonomous vehicles"
collection: publications
permalink: /publication/takumi2017multispectral
date: 2017-10-01
venue: 'Thematic Workshops of ACM Multimedia'
citation: 'Takumi, K., Watanabe, K., Ha, Q., Tejero-de-Pablos, A., Ushiku, Y., & Harada, T. (2017, October). Multispectral object detection for autonomous vehicles. In Proceedings of the on Thematic Workshops of ACM Multimedia 2017 (pp. 35-43)'
excerpt: ''
---
Recently, researchers have actively conducted studies on mobile robot technologies that involve autonomous driving. To implement an automatic mobile robot (e.g., an automated driving vehicle) in
traffic, robustly detecting various types of objects such as cars, people, and bicycles in various conditions such as daytime and nighttime is necessary. In this paper, we propose the use of multi-
spectral images as input information for object detection in traffic. Multispectral images are composed of RGB images, near-infrared images, middle-infrared images, and far-infrared images and have multilateral information as a whole. For example, some objects that cannot be visually recognized in the RGB image can be detected in the far-infrared image. To train our multispectral object detection system, we need a multispectral dataset for object detection in traffic. Since such a dataset does not currently exist, in this study we generated our own multispectral dataset. In addition, we propose a multispectral ensemble detection pipeline to fully use the features of multispectral images. The pipeline is divided into two parts: the single-spectral detection model and the ensemble part. We conducted two experiments in this work. In the first experiment, we evaluate our single-spectral object detection model. Our results show that each component in the multispectral image was individually useful for the task of object detection when applied to different types of objects. In the second experiment, we evaluate the entire multispectral object detection system and show that the mean average precision (mAP) of multispectral object detection is 13% higher than that of RGB-only object detection.

[Download here](https://dl.acm.org/doi/10.1145/3126686.3126727)