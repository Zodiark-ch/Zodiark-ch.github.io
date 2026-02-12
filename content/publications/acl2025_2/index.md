---
title: 'Debiasing the Fine-Grained Classification Task in LLMs with Bias-Aware PEFT'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Daiying Zhao, Xinyu Yang, Hang Chen

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

abstract: Fine-grained classification via LLMs is susceptible to more complex label biases compared to traditional classification tasks. Existing bias mitigation strategies, such as retraining, post-hoc adjustment, and parameter-efficient fine-tuning (PEFT) are primarily effective for simple classification biases, such as stereotypes, but fail to adequately address prediction propensity and discriminative ability biases. In this paper, we analyze these two bias phenomena and observe their progressive accumulation from intermediate to deeper layers within LLMs. To mitigate this issue, we propose a bias-aware optimization framework that incorporates two distinct label balance constraints with a PEFT strategy targeting an intermediate layer. Our approach adjusts less than 1% of the model’s parameters while effectively curbing bias amplification in deeper layers. Extensive experiments conducted across 12 datasets and 5 LLMs demonstrate that our method consistently outperforms or matches the performance of full-parameter fine-tuning and LoRA, achieving superior results with lower perplexity.


tags:
  - Large Language Models
  - Sentiment Analysis

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 

# Custom links
links:
  - type: pdf
    url: "https://aclanthology.org/2025.acl-long.717.pdf"


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

