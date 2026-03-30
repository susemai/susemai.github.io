---
title: 'ContextMix: A context-aware data augmentation method for industrial visual inspection systems'
authors:
  - Hyungmin Kim
  - Donghun Kim
  - Pyunghwan Ahn
  - Sungho Suh
  - Hansang Cho
  - Junmo Kim


author_notes: ''


date: '2024-05-01T00:00:00Z'
doi: 'https://doi.org/10.1016/j.engappai.2023.107842'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Engineering Applications of Artificial Intelligence, 2024'
publication_short: ''

abstract: 'While deep neural networks have achieved remarkable performance, data augmentation has emerged as a crucial strategy to mitigate overfitting and enhance network performance. These techniques hold particular significance in industrial manufacturing contexts. Recently, image mixing-based methods have been introduced, exhibiting improved performance on public benchmark datasets. However, their application to industrial tasks remains challenging. The manufacturing environment generates massive amounts of unlabeled data on a daily basis, with only a few instances of abnormal data occurrences. This leads to severe data imbalance. Thus, creating well-balanced datasets is not straightforward due to the high costs associated with labeling. Nonetheless, this is a crucial step for enhancing productivity. For this reason, we introduce ContextMix, a method tailored for industrial applications and benchmark datasets. ContextMix generates novel data by resizing entire images and integrating them into other images within the batch. This approach enables our method to learn discriminative features based on varying sizes from resized images and train informative secondary features for object recognition using occluded images. With the minimal additional computation cost of image resizing, ContextMix enhances performance compared to existing augmentation techniques. We evaluate its effectiveness across classification, detection, and segmentation tasks using various network architectures on public benchmark datasets. Our proposed method demonstrates improved results across a range of robustness tasks. Its efficacy in real industrial environments is particularly noteworthy, as demonstrated using the passive component dataset.'

# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: ''
url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S0952197623020262'
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
