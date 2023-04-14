---
title: jz-hydra-submitit-launcher
summary: A plugin to launch SLURM jobs on Jean Zay using hydra and its submitit launcher, with reasonable defaults.
tags:
- HPC
date: "2022-01-07T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

url_code: "https://github.com/zaccharieramzi/jz-hydra-submitit-launcher"
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

Using `hydra` and its `submitit` launcher, this plugin allows to launch SLURM jobs on Jean Zay with reasonable defaults.

Typically this means you could launch your `hydra` script `my_app.py` on Jean Zay with the following command:

```bash
hydra-submitit-launch my_app.py dev
```
