---
title: "SHINE: SHaring the INverse Estimate from the forward pass for bi-level optimization and implicit models"
date: 2021-06-01
publishDate: 2021-06-02T11:05:57.993509Z
authors: ["Zaccharie Ramzi", "Florian Mannel", "Shaojie Bai", "Jean-Luc Starck", "Philippe Ciuciu", "Thomas Moreau"]
publication_types: ["2"]
abstract: "In recent years, implicit deep learning has emerged as a method to increase the depth of deep neural networks. While their training is memory-efficient, they are still significantly slower to train than their explicit counterparts. In Deep Equilibrium Models (DEQs), the training is performed as a bi-level problem, and its computational complexity is partially driven by the iterative inversion of a huge Jacobian matrix. In this paper, we propose a novel strategy to tackle this computational bottleneck from which many bi-level problems suffer. The main idea is to use the quasi-Newton matrices from the forward pass to efficiently approximate the inverse Jacobian matrix in the direction needed for the gradient computation. We provide a theorem that motivates using our method with the original forward algorithms. In addition, by modifying these forward algorithms, we further provide theoretical guarantees that our method asymptotically estimates the true implicit gradient. We empirically study this approach in many settings, ranging from hyperparameter optimization to large Multiscale DEQs applied to CIFAR and ImageNet. We show that it reduces the computational cost of the backward pass by up to two orders of magnitude. All this is achieved while retaining the excellent performance of the original models in hyperparameter optimization and on CIFAR, and giving encouraging and competitive results on ImageNet."
featured: false
publication: ""
url_pdf: "http://arxiv.org/abs/2106.00553"
---
