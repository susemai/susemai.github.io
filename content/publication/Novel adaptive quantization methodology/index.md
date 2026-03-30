---
title: 'Novel adaptive quantization methodology for 8-bit floating-point DNN training'
authors:
  - Mohammad Hassani Sadi
  - Chirag Sudarshan
  - Norbert Wehn 

author_notes: ''


date: '2024-02-16T00:00:00Z'
doi: 'doi.org/10.1007/s10617-024-09282-2'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-02-16T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Design Automation for Embedded Systems, 2024'
publication_short: ''

abstract: 'There is a high energy cost associated with training Deep Neural Networks (DNNs). Off-chip memory access contributes a major portion to the overall energy consumption. Reduction in the number of off-chip memory transactions can be achieved by quantizing the data words to low data bit-width (E.g., 8-bit). However, low-bit-width data formats suffer from a limited dynamic range, resulting in reduced accuracy. In this paper, a novel 8-bit Floating Point (FP8) data format quantized DNN training methodology is presented, which adapts to the required dynamic range on-the-fly. Our methodology relies on varying the bias values of FP8 format to fit the dynamic range to the required range of DNN parameters and input feature maps. The range fitting during the training is adaptively performed by an online statistical analysis hardware unit without stalling the computation units or its data accesses. Our approach is compatible with any DNN compute cores without any major modifications to the architecture. We propose to integrate the new FP8 quantization unit in the memory controller. The FP32 data from the compute core are converted to FP8 in the memory controller before writing to the DRAM and converted back after reading the data from DRAM. Our results show that the DRAM access energy is reduced by 3.07 while using an 8-bit data format instead of using 32-bit. The accuracy loss of the proposed methodology with 8-bit quantized training is  for various networks with image and natural language processing datasets.'

# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: ''
url_pdf: 'https://link.springer.com/article/10.1007/s10617-024-09282-2'
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
