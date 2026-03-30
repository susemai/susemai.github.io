---
title: 'A Knowledge Distillation framework for Multi-Organ Segmentation of Medaka Fish in Tomographic Image'
authors:
  - Jwalin Bhatt
  - Yaroslav Zharov
  - Sungho Suh
  - Tilo Baumbach
  - Vincent Heuveline
  - Paul Lukowicz



author_notes: ''


date: '2023-02-24T00:00:00Z'
doi: '10.48550/arXiv.2302.12562'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'IEEE International Symposium on Biomedical Imaging (ISBI) 2023'
publication_short: ''

abstract: Morphological atlases are an important tool in organismal studies, and modern high-throughput Computed Tomography (CT) facilities can produce hundreds of full-body high-resolution volumetric images of organisms. However, creating an atlas from these volumes requires accurate organ segmentation. In the last decade, machine learning approaches have achieved incredible results in image segmentation tasks, but they require large amounts of annotated data for training. In this paper, we propose a self-training framework for multi-organ segmentation in tomographic images of Medaka fish. We utilize the pseudo-labeled data from a pretrained Teacher model and adopt a Quality Classifier to refine the pseudo-labeled data. Then, we introduce a pixel-wise knowledge distillation method to prevent overfitting to the pseudo-labeled data and improve the segmentation performance. The experimental results demonstrate that our method improves mean Intersection over Union (IoU) by 5.9% on the full dataset and enables keeping the quality while using three times less markup.


# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
url: ''
url_pdf: ''
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
