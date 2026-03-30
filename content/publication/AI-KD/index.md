---
title: 'AI-KD: Adversarial learning and Implicit regularization for self-Knowledge Distillation'
authors:
  - Hyungmin Kim
  - Sungho Suh
  - Sunghyun Baek
  - Daehwan Kim
  - Daun Jeong
  - Hansang Cho
  - Junmo Kim


author_notes: ''


date: '2024-06-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.knosys.2024.111692'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Knowledge-Based Systems, 2024'
publication_short: ''

abstract: 'We present a novel adversarial penalized self-knowledge distillation method, named adversarial learning and implicit regularization for self-knowledge distillation (AI-KD), which regularizes the training procedure by adversarial learning and implicit distillations. Our model not only distills the deterministic and progressive knowledge which are from the pre-trained and previous epoch predictive probabilities but also transfers the knowledge of the deterministic predictive distributions using adversarial learning. The motivation is that the self-knowledge distillation methods regularize the predictive probabilities with soft targets, but the exact distributions may be hard to predict. Our proposed method deploys a discriminator to distinguish the distributions between the pre-trained and student models while the student model is trained to fool the discriminator in the trained procedure. Thus, the student model not only can learn the pre-trained model’s predictive probabilities but also align the distributions between the pre-trained and student models. We demonstrate the effectiveness of the proposed method with network architectures on multiple datasets and show the proposed method achieves better performance than existing approaches.'

# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: ''
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S0950705124003277'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
