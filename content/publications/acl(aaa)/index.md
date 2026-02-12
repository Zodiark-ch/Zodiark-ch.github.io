---
title: 'Skill Path: Unveiling Language Skills from Circuit Graphs'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hang Chen, Xinyu Yang, Jiaying Zhu, Wenya Wang

# Author notes (optional)


date: '2026-01-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The Fortieth AAAI Conference on Artificial Intelligence
publication_short: AAAI (Oral)

abstract: Circuit graph discovery has emerged as a fundamental approach to elucidating the skill mechanistic of language models. Despite the output faithfulness of circuit graphs, they suffer from atomic ablation, which causes the loss of causal dependencies between connected components. In addition, their discovery process, designed to preserve output faithfulness, inadvertently captures extraneous effects other than an isolated target skill. To alleviate these challenges, we introduce skill paths, which offer a more refined and compact representation by isolating individual skills within a linear chain of components. To enable skill path extracting from circuit graphs, we propose a three-step framework, consisting of decomposition, pruning, and post-hoc causal mediation. In particular, we offer a complete linear decomposition of the transformer model which leads to a disentangled computation graph. After pruning, we further adopt causal analysis techniques, including counterfactuals and interventions, to extract the final skill paths from the circuit graph. To underscore the significance of skill paths, we investigate three generic language skills—Previous Token Skill, Induction Skill, and In-Context Learning Skill—using our framework. Experiments support two crucial properties of these skills, namely stratification and inclusiveness.


tags:
  - Large Language Models
  - Mechanistic Interpretability
  - Circuit Discovery

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 

# Custom links
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2410.01334"
  - type: code
    url: "https://github.com/Zodiark-ch/Language-Skill-of-LLMs"

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

