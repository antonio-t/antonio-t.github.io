---
title: "Bounding-box channel network for visual relationship detection"
collection: publications
permalink: /publication/inayoshi2020bounding
date: 2020-08-01
venue: 'European Conference on Computer Vision'
citation: 'Inayoshi, S., Otani, K., Tejero-de-Pablos, A., & Harada, T. (2020, August). Bounding-box channels for visual relationship detection. In European Conference on Computer Vision (pp. 682-697).'
excerpt: ''
---
Recognizing the relationship between multiple objects in an image is essential for a deeper understanding of the meaning of the image. However, current visual recognition methods are still far from reaching human-level accuracy. Recent approaches have tackled this task by combining image features with semantic and spatial features, but the way they relate them to each other is weak, mostly because the spatial context in the image feature is lost. In this paper, we propose the bounding-box channels, a novel architecture capable of relating the semantic, spatial, and image features strongly. Our network learns bounding-box channels, which are initialized according to the position and the label of objects, and concatenated to the image features extracted from such objects. Then, they are input together to the relationship estimator. This allows retaining the spatial information in the image features, and strongly associate them with the semantic and spatial features. This way, our method is capable of effectively emphasizing the features in the object area for a better modeling of the relationships within objects. Our evaluation results show the efficacy of our architecture outperforming previous works in visual relationship detection. In addition, we experimentally show that our bounding-box channels have a high generalization ability.

[Download here](http://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123500664.pdf)