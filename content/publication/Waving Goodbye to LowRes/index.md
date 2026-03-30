---
title: 'Waving Goodbye to Low-Res: A Diffusion-Wavelet Approach for Image Super-Resolution'
authors:
  - Brian B. Moser
  - Stanislav Frolov
  - Federico Raue
  - Sebastian Palacio
  - Andreas Dengel

author_notes: ''


date: '2024-09-09T00:00:00Z'
doi: 'doi.org/10.1109/IJCNN60899.2024.10651227'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-30T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: '2024 International Joint Conference on Neural Networks (IJCNN)'
publication_short: ''

abstract: 'Image Super-Resolution (SR) remains challenging, particularly in achieving high-quality details without extensive computational cost. Existing methods often struggle to balance the trade-off between image quality, especially in high-frequency details, and computational efficiency. In this paper, we present a novel Diffusion-Wavelet (DiWa) approach for bridging this gap. It leverages the strengths of diffusion models and discrete wavelet transformation. By enabling the diffusion model to operate in the frequency domain, our models effectively hallucinate highfrequency information for SR images on the wavelet spectrum, resulting in high-quality and detailed reconstructions in image space. Quantitatively, our method outperforms other state-ofthe-art diffusion-based SR methods, namely SR3 and SRDiff, regarding PSNR, SSIM, and LPIPS on both face (8x scaling) and general (4x scaling) SR benchmarks. Meanwhile, using the frequency domain allows us to use fewer parameters than the compared models: 92M parameters instead of 550M compared to SR3 and 9.3M instead of 12M compared to SRDiff. Additionally, DiWa outperforms other state-of-the-art generative methods on general SR datasets while saving inference time (ca. 250 %).'


# Summary. An optional shortened abstract.
summary:

tags:
#  - Source Themes
featured: false

# links:
# - name: ""
#url: 'https://ieeexplore.ieee.org/abstract/document/10651227'
url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10651227'
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
