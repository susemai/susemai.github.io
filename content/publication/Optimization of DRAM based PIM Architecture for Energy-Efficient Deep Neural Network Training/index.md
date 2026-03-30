---
title: 'Optimization of DRAM based PIM Architecture for Energy-Efficient Deep Neural Network Training'
authors:
  -   Chirag Sudarshan
  -   Mohammad Hassani Sadi
  -   Christian Weis
  -   Norbert Wehn

author_notes: ''


date: '2022-11-11T00:00:00Z'
doi: '10.1109/ISCAS48785.2022.9937832'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: '2022 IEEE International Symposium on Circuits and Systems (ISCAS)'
publication_short: ''

abstract: 'Deep Neural Network (DNN) training consumes high-energy. On the other hand, DNNs deployed on edge devices demand very high-energy efficiency. In this context, Processing-in-Memory (PIM) is an emerging compute paradigm that bridges the memory-computation gap to improve the energy-efficiency. DRAMs are one such memory type employed for designing energy-efficient PIM architectures for DNN training. One of the major issues of DRAM-PIM architectures designed for DNN training is the high number of internal data accesses within a bank between the memory arrays and the PIM computation units (e.g. 51% more than inference). These internal data accesses in the state-of-the-art DRAM PIM architectures consume very high energy compared to computation units. Hence, it is important to reduce the internal data access energy within the DRAM bank for further improving the energy efficiency of DRAMPIM architectures. We present three novel optimizations that together reduce the internal data access energy up to 81.54%. Our first optimization modifies the bank data access circuit to enable partial accesses of data instead of the conventional fixed granularity accesses, thereby exploiting the available sparsity during training. The second optimization is to have a dedicated low-energy region within the DRAM bank that has low capacitive load of global wires and shorter data movement. Finally, we propose a 12-bit high dynamic range floating-point format called TinyFloat that reduces the total number of data access energy by 20% compared to IEEE 754 half and single precision.'

# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: ''
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
