---
title: "Beyond Federated Learning for IoT: Efficient Split Learning with Caching and Model Customization"
collection: publications
category: manuscripts
permalink: /publication/beyond-federated-learning-for-iot
excerpt: "A communication-efficient Split Learning framework with caching and model customization for resource-constrained IoT environments."
date: 2024-07-05
venue: "IEEE Internet of Things Journal"
paperurl: "https://doi.org/10.1109/JIOT.2024.3424660"
pdfurl: "/files/Beyond_Federated_Learning_for_IoT_Efficient_Split_Learning_With_Caching_and_Model_Customization.pdf"
slidesurl: "/files/ManishaChawla_Wholesome_Thesis_Presentation_2024.pdf"
bibtexurl: "/files/fedsl.bib"
citation: >-
  M. Chawla, G. R. Gupta, S. Gaddam, and M. Wadhwa,
  "Beyond Federated Learning for IoT: Efficient Split Learning With Caching and Model Customization,"
  <i>IEEE Internet of Things Journal</i>, vol. 11, no. 20,
  pp. 32617–32630, Oct. 15, 2024.
codeurl: "https://github.com/S3-Lab-IIT/Efficient-Split-Learning"
---

## Overview

This work presents a communication-efficient **Split Learning (SL)** framework for resource-constrained Internet of Things (IoT) environments. The proposed framework, called **Efficient Split Learning (ESL)**, combines caching and model customization to reduce computational and communication overhead while enabling personalized models for heterogeneous clients.

By leveraging shared intermediate activations and client-specific model training, ESL minimizes redundant computations and communication while maintaining high model accuracy.

## Resources

- **DOI:** [View Publication](https://doi.org/10.1109/JIOT.2024.3424660)
- **PDF:** [Download Paper](/files/Beyond_Federated_Learning_for_IoT_Efficient_Split_Learning_With_Caching_and_Model_Customization.pdf)
- **Code:** [GitHub Repository](https://github.com/S3-Lab-IIT/Efficient-Split-Learning.git)
- **Slides:** [View Presentation](/files/ManishaChawla_Wholesome_Thesis_Presentation_2024.pdf)
- **BibTeX:** [Download BibTeX](/files/fedsl.bib)

## Abstract

Distributed training of deep learning models on resource-constrained devices has gained significant attention. Federated Learning (FL) and Split Learning (SL) have emerged as two prominent approaches for collaboratively training data-driven deep learning models while keeping data distributed across multiple devices. However, these approaches often incur substantial computational costs on resource-constrained devices and high communication overhead due to frequent exchanges of models, intermediate activations, and gradients.

This paper proposes **Efficient Split Learning (ESL)**, a novel framework designed to address these challenges through three key contributions:

1. **Caching and sharing of intermediate activations:** A key-value store is introduced to cache and share intermediate activations across clients, significantly reducing redundant computations and communication during training.
2. **Model customization:** State-of-the-art neural network architectures are customized to make them more suitable for the Split Learning paradigm.
3. **Personalized training:** Clients are enabled to learn individual models tailored to their specific data distributions, supporting heterogeneous learning environments.

Unlike existing communication-efficient FL and SL approaches that often trade model accuracy for reduced communication overhead, ESL achieves substantial reductions in computation and communication while maintaining high accuracy.

Extensive experiments on real-world federated benchmarks for image classification and 3D segmentation demonstrate the effectiveness of the proposed framework. Compared with baseline FL techniques, ESL achieves:

- **Computational cost reduction:** 1623× for image classification and 23.9× for 3D segmentation on resource-constrained devices.
- **Communication reduction:** 3.92× for image classification and 1.3× for 3D segmentation during training.
- **Accuracy improvement:** 35% for image classification and 31% for 3D segmentation.

Furthermore, compared with baseline SL approaches, ESL reduces training-time communication traffic by **100×** and improves accuracy by an average of **34.8%**.
