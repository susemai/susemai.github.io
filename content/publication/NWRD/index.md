---
title: 'The NWRD Dataset: An Open-Source Annotated Segmentation Dataset of Diseased Wheat Crop'
authors:
  - Hirra Anwar
  - Saad Ullah Khan
  - Muhammad Mohsin Ghaffar
  - Muhammad Fayyaz
  - Muhammad Jawad Khan
  - Christian Weis
  - Norbert Wehn
  - Faisal Shafait

author_notes: ''


date: '2023-08-04T00:00:00Z'
doi: '10.3390/s23156942'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: 'Sensors, 2023'
publication_short: ''

abstract: 'Wheat stripe rust disease (WRD) is extremely detrimental to wheat crop health, and it severely affects the crop yield, increasing the risk of food insecurity. Manual inspection by trained personnel is carried out to inspect the disease spread and extent of damage to wheat fields. However, this is quite inefficient, time-consuming, and laborious, owing to the large area of wheat plantations. Artificial intelligence (AI) and deep learning (DL) offer efficient and accurate solutions to such real-world problems. By analyzing large amounts of data, AI algorithms can identify patterns that are difficult for humans to detect, enabling early disease detection and prevention. However, deep learning models are data-driven, and scarcity of data related to specific crop diseases is one major hindrance in developing models. To overcome this limitation, in this work, we introduce an annotated real-world semantic segmentation dataset named the NUST Wheat Rust Disease (NWRD) dataset. Multileaf images from wheat fields under various illumination conditions with complex backgrounds were collected, preprocessed, and manually annotated to construct a segmentation dataset specific to wheat stripe rust disease. Classification of WRD into different types and categories is a task that has been solved in the literature; however, semantic segmentation of wheat crops to identify the specific areas of plants and leaves affected by the disease remains a challenge. For this reason, in this work, we target semantic segmentation of WRD to estimate the extent of disease spread in wheat fields. Sections of fields where the disease is prevalent need to be segmented to ensure that the sick plants are quarantined and remedial actions are taken. This will consequently limit the use of harmful fungicides only on the targeted disease area instead of the majority of wheat fields, promoting environmentally friendly and sustainable farming solutions. Owing to the complexity of the proposed NWRD segmentation dataset, in our experiments, promising results were obtained using the UNet semantic segmentation model and the proposed adaptive patching with feedback (APF) technique, which produced a precision of 0.506, recall of 0.624, and F1 score of 0.557 for the rust class.'

# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: ''
url_pdf: 'https://www.mdpi.com/1424-8220/23/15/6942'
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
