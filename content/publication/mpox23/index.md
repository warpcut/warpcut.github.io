---
title: "A Transfer Learning and Explainable Solution to Detect mpox from Smartphones images"
authors:
- Mattia Giovanni Campana
- admin
- Franca Delmastro
- Sergio Mascetti
- Elena Pagani
date: "2024-01-06T00:00:00Z"
doi: "https://doi.org/10.1016/j.pmcj.2023.101874"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-11-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Pervasive and Mobile Computing"
publication_short: "PMC"

abstract: "In recent months, the monkeypox (mpox) virus -- previously endemic in a limited area of the world -- has started spreading in multiple countries until being declared a ``public health emergency of international concern'' by the World Health Organization. The alert was renewed in February 2023 due to a persisting sustained incidence of the virus in several countries and worries about possible new outbreaks. Low-income countries with inadequate infrastructures for vaccine and testing administration are particularly at risk. 
A symptom of mpox infection is the appearance of skin rashes and eruptions, which can drive people to seek medical advice. A technology that might help perform a preliminary screening based on the aspect of skin lesions is the use of Machine Learning for image classification. However, to make this technology suitable on a large scale, it should be usable directly on mobile devices of people, with a possible notification to a remote medical expert. 
In this work, we investigate the adoption of Deep Learning to detect mpox from skin lesion images. The proposal leverages Transfer Learning to cope with the scarce availability of mpox image datasets. As a first step, a homogenous, unpolluted, dataset is produced by manual selection and preprocessing of available image data. It will also be released publicly to researchers in the field. Then, a thorough comparison is conducted amongst several Convolutional Neural Networks, based on a 10-fold stratified cross-validation. The best models are then optimized through quantization for use on mobile devices; measures of classification quality, memory footprint, and processing times validate the feasibility of our proposal. Additionally, the use of eXplainable AI is investigated as a suitable instrument to both technically and clinically validate classification outcomes."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Machine Learning
- Audio and Speech Processing
- XAI
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://pdf.sciencedirectassets.com/273419/1-s2.0-S1574119224X00024/1-s2.0-S1574119223001323/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEO%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIGHuFP4nO44qk09r9Rs6SiTWEFqzFFTgwGyDXUhm%2FfIiAiEA6Fbc9NFPjxFIcYH0ju9x94bgMlelFr77bTYT4AgxxzUqvAUIp%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDDI8Jf17MRMnIXd0fCqQBcuIq5Q0SCuI0NQMFhQw5jyHTfKb2SGKvbXeGgyE%2FXBdp%2FFPci0m4%2FQyXK%2BF7jgJxtIL1XGvJUYwrt4BM9RAMxXxXK1e1ahWI6ccs3l5Abm8Xba%2BeU%2Bp7H8ByLWMOPiwebQRCIpPUszcygbbY%2FOzXb5s0%2B2VKdrznhhIb9nqQwKEqTeK0WxAy00hFTxoOlUs7P8CNO1YdF60YLfsIXJKYKlJkrpNblkt50f107LDgpUk2966Slz4wz0Fst7YsDzxq2sJZi9imoxUR%2F1fCIqc3%2BHDJK2lnxJKzwjr5Ag0qKuChN238lNF5EI0cWjvHMmQ9iTxFTNJTFpWp8yQA71JlIlHFfX%2BogNrJd4hr3chZtymMpwEcDpdc7fHywPaodolIwLfIYqjn%2BSS4UnjnJTk7QqcpyHPLVkn%2F28K1IpkaXHCSZvJtf%2FdKuyH2IYw2Cix%2BoxlT%2F2ExHc%2FlakG2fNor3nzaK9Ft8drwO0u7DUkSZuRCN8h0sVm3trm3ccS9mKLXOT8E70Z8%2FZp%2BfoxE6vlwlH4ffksmUx0SqHfqyrOEgDx6BsXz7gNvjm0yIryrnRwq5vb6xnqagmT9BGWIse9i63VJhjAmmRK96gOSxiOQxbxnVyUighQoYp7%2B2BPyHvTGSAzPwDuZyOroylv1EuT%2FcPZQr6VQgY2gbUX2wS0SnRLFOD6bHtmDWJquCUW2UO0IJkh2uVGEcbhGGA6bG96Hsl4LdrFLV6AsOwjfq4U3eaKZaKSCSvlg31tCeoQnhUI9rtUPTHRiClEiop0rVsHfeeALo7XOr2rBA18LEZkGTyz1r%2BpYvAsG3X1LhC8qRwN5%2FiR5ECw7Fjx8A2Ezo5Par7nf%2F%2BheGJcRtKUXx8cjwq3MMf8zq0GOrEBzKzNAbZ5p4sgt4XXfAqpZPjixpVFIWiH5paD2t8m1o%2FnAzF1aypT75LxmIDXPZmdqxEQnzVL7AP4QBslgiLCiMt0R3Lc5SbwSxwYE8adcOyvAGaTpEh1%2B9BuGO9rTG0O0s1%2FRpimvIETgdmraclF3wlzMvVmuVQm7POmZptSSvcGajrwC%2FRXkxi9yzF%2B3uExzVPJZ4t7v%2FLdzKjnsWok%2BUU2P5JDgvqQApabYH7SSEAH&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20240126T151402Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY7KUEKLXB%2F20240126%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=7905b7b65227319ca6b4a39c6e2c1a5f8afbe692cf7cf4414fb7b2bbb7a48e0b&hash=bdd9ac85930d7df46d69b1da237cf108726e5e558f644110042c6ca38889fa17&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1574119223001323&tid=spdf-e1f97cbc-4c87-47c7-b513-1f0d93c59589&sid=a3f9941d2d50f54c713a6909c0a3b8679a24gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=19075a5201580256520757&rr=84b9b40e0ead7138&cc=ca'
url_code: 'https://zenodo.org/records/7981159'
url_dataset: 'https://zenodo.org/records/7948350'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
