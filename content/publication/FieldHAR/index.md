---
title: 'FieldHAR: A Fully Integrated End-to-end RTL Framework for Human Activity Recognition with Neural Networks from Heterogeneous Sensors'
authors:
  - Mengxi Liu
  - Bo Zhou
  - Zimin Zhao
  - Hyeonseok Hong
  - Hyun Kim
  - Sungho Suh
  - Vitor Fortes Rey
  - Paul Lukowicz


author_notes: ''


date: '2023-05-22T00:00:00Z'
doi: 'https://arxiv.org/abs/2305.12824'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-05-22T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: '34th IEEE International Conference on Application-specific Systems Architectures and Processors (ASAP)'
publication_short: ''

abstract: 'In this work, we propose an open-source scalable end-to-end RTL framework FieldHAR, for complex human activity recognition (HAR) from heterogeneous sensors using artificial neural networks (ANN) optimized for FPGA or ASIC integration. FieldHAR aims to address the lack of apparatus to transform complex HAR methodologies often limited to offline evaluation to efficient run-time edge applications. The framework uses parallel sensor interfaces and integer-based multi-branch convolutional neural networks (CNNs) to support flexible modality extensions with synchronous sampling at the maximum rate of each sensor. To validate the framework, we used a sensor-rich kitchen scenario HAR application which was demonstrated in a previous offline study. Through resource-aware optimizations, with FieldHAR the entire RTL solution was created from data acquisition to ANN inference taking as low as 25\% logic elements and 2\% memory bits of a low-end Cyclone IV FPGA and less than 1% accuracy loss from the original FP32 precision offline study. The RTL implementation also shows advantages over MCU-based solutions, including superior data acquisition performance and virtually eliminating ANN inference bottleneck.'


# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: 'https://arxiv.org/abs/2305.12824'
url_pdf: 'https://arxiv.org/abs/2305.12824'
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
