---
title: 'Federated Ensemble YOLOv5 – A Better Generalized Object Detection Algorithm'
authors:
  - Vinit Hegiste
  - Tatjana Legler
  - Martin Ruskowski


author_notes: ''


date: '2023-11-08T00:00:00Z'
doi: 'doi.org/10.1109/FMEC59375.2023.10305958'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 'International Conference on Fog and Mobile Edge Computing'
publication_short: ''

abstract: 'Federated learning (FL) has gained significant traction as a privacy-preserving algorithm, but the underlying resemblances of federated learning algorithms like Federated averaging (FedAvg) or Federated SGD (Fed SGD) to ensemble learning algorithms has not been fully explored. The purpose of this paper is to examine the application of FL to object detection as a method to enhance generalizability, and to compare its performance against a centralized training approach for an object detection algorithm. Specifically, we investigate the performance of a YOLOv5 model trained using FL across multiple clients and employ a random sampling strategy without replacement, so each client holds a portion of the same dataset used for centralized training. Our experimental results showcase the superior efficiency of the FL object detectors global model in generating accurate bounding boxes for unseen objects, with the test set being a mixture of objects from two distinct clients not represented in the training dataset. These findings suggest that FL can be viewed from an ensemble algorithm perspective, akin to a synergistic blend of Bagging and Boosting techniques. As a result, FL can be seen not only as a method to enhance privacy, but also as a method to enhance the performance of a machine learning model.'


# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: 'https://ieeexplore.ieee.org/abstract/document/10305958'
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10305958'
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
