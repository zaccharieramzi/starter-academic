---
title: Benchopt
summary: A framework for reproducible and extensible optimization benchmarks.
tags:
- Optimization
date: "2019-12-08T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

url_code: "https://github.com/benchopt"
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

My particular focus in Benchopt was the design of a deep learning benchmark.
In its first iteration it features 2 frameworks, PyTorch and TensorFlow, 3 datasets, 3 CNNs and 4 optimizers.
I am dedicated to growing it to a larger scale, i.e. with ImageNet, handling multiple GPUs (even maybe multiple nodes), including Jax.
Another improvement direction is to build a benchmark that includes the hyperparameter tuning in the overall optimization.
