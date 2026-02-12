---
title: 'How to enhance causal discrimination of utterances: A case on affective reasoning'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hang Chen, Xinyu Yang, Jing Luo, Wenjing Zhu

# Author notes (optional)


date: '2023-12-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing
publication_short: EMNLP 2023 (main)

abstract: Our investigation into the Affective Reasoning in Conversation (ARC) task highlights the challenge of causal discrimination. Almost all existing models, including large language models (LLMs), excel at capturing semantic correlations within utterance embeddings but fall short in determining the specific causal relationships. To overcome this limitation, we propose the incorporation of i.i.d. noise terms into the conversation process, thereby constructing a structural causal model (SCM). It explores how distinct causal relationships of fitted embeddings can be discerned through independent conditions. To facilitate the implementation of deep learning, we introduce the cogn frameworks to handle unstructured conversation data, and employ an autoencoder architecture to regard the unobservable noise as learnable “implicit causes.” Moreover, we curate a synthetic dataset that includes i.i.d. noise. Through comprehensive experiments, we validate the effectiveness and interpretability of our approach.


tags:
  - Sentiment Analysis
  - Causal Discrimination

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.18653/v1/2023.emnlp-main.33

# Custom links
links:
  - type: pdf
    url: "https://aclanthology.org/2023.emnlp-main.33.pdf"
  - type: code
    url: "https://github.com/Zodiark-ch/masters-of-our-EMNLP2023-papers"


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

