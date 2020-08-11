---
title: "Efficient Proximal Mapping of the 1-path-norm of Shallow Networks"
authors: "Fabian Latorre, Paul Rolland, Nadav Hallak and Volkan Cevher"
venue: "ICML 2020"
date: 2020-07-02
pdf: "https://arxiv.org/abs/2007.01003"
draft: false
---
We demonstrate two new important properties of the 1-path-norm of shallow
neural networks. First, despite its non-smoothness and non-convexity it
allows a closed form proximal operator which can be efficiently computed,
allowing the use of stochastic proximal-gradient-type methods for regularized
empirical risk minimization. Second, when the activation functions is
differentiable, it provides an upper bound on the Lipschitz constant of the
network. Such bound is tighter than the trivial layer-wise product of Lipschitz
constants, motivating its use for training networks robust to adversarial
perturbations. In practical experiments we illustrate the advantages of using
the proximal mapping and we compare the robustness-accuracy trade-off induced
by the 1-path-norm, L1-norm and layer-wise constraints on the Lipschitz
constant (Parseval networks).

