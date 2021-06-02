---
title: TFKBNUFFT
summary: An implementation of the NUFFT in TensorFlow.
tags:
- TensorFlow
- MRI
date: "2020-03-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

url_code: "https://github.com/zaccharieramzi/tfkbnufft"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The Non-Uniform Fast Fourier Transform (NUFFT) appears a lot in MRI when designing non-Cartesian acquisition trajectories.

In order to design differentiable physics-based models, it is important to have a differentiable efficient implementation of the NUFFT.

This project is an offspring of the excellent work done by Matthew Muckley in PyTorch; [torchkbnufft](https://github.com/mmuckley/torchkbnufft).

I was also happy to collaborate with [Chaithya G R](https://chaithyagr.github.io/) on this project, in particular receiving his help on density compensation and gradients with respect to the trajectory.
