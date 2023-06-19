---
title: "Test like you Train in Implicit Deep Learning"
date: 2023-05-24
publishDate: 2023-05-24T11:05:57.983481Z
authors: ["Zaccharie Ramzi", "Pierre Ablin", "Gabriel Peyré", "Thomas Moreau"]
publication_types: ["1"]
abstract: "Implicit deep learning has recently gained popularity with applications ranging from
meta-learning to Deep Equilibrium Networks (DEQs). In its general formulation,
it relies on expressing some components of deep learning pipelines implicitly,
typically via a root equation called the inner problem. In practice, the solution
of the inner problem is approximated during training with an iterative procedure,
usually with a fixed number of inner iterations. During inference, the inner problem
needs to be solved with new data. A popular belief is that increasing the number of
inner iterations compared to the one used during training yields better performance.
In this paper, we question such an assumption and provide a detailed theoretical
analysis in a simple setting. We demonstrate that overparametrization plays a key
role: increasing the number of iterations at test time cannot improve performance
for overparametrized networks. We validate our theory on an array of implicit
deep-learning problems. DEQs, which are typically overparametrized, do not
benefit from increasing the number of iterations at inference while meta-learning,
which is typically not overparametrized, benefits from it."
featured: false
publication: submitted
url_pdf: "https://arxiv.org/pdf/2305.15042.pdf"
# links:
#     - name: tfkbnufft
#       url: "https://github.com/zaccharieramzi/tfkbnufft"
#     - name: Code
#       url: "https://github.com/zaccharieramzi/fastmri-reproducible-benchmark"
---

