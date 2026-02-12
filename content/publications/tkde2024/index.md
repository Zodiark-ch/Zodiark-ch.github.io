---
title: "Learning a Structural Causal Model for Intuition Reasoning in Conversation"
authors:
- Hang Chen , Bingyu Liao , Jing Luo , Wenjing Zhu , and Xinyu Yang

author_notes:
date: "2024-01-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: " IEEE Transactions on Knowledge and Data Engineering"
publication_short: "TKDE"

abstract: Reasoning, a crucial aspect of NLP research, has not been adequately addressed by prevailing models including Large Language Model. Conversation reasoning, as a critical component of it, remains largely unexplored due to the absence of a well-designed cognitive model. In this article, inspired by intuition theory on conversation cognition, we develop a conversation cognitive model (CCM) that explains how each utterance receives and activates channels of information recursively. Besides, we algebraically transformed CCM into a structural causal model (SCM) under some mild assumptions, rendering it compatible with various causal discovery methods. We further propose a probabilistic implementation of the SCM for utterance-level relation reasoning. By leveraging variational inference, it explores substitutes for implicit causes, addresses the issue of their unobservability, and reconstructs the causal representations of utterances through the evidence lower bounds. Moreover, we constructed synthetic and simulated datasets incorporating implicit causes and complete cause labels, alleviating the current situation where all available datasets are implicit-causes-agnostic. Extensive experiments demonstrate that our proposed method significantly outperforms existing methods on synthetic, simulated, and real-world datasets. Finally, we analyze the performance of CCM under latent confounders and propose theoretical ideas for addressing this currently unresolved issue.


tags:
- Conversation
- Causal Discrimination
- Reasoning
featured: false

hugoblox:
  ids:
    doi: 10.1109/TKDE.2024.3352575

links:
  - type: pdf
    url: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10388481
  - type: code
    url: https://github.com/Zodiark-ch/masters-of-our-EMNLP2023-papers
 

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

