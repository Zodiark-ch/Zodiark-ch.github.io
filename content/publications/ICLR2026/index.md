---
title: 'CLUE: Conflict-guided Localization for LLM Unlearning Framework'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hang Chen, Jiaying Zhu, Xinyu Yang, Wenya Wang 

# Author notes (optional)


date: '2026-01-26T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The Fourteenth International Conference on Learning Representations
publication_short: ICLR

abstract: The LLM unlearning aims to eliminate the influence of undesirable data without affecting causally unrelated information. This process typically involves using a forget set to remove target information, alongside a retain set to maintain non-target capabilities. While recent localization-based methods demonstrate promise in identifying important nodes (neurons) to be unlearned, they fail to disentangle nodes responsible for forgetting undesirable knowledge or retaining essential skills, often treating them as a single entangled group. As a result, these methods apply uniform interventions, risking catastrophic over-forgetting or incomplete erasure of the target knowledge. To address this, we turn to circuit discovery, a mechanistic interpretability technique, and propose the Conflict-guided Localization for LLM Unlearning framEwork (CLUE). This framework identifies the forget and retain circuit composed of important nodes, and then the circuits are transformed into conjunctive normal forms (CNF). The assignment of each node in the CNF satisfiability solution reveals whether it should be forgotten or retained. We then provide targeted fine-tuning strategies for different categories of nodes. Extensive experiments demonstrate that, compared to existing localization methods, CLUE achieves superior forget efficacy and retain utility through precise neural localization.


tags:
  - LLM Unlearning
  - Mechanistic Interpretability
  - Circuit Discovery

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 

# Custom links
links:
  - type: pdf
    url: "https://openreview.net/pdf?id=jtRYvazBWv"
  - type: code
    url: "https://github.com/Zodiark-ch/CLUE"


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

