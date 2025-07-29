---
title: "MIAS-SAM: Medical Image Anomaly Segmentation without thresholding"
authors:
- admin
- Dragan Ahmetovic
- Sergio Mascetti
author_notes:
- "Corresponding author"
date: "2025-07-25T00:00:00Z"
doi: "https://arxiv.org/pdf/2505.22762"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "British Machine Vision Conferenece 2025"
publication_short: "BMVC25"

abstract: "This paper presents MIAS-SAM, a novel approach for the segmentation of anomalous regions in medical images. MIAS-SAM uses a patch-based memory bank to store relevant image features, which are extracted from normal data using the SAM encoder. At inference time, the embedding patches extracted from the SAM encoder are compared with those in the memory bank to obtain the anomaly map. Finally, MIAS-SAM computes the center of gravity of the anomaly map to prompt the SAM decoder, obtaining an accurate segmentation from the previously extracted features. Differently from prior works, MIAS-SAM does not require to define a threshold value to obtain the segmentation from the anomaly map. Experimental results conducted on three publicly available datasets, each with a different imaging modality (Brain MRI, Liver CT, and Retina OCT) show accurate anomaly segmentation capabilities measured using DICE score."

# Summary. An optional shortened abstract.
summary: "MIAS-SAM exploits the zero-shot segmentation capabilities of segment-anything to obtain accurate anomaly segmentations in an unsupervised way."

tags:
- Anomaly detection
- Segmentation
- Segment Anything
- Medical Imaging
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/pdf/2505.22762'
url_code: 'https://github.com/warpcut/MIAS-SAM'
url_dataset: 'https://github.com/DorisBao/BMAD'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'MIAS-SAM framework'
  focal_point: "center"
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
#slides: AIxIA
---
