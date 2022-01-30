---
title: "Hybrid learning of Non-Cartesian k-space trajectory and MR image reconstruction networks"
date: 2022-01-01
publishDate: 2022-01-30T18:28:26.133812Z
authors: ["Chaithya G R", "Zaccharie Ramzi", "Philippe Ciuciu"]
publication_types: ["3"]
abstract: "Compressed sensing (CS) in Magnetic resonance Imaging (MRI) essentially involves the optimization of 1) the sampling pattern in k-space under MR hardware constraints and 2) image reconstruction from the undersampled k-space data. Recently, deep learning methods have allowed the community to address both problems simultaneously, especially in the non-Cartesian acquisition setting. This paper aims to contribute to this field by tackling some major concerns in existing approaches. Regarding the learning of the sampling pattern, we perform ablation studies using parameter-free reconstructions like the density compensated (DCp) adjoint operator of the nonuniform fast Fourier transform (NUFFT) to ensure that the learned k-space trajectories actually sample the center of k-space densely. Additionally we optimize these trajectories by embedding a projected gradient descent algorithm over the hardware MR constraints. Later, we introduce a novel hybrid learning approach that operates across multiple resolutions to jointly optimize the reconstruction network and the k-space trajectory and present improved image reconstruction quality at 20-fold acceleration factor on T1 and T2-weighted images on the fastMRI dataset with SSIM scores of nearly 0.92-0.95 in our retrospective studies."
featured: false
publication: ""
url_pdf: "https://hal.inria.fr/hal-03394881"
---

