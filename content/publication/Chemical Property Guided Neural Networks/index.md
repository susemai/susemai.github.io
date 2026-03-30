---
title: 'Chemical Property-Guided Neural Networks for Naphtha Composition Prediction'
authors:
  - Chonghyo Joo
  - Jeongdong Kim
  - Hyungtae Cho
  - Jaewon Lee
  - Sungho Suh
  - Junghwan Kim

author_notes: ''


date: '2023-06-02T00:00:00Z'
doi: '10.48550/arXiv.2306.01391'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-06-02T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'IEEE International Conference on Industrial Informatics 2023 (INDIN)'
publication_short: ''

abstract: 'The naphtha cracking process heavily relies on the composition of naphtha, which is a complex blend of different hydrocarbons. Predicting the naphtha composition accurately is crucial for efficiently controlling the cracking process and achieving maximum performance. Traditional methods, such as gas chromatography and true boiling curve, are not feasible due to the need for pilot-plant-scale experiments or cost constraints. In this paper, we propose a neural network framework that utilizes chemical property information to improve the performance of naphtha composition prediction. Our proposed framework comprises two parts: a Watson K factor estimation network and a naphtha composition prediction network. Both networks share a feature extraction network based on Convolutional Neural Network (CNN) architecture, while the output layers use Multi-Layer Perceptron (MLP) based networks to generate two different outputs - Watson K factor and naphtha composition. The naphtha composition is expressed in percentages, and its sum should be 100%. To enhance the naphtha composition prediction, we utilize a distillation simulator to obtain the distillation curve from the naphtha composition, which is dependent on its chemical properties. By designing a loss function between the estimated and simulated Watson K factors, we improve the performance of both Watson K estimation and naphtha composition prediction. The experimental results show that our proposed framework can predict the naphtha composition accurately while reflecting real naphtha chemical properties.'


# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: 'https://arxiv.org/abs/2306.01391'
url_pdf: 'https://arxiv.org/abs/2306.01391'
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
