---
title: "Which Transformer to Favor: A Comparative Analysis of Efficiency in Vision Transformers"
authors:
- "Tobias Nauen"
- "Sebastian Palacio"
- "Federico Raue"
- "Andreas Dengel"
date: "2025-01-01T00:00:00Z"
url_pdf: "https://openaccess.thecvf.com/content/WACV2025/papers/Nauen_Which_Transformer_to_Favor_A_Comparative_Analysis_of_Efficiency_in_WACV_2025_paper.pdf"
url_code: "https://github.com/tobna/WhatTransformerToFavor"
links:
  - name: Paper Website
    url: "https://nauen-it.de/publications/wtf-benchmark/"
doi: "10.1109/wacv61041.2025.00676"
publication_types: ["1"]
publication: "Winter Conference on Applications of Computer Vision (WACV) 2025"

abstract: Self-attention in Transformers comes with a high computational cost because of their quadratic computational complexity, but their effectiveness in addressing problems in language and vision has sparked extensive research aimed at enhancing their efficiency. However, diverse experimental conditions, spanning multiple input domains, prevent a fair comparison based solely on reported results, posing challenges for model selection. To address this gap in comparability, we perform a large-scale benchmark of more than 45 models for image classification, evaluating key efficiency aspects, including accuracy, speed, and memory usage. Our benchmark provides a standardized baseline for efficiency-oriented transformers. We analyze the results based on the Pareto front – the boundary of optimal models. Surprisingly, despite claims of other models being more efficient, ViT remains Pareto optimal across multiple metrics. We observe that hybrid attention-CNN models exhibit remarkable inference memory- and parameter-efficiency. Moreover, our benchmark shows that using a larger model in general is more efficient than using higher resolution images. Thanks to our holistic evaluation, we provide a centralized resource for practitioners and researchers, facilitating informed decisions when selecting or developing efficient transformers.

summary: A comprehensive benchmark and analysis of more than 45 transformer models for image classification to evaluate their efficiency, considering various performance metrics. We find the optimal architectures to use and uncover that model-scaling is more efficient than image scaling.
---

### Citation

T. C. Nauen, S. Palacio, F. Raue, A. Dengel, „Which Transformer to Favor: A Comparative Analysis of Efficiency in Vision Transformers“, IEEE/CVF Winter Conference on Applications of Computer Vision, WACV, 2025
