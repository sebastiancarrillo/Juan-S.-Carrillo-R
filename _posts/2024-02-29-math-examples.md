---
title: "Automatic Glaucoma Detection from Fundus Images"
date: 2024-02-29
categories:
  - blog
tags:
  - glaucoma
  - medical imaging
  - computer vision
  - deep learning
---

In this post, I highlight the work presented in [this IEEE paper](https://ieeexplore.ieee.org/abstract/document/8730250), which proposes a computational tool for the automatic detection of glaucoma using fundus images.

Glaucoma remains one of the leading causes of irreversible blindness, particularly in individuals over 40 years of age. The situation is especially concerning in countries like Colombia, where the prevalence of the disease is high and the number of ophthalmologists per capita is insufficient to meet the need for early screening and diagnosis.

This study addresses the issue by leveraging fundus imaging—a low-cost, portable, and widely used technique for glaucoma screening. The proposed system introduces improvements in several key areas:

- **Optic Disc Segmentation**: Enhanced accuracy in segmenting the optic disc, improving upon prior literature benchmarks.
- **Cup Segmentation**: A novel thresholding approach is applied to delineate the optic cup.
- **C/D Ratio Analysis**: Introduction of a new measure for the cup-to-disc size ratio, which is critical in glaucoma diagnosis.

The system was trained and tested using a dataset of fundus images collected in collaboration with the *Center of Prevention and Attention of Glaucoma* in Bucaramanga, Colombia. The tool achieved an impressive **88.5% success rate** in glaucoma detection, highlighting its potential for aiding mass screening in resource-limited settings.

This work demonstrates the potential of combining image processing techniques with domain-specific knowledge to create accessible diagnostic tools that can have real-world medical impact.

> IEEE Reference:  
> J. A. Díaz-Peñaloza, J. S. Carrillo and J. A. Pérez, "Automatic Glaucoma Detection from Fundus Images," *2019 XXII Symposium on Image, Signal Processing and Artificial Vision (STSIVA)*, Bucaramanga, Colombia, 2019, pp. 1-5.  
> doi: [10.1109/STSIVA.2019.8730250](https://doi.org/10.1109/STSIVA.2019.8730250)

