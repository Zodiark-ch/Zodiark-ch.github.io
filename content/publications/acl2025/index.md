---
title: 'Quantifying Semantic Emergence in Language Models'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hang Chen, Xinyu Yang, Jiaying Zhu, Wenya Wang

# Author notes (optional)


date: '2025-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-07-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics
publication_short: ACL 2025 (main)

abstract: Large language models (LLMs) are widely recognized for their exceptional capacity to capture semantics meaning. Yet, there remains no established metric to quantify this capability. In this work, we introduce a quantitative metric, Information Emergence (IE), designed to measure LLMs’ ability to extract semantics from input tokens. We formalize “semantics” as the meaningful information abstracted from a sequence of tokens and quantify this by comparing the entropy reduction observed for a sequence of tokens (macro-level) and individual tokens (micro-level). To achieve this, we design a lightweight estimator to compute the mutual information at each transformer layer, which is agnostic to different tasks and language model architectures. We apply IE in both synthetic in-context learning (ICL) scenarios and natural sentence contexts. Experiments demonstrate informativeness and patterns about semantics. While some of these patterns confirm the conventional prior linguistic knowledge, the rest are relatively unexpected, which may provide new insights.


tags:
  - Large Language Models
  - Evaluation
  - LLM Emergence

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.18653/v1/2025.acl-long.588

# Custom links
links:
  - type: pdf
    url: "https://aclanthology.org/2025.acl-long.588.pdf"
  - type: code
    url: https://github.com/Zodiark-ch/Emergence-of-LLMs


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---

