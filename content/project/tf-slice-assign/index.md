---
title: tf-slice-assign
summary: A utility for tensor slice assignment in TensorFlow.
tags:
- Deep Learning
- TensorFlow
date: "2020-06-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

url_code: "https://github.com/zaccharieramzi/tf-slice-assign"
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

TensorFlow has a "dramatic flaw"; you can't assign to a tensor slice.

This project aims at reducing the pain of users wanting to use `scatter_nd_*` type of functions.
