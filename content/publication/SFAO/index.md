---
title: "SFAO: Sign-Flipping-Aware Optimization for Early-Stopping of Binarized Neural Networks"
authors:
- Ju Yeon Kang
- Chang Ho Ryu
- Suk Bong Kang
- Tae Hee Han

date: "2023-11-01T00:00:00Z"
doi: "10.1109/ACCESS.2023.3332472"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "**
IEEE Access, Vol. 11, pp. 128306-128315, Nov. 2023**"
publication_short: ""

abstract: One of the vital challenges for the binary neural networks (BNNs) is improving their inference performance by expanding their data representation capabilities for figuring out delicate patterns and nuances in the data. Addressing the explosive computational demands on neural network training is essential to guarantee sustainable development and scalable deployment. However, mitigating the increase in the computational cost during the training phase is critical for ensuring sustainability and scalability during deployment. In this study, an advanced sign-flipping-aware optimizer (SFAO) that focuses on BNNs was introduced to diminish the computational burden. SFAO balanced the model performance and computational cost through sign-flipping-aware updating rules throughout the training of BNNs. SFAO optimizer, tailored for BNNs with binary weight-specific updating rules, considerably reduced the computing resources needed for training on the CIFAR-10 dataset. Specifically, it surpassed the conventional full-precision updating rule by reducing the total instruction count by 21.89%. In contrast, SFAO showed a marginal 0.44% decline in the image classification accuracy relative to the updating rules for the full-precision parameters. Furthermore, the implementation of early stopping using the sign flip rate led to a notable reduction of 9.37% in the average computation time per network for the ImageNet dataset.


tags:
- Source Themes
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
  caption: ''
  focal_point: ""
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
slides: example
---