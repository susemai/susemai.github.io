---
title: "OA-CutMix: Correcting the Label Bias of CutMix"
authors:
  - "Tobias Nauen"
  - "Stanislav Frolov"
  - "Federico Raue"
  - "Brian B. Moser"
  - "Andreas Dengel"
date: "2026-06-04T00:00:00Z"
url_pdf: "http://arxiv.org/pdf/2606.04820"
url_code: "https://github.com/tobna/oa-cutmix"
links:
  - name: Paper Website
    url: "https://nauen-it.de/publications/oa-cutmix/"
publication_types: ["1"]
publication: "35th International Conference on Artificial Neural Networks (ICANN 2026)"

abstract: "CutMix has become the de facto standard mixing augmentation, yet its label assignment rests on a flawed assumption: The area of the pasted patch faithfully reflects its semantic contribution to the mixed image. In practice, however, patches frequently land on background regions, assigning label credit to classes whose objects are not visible. The mean discrepancy of the CutMix label and the semantic object area is 21.5%. In 17% of samples an image contributes zero visible object pixels yet receives nonzero label weight. We propose Object-Aware CutMix (OA-CutMix), which corrects this bias by replacing the area-based CutMix weight with one derived from precomputed segmentation masks, assigning labels in proportion to the visible object area each image contributes to the mix. The image mixing procedure is left entirely unchanged. We evaluate OA-CutMix against 10+ static and dynamic mixing methods across 4 architectures and 6 datasets. OA-CutMix consistently achieves the highest accuracy over all tasks, outperforming even dynamic mixing methods, but at a fraction of the training-time cost. Improvements are largest for small objects, where the label bias from CutMix is greatest. Thus, correcting the label is sufficient to match or exceed the performance of methods modifying the image mixing algorithm."

summary: CutMix assigns labels by patch area, not by visible object content, a systematic bias that mislabels 21.5% of samples and creates ghost labels in 17%. OA-CutMix replaces the label with one derived from object area, leaving the image mixing unchanged. It matches or beats 10+ static and dynamic mixing methods across 4 architectures and 6 datasets.
---

### Citation

T. C. Nauen, S. Frolov, F. Raue, B. B. Moser, A. Dengel, „OA-CutMix: Correcting the Label Bias of CutMix“, 35th International Conference on Artificial Neural Networks (ICANN 2026), September 2026
