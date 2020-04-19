---
title: "An Inexact Augmented Lagrangian Framework for Nonconvex Optimization with Nonlinear Constraints"
authors: "Mehmet Fatih Sahin, Armin Eftekhari, Ahmet Alacaoglu, Fabian Latorre and Volkan Cevher"
venue: "NeurIPS 2019"
date: 2019-10-19
pdf: "http://papers.nips.cc/paper/9545-an-inexact-augmented-lagrangian-framework-for-nonconvex-optimization-with-nonlinear-constraints"
abstract: "We propose a practical inexact augmented Lagrangian method (iALM)
for nonconvex problems with nonlinear constraints. We characterize the total
computational complexity of our method subject to a verifiable geometric
condition, which is closely related to the Polyak-Lojasiewicz and
Mangasarian-Fromowitz conditions. In particular, when a first-order solver is
used for the inner iterates, we prove that iALM finds a first-order stationary
point with $\mathcal{O}(1/ϵ^3)$ calls to the first-order oracle. {If, in addition, the
problem is smooth and} a second-order solver is used for the inner iterates,
iALM finds a second-order stationary point with $\mathcal{O}(1/ϵ^5)$ calls to the
second-order oracle. These complexity results match the known theoretical
results in the literature. We also provide strong numerical evidence on
large-scale machine learning problems, including the Burer-Monteiro
factorization of semidefinite programs, and a novel nonconvex relaxation of the
standard basis pursuit template. For these examples, we also show how to verify
our geometric condition."
draft: false
---
