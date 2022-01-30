---
title: "NC-PDNet: a Density-Compensated Unrolled Network for 2D and 3D non-Cartesian MRI Reconstruction"
date: 2021-01-01
publishDate: 2021-07-07T09:12:08.104625Z
authors: ["Zaccharie Ramzi", "Jean-Luc Starck", "Chaithya G R", "Philippe Ciuciu"]
publication_types: ["3"]
abstract: "Deep Learning has become a very promising avenue for magnetic resonance image~(MRI) reconstruction.  In this work, we explore the potential of unrolled networks for non-Cartesian acquisition settings.  We design the NC-PDNet (Non-Cartesian Primal Dual Network), the first density-compensated (DCp) unrolled neural network, and validate the need for its key components via an ablation study. Moreover, we conduct some generalizability experiments to test this network in out-of-distribution settings, for example training on knee data and validating on brain data. The results show that NC-PDNet outperforms baseline (U-Net, Deep image prior) models both visually and quantitatively in all settings. In particular, in the 2D multi-coil acquisition scenario, the NC-PDNet provides up to a 1.2dB improvement in peak signal-to-noise ratio (PSNR) over baseline networks, while also allowing a gain of at least 1dB in PSNR in generalization settings. We provide the open-source implementation of NC-PDNet, and in particular the Non-uniform Fourier Transform in TensorFlow, tested on 2D multi-coil and 3D single-coil k-space data."
featured: false
publication: ""
url_pdf: "https://hal.inria.fr/hal-03188997"
---

