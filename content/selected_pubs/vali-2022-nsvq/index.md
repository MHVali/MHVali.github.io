---
title: "NSVQ: Noise Substitution in Vector Quantization for Machine Learning"
authors:
- Mohammad Hassan Vali
- Tom Bäckström
date: "2022-01-28"

# Schedule page publish date (NOT publication's date).
# publishDate: "2025-09-30"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: Machine learning algorithms have been shown to be highly effective in solving optimization problems in a wide range of applications. Such algorithms typically use gradient descent with backpropagation and the chain rule. Hence, the backpropagation fails if intermediate gradients are zero for some functions in the computational graph, because it causes the gradients to collapse when multiplying with zero. Vector quantization is one of those challenging functions for machine learning algorithms, since it is a piece-wise constant function and its gradient is zero almost everywhere. A typical solution is to apply the straight through estimator which simply copies the gradients over the vector quantization function in the backpropagation. Other solutions are based on smooth or stochastic approximation. This study proposes a vector quantization technique called NSVQ, which approximates the vector quantization behavior by substituting a multiplicative noise so that it can be used for machine learning problems. Specifically, the vector quantization error is replaced by product of the original error and a normalized noise vector, the samples of which are drawn from a zero-mean, unit-variance normal distribution. We test our proposed NSVQ in three scenarios with various types of applications. Based on the experiments, the proposed NSVQ achieves more accuracy and faster convergence in comparison to the straight through estimator, exponential moving averages, and the MiniBatchKmeans approaches.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

# tags:
# - Large Language Models

featured: true

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

links:
# - type: preprint
#   provider: arxiv
#   id: 1512.04133v1
# - type: code
#   url: https://github.com/HugoBlox/hugo-blox-builder
# - type: slides
#   url: https://www.slideshare.net/
# - type: dataset
#   url: "#"
# - type: poster
#   url: "#"
- type: custom
  label: Link
  url: https://ieeexplore.ieee.org/abstract/document/9696322
# - type: source
#   url: "https://arxiv.org/pdf/2509.26469"
# - type: video
#   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs. -->

<!-- > [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example. -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
