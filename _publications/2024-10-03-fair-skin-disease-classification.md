---
title: "Fair and Accurate Skin Disease Image Classification by Alignment with Clinical Labels"
collection: publications
category: conferences
permalink: /publication/fair-skin-disease-classification
excerpt: "A fairness-aware framework for skin disease image classification through alignment with clinical labels."
date: 2024-10-03
venue: "Medical Image Computing and Computer Assisted Intervention (MICCAI 2024)"
paperurl: "https://doi.org/10.1007/978-3-031-72378-0_37"
pdfurl: "/files/PatchAlignFair_and_Accurate_Skin_Disease_Image_Cla.pdf"
citation: >
  Aayushman, Hemanth Gaddey, Vidhi Mittal, Manisha Chawla, and Gagan Raj Gupta.
  "Fair and Accurate Skin Disease Image Classification by Alignment with Clinical Labels."
  <i>Medical Image Computing and Computer Assisted Intervention (MICCAI 2024)</i>,
  Springer, pp. 394–404, 2024.
---
## Overview

This work presents a fairness-aware framework for skin disease image classification by aligning learned visual representations with clinically meaningful labels. The proposed approach improves diagnostic accuracy while reducing demographic bias, contributing toward more reliable and equitable AI-assisted healthcare.

## Resources

- 📄 **DOI:** [Link](https://doi.org/10.1007/978-3-031-72378-0_37)
- 📥 **PDF:** [Download Paper](/files/PatchAlignFair_and_Accurate_Skin_Disease_Image_Cla.pdf)
- 💻 **Code:** [GitHUb](https://github.com/aayushmanace/PatchAlign24)
- 📚 **BibTeX:** [Download](/files/patchalign.bib)

## Abstract

Deep learning models have achieved great success in automating skin lesion diagnosis. However, the ethnic disparity in these models’ predictions needs to be addressed before deployment of these models. We introduce a novel approach: PatchAlign, to enhance skin condition image classification accuracy and fairness through alignment with clinical text representations of skin conditions. PatchAlign uses Graph Optimal Transport (GOT) Loss as a regularizer to perform cross-domain alignment. The representations thus obtained are robust and generalize well across skin tones, even with limited training samples. To reduce the effect of noise/artifacts in clinical dermatology images, we propose a learnable Masked Graph Optimal Transport for cross-domain alignment that further improves the fairness metrics.

We compare our model to the SOTA model (FairDisCo) on two skin lesion datasets with different skin types: Fitzpatrick17k and Diverse Dermatology Images (DDI). Our proposed approach, PatchAlign, enhances the accuracy of skin condition image classification by 2.8% (in-domain) and 6.2% (out-domain) on Fitzpatrick17k and 4.2% (in-domain) on DDI compared to FairDisCo. In addition, it consistently improves the fairness of true positive rates across skin tones in all of our experiments.

## Key Contributions

- Developed a fairness-aware framework for skin disease image classification.
- Introduced representation alignment using clinically meaningful labels.
- Improved both classification accuracy and fairness across demographic groups.
- Demonstrated effectiveness on benchmark dermatology datasets.
- Published at **MICCAI 2024**, one of the leading international conferences in medical image computing.
