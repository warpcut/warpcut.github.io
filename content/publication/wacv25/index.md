---
title: "ReC-TTT: Contrastive Feature Reconstruction for Test-Time Training"
authors:
- admin
- Sergio Mascetti
- Jose Dolz
- Christian Desrosiers
author_notes:
- "Corresponding author"
date: "2025-03-03T00:00:00Z"
doi: "https://doi.org/10.1007/978-3-031-44521-7_13"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-03-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Winter Conference on Applications of Computer Vision 2025"
publication_short: "WACV25"

abstract: "The remarkable progress in deep learning (DL) showcases outstanding results in various computer vision tasks. However, adaptation to real-time variations in data distributions remains an important challenge. Test-Time Training (TTT) was proposed as an effective solution to this issue, which increases the generalization ability of trained models by adding an auxiliary task at train time and then using its loss at test time to adapt the model. Inspired by the recent achievements of contrastive representation learning in unsupervised tasks, we propose ReC-TTT, a test-time training technique that can adapt a DL model to new unseen domains by generating discriminative views of the input data. ReC-TTT uses cross-reconstruction as an auxiliary task between a frozen encoder and two trainable encoders, taking advantage of a single shared decoder. This enables, at test time, to adapt the encoders to extract features that will be correctly reconstructed by the decoder that, in this phase, is frozen on the source domain. Experimental results show that ReC-TTT achieves better results than other state-of-the-art techniques in most domain shift classification challenges."

# Summary. An optional shortened abstract.
summary: "ReC-TTT is a test-time training method that improves model adaptation to unseen domains using cross-reconstruction between encoders and a shared decoder. It outperforms existing methods in domain shift classification tasks."

tags:
- Test-time training
- Contrastive feature reconstruction
- Domain Adaptation
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: https://openaccess.thecvf.com/content/WACV2025/papers/Colussi_ReC-TTT_Contrastive_Feature_Reconstruction_for_Test-Time_Training_WACV_2025_paper.pdf
url_code: https://github.com/warpcut/ReC-TTT
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'ReC-TTT Framework'
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
