---
title: "Source-Free Domain Adaptation with Class Distribution Shift via Generic Features"
collection: publications
permalink: /publication/tejero2024source-free
date: 2024-08-08
venue: 'Meeting on Image Recognition and Understanding'
citation: 'Tejero-de-Pablos, A., Togashi, R., Otani, M., Satoh, S. (2024, August). Source-Free Domain Adaptation with Class Distribution Shift via Generic Features. In Meeting on Image Recognition and Understanding.'
excerpt: ''
---
Source-free domain adaptation (SFDA) retrains a model fit on data from a source domain (e.g. drawings) to classify data from a target domain (e.g. photos) employing only the target samples. In addition to the domain shift, in a realistic scenario, the number of samples per class on source and target would also differ (i.e. class distribution shift, or CDS). By studying the SFDA pipeline, whose core is nearest neighbors (NN)-based pseudolabeling, we identify for the first time its sensibility to CDS, and propose a method to obtain robust NN. Since the class distribution of the target samples cannot be estimated via the source model, we leverage an external generic model that provides a “second opinion” for calculating NN. Our method outperforms previous works in several datasets and tasks.