---
title: SHINE @ SIAM MDS 2022

event: SIAM MDS 2022
event_url: https://www.siam.org/conferences/cm/conference/mds22

location: San Diego & Online

summary: "A presentation of my work on bi-level problems and Deep EQuilibrium networks: SHINE."
abstract: "Implicit deep learning has emerged as a method to increase the effective depth of deep neural networks. While their training is memory-efficient, they are still slower to train than their explicit counterparts. In Deep Equilibrium Models (DEQs), the training is performed as a bi-level problem, and its computational complexity is partially driven by the iterative inversion of a huge Jacobian matrix. In this paper, we propose a novel strategy to tackle this computational bottleneck from which many bi-level problems suffer. The main idea is to use the quasi-Newton matrices from the forward pass to efficiently approximate the inverse Jacobian matrix in the direction needed for the gradient computation. We provide a theorem that motivates using our method with the original forward algorithms. In addition, by modifying these forward algorithms, we further provide theoretical guarantees that our method asymptotically estimates the true implicit gradient. We empirically study this approach and the recent Jacobian-Free method in different settings, ranging from hyperparameter optimization to large Multiscale DEQs (MDEQs) applied to CIFAR and ImageNet. Both methods reduce significantly the computational cost of the backward pass. While SHINE has a clear advantage on hyperparameter optimization problems, both methods attain similar computational performances for larger scale problems such as MDEQs at the cost of a limited performance drop compared to the original models."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-09-30T16:00:00Z"
date_end: "2022-09-30T17:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: [Zaccharie Ramzi]
tags: [DEQ, Deep Learning]

# Is this a featured talk? (true/false)
featured: false

url_code: "https://github.com/zaccharieramzi/shine"
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# -
---
