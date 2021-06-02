---
title: Denoising Score Matching for Uncertainty Quantification @ Machine Learning Club

event: Machine Learning Club
event_url: mlclub.net

location: Online

summary: A presentation of my network for Uncertainty Quantification in Inverse Problems with Denoising Score Matching.
abstract: "Deep neural networks have proven extremely efficient at solving a wide range of inverse problems, but most often the uncertainty on the solution they provide is hard to quantify. In this work, we propose a generic Bayesian framework for solving inverse problems, in which we limit the use of deep neural networks to learning a prior distribution on the signals to recover. We adopt recent denoising score matching techniques to learn this prior from data, and subsequently use it as part of an annealed Hamiltonian Monte-Carlo scheme to sample the full posterior of image inverse problems. We apply this framework to Magnetic Resonance Image (MRI) reconstruction and illustrate how this approach not only yields high quality reconstructions but can also be used to assess the uncertainty on particular features of a reconstructed image."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-11-18T18:00:00Z"
date_end: "2020-11-18T19:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: [Zaccharie Ramzi, Benjamin Remy]
tags: [MRI, Deep Learning]

# Is this a featured talk? (true/false)
featured: false


url_code: ""
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
projects:
- fastmri
---
