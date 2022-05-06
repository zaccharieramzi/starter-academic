---
title: "Denoising Score-Matching for Uncertainty Quantification in Inverse Problems"
date: 2020-01-01
publishDate: 2021-06-02T11:05:57.983289Z
authors: ["Zaccharie Ramzi", "Benjamin Remy", "Francois Lanusse", "Jean-Luc Starck", "Philippe Ciuciu"]
publication_types: ["1"]
abstract: "Deep neural networks have proven extremely efficient at solving a wide range of inverse problems, but most often the uncertainty on the solution they provide is hard to quantify. In this work, we propose a generic Bayesian framework for solving inverse problems, in which we limit the use of deep neural networks to learning a prior distribution on the signals to recover. We adopt recent denoising score matching techniques to learn this prior from data, and subsequently use it as part of an annealed Hamiltonian Monte-Carlo scheme to sample the full posterior of image inverse problems. We apply this framework to Magnetic Resonance Image (MRI) reconstruction and illustrate how this approach not only yields high quality reconstructions but can also be used to assess the uncertainty on particular features of a reconstructed image."
featured: false
publication: "*NeurIPS 2020 Deep Learning and Inverse Problems workshop*"
url_pdf: "http://arxiv.org/abs/2011.08698"
links:
    - name: Code
      url: "https://github.com/b-remy/score-estimation-comparison"
---

