---
title: "CASR: Refining Action Segmentation via marginalizing frame-level causal relationships"
authors:
- Keqing Du, Xinyu Yang, Hang Chen

author_notes:
date: "2025-09-21T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-21T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Multimedia"
publication_short: "TMM"

abstract: Integrating deep learning and causal discovery has increased the necessity for a causal relationship between frames as evidence for explainability in Temporal Action Segmentation (TAS) tasks. However, frame-level causal relationships apparently emerge noise outside the segment, making it infeasible to suggest macro action relationships through frame relationships. To address this research gap, we propose a method of marginalizing frame-level noise relationships and introduce a Causal Abstraction Segmentation Refiner (CASR) to enhance the segmentation ability. Specifically, we retain all cross-segment relationships while discarding all inter-segment relationships over the frame-level model, satisfying a consistent mapping of causal abstraction in terms of action semantics from frames to segments. Given the pre-segmentation of the backbone, we treat the whitening frame relationships of the same and different segments in a video as positive and negative cases, respectively. Through contrastive learning, we identify whether each frame belongs to the corresponding segment, thereby enhancing the segmentation performance. In addition, we propose a loss function independent of the action segment engineer to evaluate the causal interpretability of segmentation results. Extensive experimental results on mainstream datasets indicate that our method not only significantly surpasses existing methods in action segmentation performance, but also performs better in evaluating causal models. Our CASR can be plugged into various action segmentation engineers (MS-TCN++, ASRF, C2F-TCN, CETNet) with different backbones.


tags:
- Temporal Action Segmentation
- Causal Model
featured: false

hugoblox:
  ids:
    doi: 



 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
slides: ""
---

