---
title: "Distill the Best, Ignore the Rest: A Study in Latent Dataset Distillation on Core-Sets"
authors:
  - "Brian B. Moser"
  - "Federico Raue"
  - "Tobias Nauen"
  - "Stanislav Frolov"
  - "Andreas Dengel"
date: "2025-06-30T00:00:00Z"
url_pdf: "https://arxiv.org/pdf/2411.12115"
url_code: "https://github.com/Brian-Moser/prune_and_distill"
doi: "https://doi.org/10.1109/IJCNN64981.2025.11229108"
publication_types: ["1"]
publication: "International Joint Conference on Neural Networks 2025"

abstract: 'Latent dataset distillation, which exploits pre-trained generative priors, has gained significant interest in recent years because it can be applied agnostic to any distillation algorithm and addresses two significant limitations of classical distillation algorithms: cross-architecture generalization and high-resolution synthesis. However, existing approaches typically distill from the entire dataset, potentially including non-beneficial samples. We introduce a novel "Prune First, Distill After" framework that systematically prunes datasets via loss-based sampling prior to latent distillation. By leveraging pruning before classical distillation techniques and generative priors, we create a representative coreset that leads to enhanced generalization for unseen architectures - a significant challenge of current distillation methods. More specifically, our proposed framework significantly boosts distilled quality, achieving up to a 5.2 percentage points accuracy increase even with substantial dataset pruning, i.e., removing 80% of the original dataset prior to distillation. Overall, our experimental results highlight the advantages of our easy-sample prioritization and cross-architecture robustness, paving the way for more effective and high-quality dataset distillation.'

summary: We improve dataset distillation by distilling only a representative coreset.
---

### Citation

B. B. Moser, F. Raue, T. C. Nauen, S. Frolov, A. Dengel, „Distill the Best, Ignore the Rest: A Study in Latent Dataset Distillation on Core-Sets“, International Joint Conference on Neural Networks, 2025
