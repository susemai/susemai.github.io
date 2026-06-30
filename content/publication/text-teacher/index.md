---
title: "TextTeacher: What Can Language Teach About Images?"
authors:
  - "Tobias Nauen"
  - "Stanislav Frolov"
  - "Brian B. Moser"
  - "Federico Raue"
  - "Ahmed Anwar"
  - "Andreas Dengel"
date: "2026-05-20T00:00:00Z"
url_pdf: "https://openreview.net/pdf?id=Xwb0aEUwKh"
url_code: "https://github.com/tobna/TextTeacher"
links:
  - name: Paper Website
    url: "https://nauen-it.de/publications/text-teacher/"
publication_types: ["2"]
publication: "Transactions on Machine Learning Research (TMLR)"

abstract: "The platonic representation hypothesis suggests that sufficiently large models converge to a shared representation geometry, even across modalities. Motivated by this, we ask: Can the semantic knowledge of a language model efficiently improve a vision model? As an answer, we introduce TextTeacher, a simple auxiliary objective that injects text embeddings as additional information into image classification training. TextTeacher uses readily available image captions, a pre-trained and frozen text encoder, and a lightweight projection to produce semantic anchors that efficiently guide representations during training while leaving the inference-time model unchanged. On ImageNet with standard ViT backbones, TextTeacher improves accuracy by up to +2.7 percentage points (p.p.) and yields consistent transfer gains (on average +1.0 p.p.) under the same recipe and compute. It outperforms vision knowledge distillation, yielding more accuracy at a constant compute budget or similar accuracy, but 33% faster. Our analysis indicates that TextTeacher acts as a feature-space preconditioner, shaping deeper layers in the first stages of training, and aiding generalization by supplying complementary semantic cues. TextTeacher adds negligible overhead, requires no costly multimodal training of the target model and preserves the simplicity and latency of pure vision models."

summary: We use a frozen text encoder on image captions as a lightweight training-time auxiliary objective for image classifiers. The text components are dropped at inference, leaving a fast, unimodal vision model. Accuracy on ImageNet improves by up to +2.7 p.p. and downstream transfer by +1.0 p.p. on average, outperforming vision knowledge distillation at a fraction of the compute.
---

### Citation

T. C. Nauen, S. Frolov, B. B. Moser, F. Raue, A. Anwar, A. Dengel, „TextTeacher: What Can Language Teach About Images?“, Transactions on Machine Learning Research (TMLR), May 2026
