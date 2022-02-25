---
title: PhD Defense

event:
event_url:

location: NeuroSpin Amphitheater

summary: My PhD defense (the video is actually a rehearsal since the live did not work during the actual presentation).
abstract: "Magnetic Resonance Imaging (MRI) is one of the most prominent imaging techniques in the world. Its main purpose is to probe soft tissues in a non-invasive and non-ionizing way. However, its wider adoption is hindered by an overall high scan time. In order to reduce this duration, several approaches have been proposed, among which Parallel Imaging (PI) and Compressed Sensing (CS) are the most important. Using these techniques, MR data can be acquired in a highly compressed way which allows the reduction of acquisition times. However, the algorithms typically used to reconstruct the MR images from these undersampled data are slow and underperform in highly accelerated scenarios.
In order to address these issues, unrolled neural networks have been introduced. The core idea of these models is to unroll the iterations of classical reconstruction algorithms into a finite computation graph. The main objective of this PhD thesis is to propose new architecture designs for acquisition scenarios which deviate from the typical Cartesian 2D sampling. To this end, we first review a handful of neural networks for MRI reconstruction. After selecting the best performer, the PDNet, we extend it to two contexts: the fastMRI 2020 reconstruction challenge and the 3D non-Cartesian data problem. We also chose to address the concerns of many regarding the clinical applicability of deep learning for medical imaging. We do so by proposing ways to build robust and inspectable models, but also by simply testing the trained networks in out-of-distribution settings. Finally, after noticing how the implicit deep learning framework can help implement deeper MRI reconstruction models, we introduce a new acceleration method (called SHINE) for the training of such models."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-02-18T14:00:00Z"
date_end: "2022-02-18T16:30:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: [Zaccharie Ramzi]
tags: [Deep Learning, Software Engineering]

# Is this a featured talk? (true/false)
featured: false

url_code: "https://github.com/zaccharieramzi/PhD-defense-presentation"
url_pdf: "https://github.com/zaccharieramzi/PhD-defense-presentation/blob/master/main.pdf"
url_slides: ""
url_video: "https://www.youtube.com/watch?v=idaodn9sNaQ&t=2932s"

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
---
