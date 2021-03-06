---
title: "Learning the sampling density in 2D SPARKLING MRI acquisition for optimized image reconstruction"
date: 2021-01-01
publishDate: 2021-07-07T09:12:08.106651Z
authors: ["Chaithya G R", "Zaccharie Ramzi", "Philippe Ciuciu"]
publication_types: ["3"]
abstract: "The SPARKLING algorithm was originally developed for accelerated 2D magnetic resonance imaging (MRI) in the compressed sensing (CS) context. It yields non-Cartesian sampling trajectories that jointly fulfill a target sampling density while each individual trajectory complies with MR hardware constraints. However, the two main limitations of SPARKLING are first that the optimal target sampling density is unknown and thus a user-defined parameter and second that this sampling pattern generation remains disconnected from MR image reconstruction thus from the optimization of image quality. Recently, data-driven learning schemes such as LOUPE have been proposed to learn a discrete sampling pattern, by jointly optimizing the whole pipeline from data acquisition to image reconstruction. In this work, we merge these methods with a state-of-the-art deep neural network for image reconstruction, called XPDNet, to learn the optimal target sampling density. Next, this density is used as input parameter to SPARKLING to obtain 20x accelerated non-Cartesian trajectories. These trajectories are tested on retrospective compressed sensing (CS) studies and show superior performance in terms of image quality with both deep learning (DL) and conventional CS reconstruction schemes."
featured: false
publication: ""
tags: ["compressed sensing", "index terms-non-cartesian trajectories", "mri", "reconstruction networks"]
url_pdf: "https://hal.inria.fr/hal-03158831v2"
---

