---
title: XPDNet @ NeurIPS 2020 Medical Imaging Workshop

event: NeurIPS 2020 Medical Imaging Workshop
event_url: https://sites.google.com/view/med-neurips-2020

location: Online

summary: A presentation of my network for MRI reconstruction: the XPDNet.
abstract: "In classical Magnetic Resonance Imaging reconstruction, slow iterative non-linear algorithms using manually crafted priors are applied to obtain the anatomical image from under-sampled Fourier measurements. In addition they have to deal with an incomplete knowledge of the exact measurement operator. Deep Learning methods, and in particular, unrolled networks, have allowed to alleviate those issues. In this talk we will see how Deep Learning enables us to: i) learn an optimal optimization scheme, ii) learn a prior from the data and iii) learn how to refine our knowledge of the measurements operator. We show the results of this approach on the fastMRI 2020 brain reconstruction challenge where we secured the 2nd spot in both the 4x and 8x acceleration tracks."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-12-12T19:25:00Z"
date_end: "2020-12-12T19:35:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: [Zaccharie Ramzi]
tags: [MRI, Deep Learning]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image courtesy of fastmri.org'
  focal_point: Smart

url_code: "https://github.com/zaccharieramzi/fastmri-reproducible-benchmark"
url_pdf: ""
url_slides: "https://docs.google.com/presentation/d/10Ax9Q0IL2WPkmLtQ9x3ajKGFDghLgY69s2a5wi5gfaE/edit?usp=sharing"
url_video: "https://slideslive.com/38942421/xpdnet-for-brain-multicoil-mri-reconstruction"

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
projects:
- fastmri
---
