---
title: "LoRIS - Weakly-Supervised Anomaly Detection for Ultrasound Images"
authors:
- admin
- Dragan Ahmetovic
- Gabriele Civitarese
- Claudio Bettini
- Aiman Solyman
- Roberta Gualtierotti
- Flora Peyvandi
- Sergio Mascetti
author_notes:
- "Corresponding author"
date: 2024-10-05
doi: "https://doi.org/10.1007/978-3-031-44521-7_13"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Simplifying Medical Ultrasound"
publication_short: "ASMUS24"

abstract: "This paper presents LoRIS (Localized Reconstruction-by-Inpainting with Single-mask), a novel weakly-supervised anomaly detection technique designed to identify knee joint recess distension in musculoskeletal ultrasound images, which are noisy and unbalanced (as distended cases are rarer). In this context, supervised techniques require a high number of annotated images of both classes (distended and non-distended). On the other hand, we show that existing unsupervised anomaly detection techniques, which can be trained with images from a single class, are ineffective and often unable to correctly localize the anomaly. To overcome these issues, LoRIS is trained with nondistended images only and uses the recess bounding box as location prior to guide the reconstruction. Experimental results show that LoRIS outperforms state-of-the-art unsupervised anomaly detection techniques. When compared to a state-of-the-art fully supervised solution, LoRIS presents similar performance but has two key advantages: during training it requires images from a single class only, and it also outputs the recess segmentation, without the need for segmentation annotations."

# Summary. An optional shortened abstract.
summary: LoRIS is a weakly-supervised anomaly detection method for knee ultrasound images. Trained only on nondistended cases, it uses a location prior to guide reconstruction and detect anomalies. It outperforms unsupervised methods and matches supervised ones—without needing segmentation annotations or images from both classes.

tags:
- Anomaly detection
- Weak-supervision
- Ultrasound images
featured: False

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/chapter/10.1007/978-3-031-73647-6_19
url_code: https://github.com/warpcut/LoRIS
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'LoRIS architecture'
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
