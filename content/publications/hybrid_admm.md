---
title: "A Plug-and-Play Deep Image Prior"
authors: "Zhaodong Sun, Fabian Latorre, Thomas Sanchez and Volkan Cevher"
venue: "ICASSP 2021"
date: 2021-05-31
pdf: "https://ieeexplore.ieee.org/abstract/document/9414879"
draft: false
---
Deep image priors (DIP) offer a novel approach for the regularization that
leverages the inductive bias of a deep convolutional architecture in inverse
problems. However, the quality of DIP approaches often degrades when the number
of iterations exceeds a certain threshold due to overfitting. To mitigate this
effect, this work incorporates a plug-and-play prior scheme which can
accommodate additional regularization steps within a DIP framework. Our
modification is achieved using an augmented Lagrangian formulation of the
problem, and is solved using an Alternating Direction Method of Multipliers
(ADMM) variant, which can capture existing DIP approaches as a special case. We
show experimentally that our ADMM-based DIP pairing outperforms competitive
baselines in PSNR while exhibiting less overfitting.

