---
title: "Fair and Accurate Skin Disease Image Classification by Alignment with Clinical Labels"
collection: publications
category: conferences
permalink: /publication/fair-skin-disease-classification
excerpt: "PatchAlign: A fairness-aware framework for accurate skin disease image classification through alignment with clinically meaningful text representations."
date: 2024-10-03
venue: "Medical Image Computing and Computer Assisted Intervention (MICCAI 2024)"
paperurl: "https://doi.org/10.1007/978-3-031-72378-0_37"
pdfurl: "/files/PatchAlignFair_and_Accurate_Skin_Disease_Image_Cla.pdf"
citation: >-
  Aayushman, Hemanth Gaddey, Vidhi Mittal, Manisha Chawla, and Gagan Raj Gupta,
  "Fair and Accurate Skin Disease Image Classification by Alignment with Clinical Labels,"
  <i>Medical Image Computing and Computer Assisted Intervention (MICCAI 2024)</i>,
  Springer, pp. 394–404, 2024.
---

## Overview

This work introduces **PatchAlign**, a fairness-aware framework for skin disease image classification that improves diagnostic accuracy while mitigating demographic bias across different skin tones.

The proposed approach aligns visual representations learned from dermatological images with clinically meaningful text representations of skin conditions. By incorporating Graph Optimal Transport (GOT) Loss for cross-domain alignment, PatchAlign learns robust representations that generalize effectively across diverse skin tones, even when training data is limited.

To further address noise and artifacts in clinical dermatology images, the framework introduces a learnable Masked Graph Optimal Transport mechanism, enhancing the fairness of model predictions.

## Resources

- **DOI:** [View Publication](https://doi.org/10.1007/978-3-031-72378-0_37)
- **PDF:** [Download Paper](/files/PatchAlignFair_and_Accurate_Skin_Disease_Image_Cla.pdf)
- **Code:** [GitHub Repository](https://github.com/aayushmanace/PatchAlign24)
- **BibTeX:** [Download BibTeX](/files/patchalign.bib)

## Abstract

Deep learning models have achieved remarkable success in automating skin lesion diagnosis. However, demographic disparities in model predictions, particularly across different ethnic groups and skin tones, remain a major challenge that must be addressed before deploying these models in clinical settings.

In this work, we introduce **PatchAlign**, a novel approach to improving both the accuracy and fairness of skin condition image classification through alignment with clinical text representations of skin conditions. PatchAlign employs Graph Optimal Transport (GOT) Loss as a regularizer to facilitate cross-domain alignment between visual and clinical text representations. The resulting representations are robust and generalize effectively across different skin tones, even with limited training samples.

To mitigate the impact of noise and artifacts in clinical dermatology images, we further propose a learnable Masked Graph Optimal Transport mechanism for cross-domain alignment, which provides additional improvements in fairness metrics.

We evaluate PatchAlign against the state-of-the-art FairDisCo model on two skin lesion datasets covering diverse skin types: **Fitzpatrick17k** and **Diverse Dermatology Images (DDI)**. Experimental results demonstrate that PatchAlign improves skin condition image classification accuracy over FairDisCo by:

- **Fitzpatrick17k:** 2.8% improvement in in-domain accuracy and 6.2% improvement in out-of-domain accuracy.
- **DDI:** 4.2% improvement in in-domain accuracy.

Furthermore, PatchAlign consistently improves the fairness of true positive rates across different skin tones in all experiments, demonstrating its potential for developing more accurate and equitable AI-assisted dermatological diagnosis systems.

## Key Contributions

- Proposed **PatchAlign**, a fairness-aware framework for skin disease image classification.
- Introduced clinical text-guided representation alignment using Graph Optimal Transport (GOT) Loss.
- Developed a learnable Masked Graph Optimal Transport mechanism to address noise and artifacts in dermatological images.
- Improved classification accuracy across in-domain and out-of-domain evaluation settings.
- Demonstrated consistent improvements in true positive rate fairness across different skin tones.
- Published at **MICCAI 2024**, a leading international conference in medical image computing.
