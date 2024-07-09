---
title: "RL-Based Cache Replacement: A Modern Interpretation of Belady’s Algorithm With Bypass Mechanism and Access Type Analysis"
authors:
- Ho Jung Yoo
-Jeong Hun KIM
- Tae Hee Han

date: "2023-12-01T00:00:00Z"
doi: "10.1109/ACCESS.2023.3346790"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Access, Vol. 11, pp. 145238-145253, Dec. 2023 **Featured article**"
publication_short: ""

abstract: Belady’s algorithm is widely known as an optimal cache replacement policy. It has been the foundation of numerous recent studies on cache replacement policies, and most studies assume this as an upper limit. Despite its widespread adoption, we discovered opportunities to unleash the headroom by addressing cache access types and implementing cache bypass. In this study, we propose Stormbird, a cache replacement policy that synergistically integrates the extensions of Belady’s algorithm and the power of reinforcement learning. Reinforcement learning is well-suited for cache replacement policy problems owing to its ability to interact dynamically with the environment, adapt to changing access patterns, and optimize the maximum cumulative rewards. Stormbird utilizes several selected features from the reinforcement learning model to enhance the instructions per cycle efficiency while maintaining a low hardware area overhead. Furthermore, it considers cache access types and integrates dynamic set dueling techniques to improve the cache performance. For 2 MB last-level cache per core, Stormbird achieves an average instructions per cycle improvement of 0.13% over the previous state-of-the-art on a single-core system and 0.02% on a four-core system while simultaneously reducing hardware overhead by 62.5%. Stormbird incurs a low hardware overhead of only 10.5 KB for 2 MB last-level cache and can be implemented without using program counter values.


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
