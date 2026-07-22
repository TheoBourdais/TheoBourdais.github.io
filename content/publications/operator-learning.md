---
title: "Operator Learning at Machine Precision"
date: 2025-11-25
publishDate: 2025-11-25
type: "publications"
short_text: "CHONKNORIS achieves machine-precision operator learning by regressing Cholesky factors of Newton–Kantorovich updates rather than the solution operator itself."
authors: ["Aras Bacho", "Aleksei G. Sorokin", "Xianjin Yang", "Theo Bourdais", "Edoardo Calvello", "Matthieu Darcy", "Alexander Hsu", "Bamdad Hosseini", "Houman Owhadi"]
publication_types: ["3"]
image: "/images/operator.png"
abstract: "Neural operator learning methods have garnered significant attention in scientific computing for their ability to approximate infinite-dimensional operators. However, increasing their complexity often fails to substantially improve their accuracy, leaving them on par with much simpler approaches such as kernel methods and more traditional reduced-order models. In this article, we set out to address this shortcoming and introduce CHONKNORIS (Cholesky Newton–Kantorovich Neural Operator Residual Iterative System), an operator learning paradigm that can achieve machine precision. CHONKNORIS draws on numerical analysis: many nonlinear forward and inverse PDE problems are solvable by Newton-type methods. Rather than regressing the solution operator itself, our method regresses the Cholesky factors of the elliptic operator associated with Tikhonov-regularized Newton–Kantorovich updates."
featured: true
publication: "arXiv preprint"
publication_short: "arXiv"
url_pdf: "https://arxiv.org/abs/2511.19980"
url_github: "https://github.com/ArasBacho/CHONKNORIS"
links:
- name: "Paper"
  url: "https://arxiv.org/abs/2511.19980"
- name: "Code"
  url: "https://github.com/ArasBacho/CHONKNORIS"
tags: ["Operator Learning", "Scientific Computing", "Neural Operators", "Machine Learning"]
---

## Context

We introduce CHONKNORIS, an operator learning framework that can reach machine precision by learning Newton–Kantorovich update structure rather than regressing the solution operator directly.

## Abstract

Neural operator learning methods have garnered significant attention in scientific computing for their ability to approximate infinite-dimensional operators. However, increasing their complexity often fails to substantially improve their accuracy, leaving them on par with much simpler approaches such as kernel methods and more traditional reduced-order models. In this article, we set out to address this shortcoming and introduce CHONKNORIS (Cholesky Newton–Kantorovich Neural Operator Residual Iterative System), an operator learning paradigm that can achieve machine precision. CHONKNORIS draws on numerical analysis: many nonlinear forward and inverse PDE problems are solvable by Newton-type methods. Rather than regressing the solution operator itself, our method regresses the Cholesky factors of the elliptic operator associated with Tikhonov-regularized Newton–Kantorovich updates.
