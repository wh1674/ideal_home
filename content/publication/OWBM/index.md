---
title: "OWBM: OSNR-Aware Wavelength Allocation and Branching Methods for Multicast Routing in Custom Topology-Based Optical Network-on-Chips"
authors:
- Yong Wook Kim
- Tae Hee Han

date: "2024-04-01T00:00:00Z"
doi: "10.1109/ACCESS.2024.3384555"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, Vol. 12, pp. 49508-49527, Apr. 2024"
publication_short: ""

abstract: In light of the rapid advancements in big data and artificial intelligence applications, heterogeneous computing (HGC) platforms that integrate diverse computing units have gained traction with the aim of achieving energy efficiency and high performance. A custom topology-based optical network-on-chip (ONoC) that provides unparalleled diversity between computing nodes is expected to be the next-generation communication infrastructure for meeting the bandwidth and energy efficiency requirements of HGC. One of the recent challenges in the field of ONoCs is to accelerate multicast routing via wavelength division multiplexing (WDM), which dispatches data parallelly across non-interfering wavelengths. The optimization of network throughput and laser power efficiency revolves around two factors the number of wavelengths and optical signal-to-noise ratio (OSNR). Accordingly, we introduce OSNR-aware wavelength allocation and branching methods for multicast routing (OWBM) tailored to an HGC platform in a customized ONoC. OWBM increases the wavelength resource efficiency by establishing independent routing paths in the partitioned destination nodes such that each routing path is guaranteed to be prevented from overlapping among the partitions. Moreover, the adaptive branching mechanism of OWBM adaptively selects path-based routing and OSNR-aware routing on the fly according to the wavelength allocation cases, further augmenting the throughput and laser power efficiency. Consequently, OWBM outperformed conventional tree- and path-based multicast approaches by elevating the average throughput by 47.39% and curbing the laser power consumption by up to 35.92% in various convolutional neural network benchmarks. Compared with the existing ONoC wavelength allocation techniques, the OWBM demonstrated a maximum of 42.46% enhanced wavelength utilization on a 64-core HGC platform.


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
