---
title: 'Learning from the Best: Contrastive Representations Learning Across Sensor Locations for Wearable Activity Recognitiony'
authors:
  - Vitor Fortes Rey
  - Sungho Suh
  - Paul Lukowicz


author_notes: ''


date: '2022-10-04T00:00:00Z'
doi: '10.48550/arXiv.2210.01459'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'International Symposium on Wearable Computers, 2022'
publication_short: ''

abstract: We address the well-known wearable activity recognition problem of having to work with sensors that are non-optimal in terms of information they provide but have to be used due to wearability/usability concerns (e.g. the need to work with wrist-worn IMUs because they are embedded in most smart watches). To mitigate this problem we propose a method that facilitates the use of information from sensors that are only present during the training process and are unavailable during the later use of the system. The method transfers information from the source sensors to the latent representation of the target sensor data through contrastive loss that is combined with the classification loss during joint training. We evaluate the method on the well-known PAMAP2 and Opportunity benchmarks for different combinations of source and target sensors showing average (over all activities) F1 score improvements of between 5% and 13% with the improvement on individual activities, particularly well suited to benefit from the additional information going up to between 20% and 40%.

# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: 'https://arxiv.org/abs/2210.01459'
url_pdf: 'https://arxiv.org/pdf/2210.01459'
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
