---
title: "Benchmarking MRI reconstruction neural networks on large public datasets"
date: 2020-01-01
publishDate: 2021-06-02T11:05:57.982877Z
authors: ["Zaccharie Ramzi", "Philippe Ciuciu", "Jean-Luc Starck"]
publication_types: ["2"]
abstract: "Deep learning is starting to offer promising results for reconstruction in Magnetic Resonance Imaging (MRI). A lot of networks are being developed, but the comparisons remain hard because the frameworks used are not the same among studies, the networks are not properly re-trained, and the datasets used are not the same among comparisons. The recent release of a public dataset, fastMRI, consisting of raw k-space data, encouraged us to write a consistent benchmark of several deep neural networks for MR image reconstruction. This paper shows the results obtained for this benchmark, allowing to compare the networks, and links the open source implementation of all these networks in Keras. The main finding of this benchmark is that it is beneficial to perform more iterations between the image and the measurement spaces compared to having a deeper per-space network."
featured: false
publication: "*Applied Sciences (Switzerland)*"
tags: ["deep learning", "fastmri", "image reconstruction", "mri", "neural networks", "oasis"]
url_pdf: "https://www.mdpi.com/2076-3417/10/5/1816"
doi: "10.3390/app10051816"
links:
    - name: Code
      url: "https://github.com/zaccharieramzi/fastmri-reproducible-benchmark"
---

