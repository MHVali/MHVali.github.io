---
title: "Unsupervised Panoptic Interpretation of Latent Spaces in GANs Using Space-Filling Vector Quantization"
authors:
- Mohammad Hassan Vali
- Tom Bäckström
date: "2025-06-25"

# Schedule page publish date (NOT publication's date).
# publishDate: "2025-09-30"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: Generative adversarial networks (GANs) learn a latent space whose samples can be mapped to real-world images. Such latent spaces are difficult to interpret. Some earlier supervised methods aim to create an interpretable latent space or discover interpretable directions, which requires exploiting data labels or annotated synthesized samples for training. However, we propose using a modification of vector quantization called space-filling vector quantization (SFVQ), which quantizes the data on a piece-wise linear curve. SFVQ can capture the underlying morphological structure of the latent space, making it interpretable. We apply this technique to model the latent space of pre-trained StyleGAN2 and BigGAN networks on various datasets. Our experiments show that the SFVQ curve yields a general interpretable model of the latent space such that it determines which parts of the latent space correspond to specific generative factors. Furthermore, we demonstrate that each line of the SFVQ curve can potentially refer to an interpretable direction for applying intelligible image transformations. We also demonstrate that the points located on an SFVQ line can be used for controllable data augmentation.

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
  url: https://openreview.net/forum?id=SEJatSGZX8&referrer=%5Bthe%20profile%20of%20Mohammad%20Hassan%20Vali%5D(%2Fprofile%3Fid%3D~Mohammad_Hassan_Vali1)
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
