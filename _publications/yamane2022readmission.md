---
title: "Readmission prediction for heart failure patients using features extracted from SS-MIX"
collection: publications
permalink: /publication/yamane2022readmission
date: 2022-11-14
venue: 'SCIS&ISIS'
citation: 'Yamane, H., Kurose, Y., Tejero-de-Pablos, A., Gu, L., Iho, J., Tokunaga, Y., Horie, M., Hayashi, Y., Nishizawa, K., Koyama, Y., & Tatsuya, H. (2022). Readmission prediction for heart failure patients using features extracted from SS-MIX. Joint 12th International Conference on Soft Computing and Intelligent Systems and 23rd International Symposium on Advanced Intelligent Systems (SCIS&ISIS).'
excerpt: ''
---
Increased demand for healthcare has resulted in necessity of utilizing electronic medical records. Standardized Structured Medical Information eXchange (SS-MIX) is a standard data storage format used in Japan to share clinical data. SS-MIX contains standard medical receipt data which is automatically stored. In this paper, we utilize the SS-MIX data to predict readmission of patients, who are suffering from heart failure. (i.e.,We define the readmission prediction task as a binary prediction task, where whether a patient readmits within N days after hospital discharge or not.) We train classifiers based on features (e.g., disease history, allergy, prescription, etc.) that are extracted from medical receipt data which is contained in SS-MIX. The experimental result showed that above features are effective for the task of readmission prediction; in particular, LightGBM outperformed other classifiers. Moreover, features from ICD10 codes are shown to be effective to predict readmission.

[Download here](https://ieeexplore.ieee.org/abstract/document/10001907)

Bibtex:
```
@inproceedings{yamane2022readmission,
  title={Readmission Prediction for Heart Failure Patients Using Features Extracted From SS-MIX},
  author={Yamane, Hiroaki and Kurose, Yusuke and Tejero-de-Pablos, Antonio and Gu, Lin and Iho, Junichi and Tokunaga, Youji and Horie, Makoto and Hayashi, Yusaku and Nishizawa, Keisuke and Koyama, Yasushi and others},
  booktitle={Joint 12th International Conference on Soft Computing and Intelligent Systems and 23rd International Symposium on Advanced Intelligent Systems (SCIS\&ISIS)},
  pages={1--5},
  year={2022}
}
```
