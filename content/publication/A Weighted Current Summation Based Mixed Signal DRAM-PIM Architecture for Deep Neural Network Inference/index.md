---
title: 'A Weighted Current Summation Based Mixed Signal DRAM-PIM Architecture for Deep Neural Network Inference'
authors:
  - Chirag Sudarshan
  - Taha Soliman
  - Jan Lappas
  - Christian Weis
  - Mohammad Hassani Sadi
  - Matthias Jung
  - Andre Guntoro
  - Norbert Wehn

author_notes: ''


date: '2022-04-25T00:00:00Z'
doi: '10.1109/JETCAS.2022.3170235'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*IEEE Journal on Emerging and Selected Topics in Circuits and Systems* (Volume: 12, Issue: 2, June 2022)'
publication_short: ''

abstract: Processing-in-Memory (PIM) is an emerging approach to bridge the memory-computation gap. One of the major challenges of PIM architectures in the scope of Deep Neural Network (DNN) inference is the implementation of area-intensive Multiply-Accumulate (MAC) units in memory technologies, especially for DRAM-based PIMs. The DRAM architecture restricts the integration of DNN computation units near the area optimized commodity DRAM Sub-Array (SA) or Primary Sense Amplifier (PSA) region, where the data parallelism is maximum and the data movement cost is minimum. In this paper, we present a novel DRAM-based PIM architecture that is based on bit-decomposed MAC operation and Weighted Current Summation (WCS) technique to implement the MAC unit with minimal additional circuitry in the PSA region by leveraging on mixed-signal design. The architecture presents a two-stage design that employs light-weight current mirror based analog units near the SAs in the PSA region, whereas all the other substantial logic is integrated near the bank peripheral region. Hence, our architecture attains a balance between the data parallelism, data movement energy and area optimization. For an 8-bit CNN inference, our novel 8Gb DRAM PIM device achieves a peak performance of 142.8GOPS while consuming a power of 756.76mW, which results in an energy efficiency of 188.8GOPS/W. The area overhead of such an 8Gb device for a 2ynm DRAM technology is 12.63% in comparison to a commodity 8Gb DRAM device.

# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#   url: ""
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
