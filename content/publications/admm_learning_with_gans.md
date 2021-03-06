---
title: "Fast and Provable ADMM for learning with Generative Priors"
authors: "Fabian Latorre, Armin Eftekhari and Volkan Cevher"
venue: "NeurIPS 2019"
date: 2019-10-19
pdf: "https://papers.nips.cc/paper/9371-fast-and-provable-admm-for-learning-with-generative-priors"
draft: false
---
In this work, we propose a (linearized) Alternating Direction
Method-of-Multipliers (ADMM) algorithm for minimizing a convex function subject
to a nonconvex constraint. We focus on the special case where such constraint
arises from the specification that a variable should lie in the range of a
neural network. This is motivated by recent successful applications of
Generative Adversarial Networks (GANs) in tasks like compressive sensing,
denoising and robustness against adversarial examples. The derived rates for
our algorithm are characterized in terms of certain geometric properties of the
generator network, which we show hold for feedforward architectures, under mild
assumptions. Unlike gradient descent (GD), it can efficiently handle non-smooth
objectives as well as exploit efficient partial minimization procedures, thus
being faster in many practical scenarios.
