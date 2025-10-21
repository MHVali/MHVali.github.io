---
title: "Interpretable Latent Space Using Space-Filling Curves for Phonetic Analysis in Voice Conversion"
authors:
- Mohammad Hassan Vali
- Tom Bäckström
date: "2023-08-24"

# Schedule page publish date (NOT publication's date).
# publishDate: "2025-09-30"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
# publication: ""
# publication_short: ""

abstract: Vector quantized variational autoencoders (VQ-VAE) are well-known deep generative models, which map input data to a latent space that is used for data generation. Such latent spaces are unstructured and can thus be difficult to interpret. Some earlier approaches have introduced a structure to the latent space through supervised learning by defining data labels as latent variables. In contrast, we propose an unsupervised technique incorporating space-filling curves into vector quantization (VQ), which yields an arranged form of latent vectors such that adjacent elements in the VQ codebook refer to similar content. We applied this technique to the latent codebook vectors of a VQ-VAE, which encode the phonetic information of a speech signal in a voice conversion task. Our experiments show there is a clear arrangement in latent vectors representing speech phones, which clarifies what phone each latent vector corresponds to and facilitates other detailed interpretations of latent vectors.

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
  url: https://www.isca-archive.org/interspeech_2023/vali23_interspeech.html
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
