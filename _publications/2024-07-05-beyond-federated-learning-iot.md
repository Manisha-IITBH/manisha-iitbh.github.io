---
title: "Beyond Federated Learning for IoT: Efficient Split Learning with Caching and Model Customization"
collection: publications
category: manuscripts
permalink: /publication/beyond-federated-learning-for-iot
excerpt: "Efficient split learning with caching and model customization for resource-constrained IoT environments."
date: 2024-07-05
venue: "IEEE Internet of Things Journal"
paperurl: "https://doi.org/10.1109/JIOT.2024.3424660"
pdfurl: "/files/Beyond_Federated_Learning_for_IoT_Efficient_Split_Learning_With_Caching_and_Model_Customization.pdf"
slidesurl: "/files/ManishaChawla_Wholesome_Thesis_Presentation_2024.pdf"
bibtexurl: "/files/fedsl.bib"
citation: >
  M. Chawla, G. R. Gupta, S. Gaddam, and M. Wadhwa,
  "Beyond Federated Learning for IoT: Efficient Split Learning With Caching and Model Customization,"
  <i>IEEE Internet of Things Journal</i>, vol. 11, no. 20,
  pp. 32617–32630, Oct. 15, 2024.
---
## Overview

This work proposes a communication-efficient Split Learning framework for resource-constrained Internet of Things (IoT) environments. The proposed approach introduces caching and model customization to reduce communication overhead while enabling personalized models for heterogeneous clients.

## Resources

- **DOI:** [Link](https://doi.org/10.1109/JIOT.2024.3424660)
- **PDF:** [Download Paper](/files/Beyond_Federated_Learning_for_IoT_Efficient_Split_Learning_With_Caching_and_Model_Customization.pdf)
- **Code:** [https://github.com/Manisha-IITBH/FedSL-IoT](https://github.com/S3-Lab-IIT/Efficient-Split-Learning.git)
- **Slides:** [Presentation](/files/ManishaChawla_Wholesome_Thesis_Presentation_2024.pdf)
- **BibTeX:** [Download](/files/fedsl.bib)

## Abstract

Distributed training of deep learning models on resource-constrained devices has gained significant interest. Training data-driven deep-learning models collaboratively using Federated learning (FL) and Split learning (SL) have become the most popular ways to do this task. We aim to optimize these techniques by reducing device computation during parallel model training, and reducing high communication costs due to the frequent exchange of models, data, and gradients. This paper proposes Efficient Split Learning (ESL), a novel approach addressing these challenges through three key ideas: (1) a key-value store for caching and sharing intermediate activations across clients, significantly reducing redundant computations and communication during the training phase, (2) customization of state-of-the-art neural networks for split learning context, and (3) personalized training allowing clients to learn individual models tailored to their specific data distributions.

Existing communication-efficient FL/SL methods trade accuracy to reduce communication. In contrast, ESL achieves significant communication reduction while maintaining high accuracy. Extensive experimentation on real-world federated benchmarks for image classification and 3D segmentation demonstrates significant improvements over baseline FL techniques: ESL achieves a reduction in computation by 1623x for image classification and 23.9x for 3D segmentation on resource constrained devices. Additionally, it reduces communication traffic, during training, between clients and the server by 3.92x for image classification and 1.3x for 3D segmentation, while improving average accuracy by 35\% and 31\%, respectively. Furthermore, when compared to the baseline SL approaches, ESL reduces communication traffic during training by 100x and improves accuracy by an average of 34.8\%.
