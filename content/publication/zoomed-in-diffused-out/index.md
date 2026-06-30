---
title: "When 512×512 is not Enough: Local Degradation-Aware Multi-Diffusion for Extreme Image Super-Resolution"
authors:
  - "Brian B. Moser"
  - "Stanislav Frolov"
  - "Tobias Nauen"
  - "Federico Raue"
  - "Andreas Dengel"
date: "2025-09-14T00:00:00Z"
url_pdf: "https://arxiv.org/pdf/2411.12072"
url_code: "https://github.com/Brian-Moser/zido"
doi: "https://doi.org/10.1109/ICIP55913.2025.11084710"
publication_types: ["1"]
publication: "2025 IEEE International Conference on Image Processing (ICIP)"

abstract: "Large-scale, pre-trained Text-to-Image (T2I) diffusion models have gained significant popularity in image generation tasks and have shown unexpected potential in image Super-Resolution (SR). However, most existing T2I diffusion models are trained with a resolution limit of 512x512, making scaling beyond this resolution an unresolved but necessary challenge for image SR. In this work, we introduce a novel approach that, for the first time, enables these models to generate 2K, 4K, and even 8K images without any additional training. Our method leverages MultiDiffusion, which distributes the generation across multiple diffusion paths to ensure global coherence at larger scales, and local degradation-aware prompt extraction, which guides the T2I model to reconstruct fine local structures according to its low-resolution input. These innovations unlock higher resolutions, allowing T2I diffusion models to be applied to image SR tasks without limitation on resolution."

summary: We extend pretrained super-resolution models to larger images by using local-aware prompts.
---

### Citation

S. Frolov, B. B. Moser, T. C. Nauen, F. Raue, A. Dengel, „When 512×512 is Not Enough: Local Degradation-Aware Multi-Diffusion for Extreme Image Super-Resolution“, IEEE International Conference on Image Processing (ICIP), 2025
