---
title: 'Navigating by Old Maps: The Pitfalls of Static Mechanistic Localization in LLM Post-Training'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hang Chen, Jiaying Zhu, Hongyang Chen, Hongxu Liu, Xinyu Yang, Wenya Wang

# Author notes (optional)


date: '2026-05-07T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-07T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The Fortieth Annual Conference on Neural Information Processing Systems
publication_short: NeurIPS

abstract: The "Locate-then-Update" paradigm has become a predominant approach in the post-training of large language models (LLMs), identifying critical components via mechanistic interpretability for targeted parameter updates. However, this paradigm rests on a fundamental yet unverified assumption — can mechanisms derived from current static parameters reliably guide future dynamic parameter updates? To investigate this, we systematically track the structural evolution of Transformer circuits throughout the supervised fine-tuning (SFT) process, revealing the underlying dynamics of task mechanisms. We introduce three novel metrics — Circuit Distance, Circuit Stability, and Circuit Conflict — to analyze circuit evolution across three dimensions — neural migration, semantic stability, and cross-task interference. Our empirical results reveal that circuits inherently exhibit "Free Evolution" during parameter updates. Consequently, static mechanisms extracted from current states inevitably suffer from temporal latency, making them fundamentally inadequate for guiding future states. Moreover, by deconstructing the "illusion of effectiveness" in existing methods, this work underscores the necessity of "foresight" in mechanistic localization and proposes a predictive framework for future research.


tags:
  - Mechanistic Interpretability
  - Post-training
  - Circuit Discovery

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: 2605.06076

# Custom links
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2605.06076"
---
