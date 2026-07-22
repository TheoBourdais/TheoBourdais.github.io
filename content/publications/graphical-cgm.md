---
title: "Graphical conditional generative modeling for digital twin modeling"
date: 2026-06-15
publishDate: 2026-06-15
type: "publications"
short_text: "A framework for discovering which inputs shape the full conditional law of a target—beyond the conditional mean—for parsimonious digital-twin surrogates."
authors: ["Zongren Zou", "Theo Bourdais", "Ricardo Baptista", "Houman Owhadi"]
publication_types: ["3"]
image: "/images/gcgm.jpg"
abstract: "Digital twin modeling, including control and data assimilation under model uncertainty, often faces an open-ended fidelity problem: adding variables, data streams, and time scales can indefinitely increase model complexity, ultimately producing systems that are difficult to maintain, validate, interpret, and use for stress or safety testing. As an alternative, one can seek parsimonious stochastic surrogate models built only on the variables needed to describe the relevant quantities of interest. We introduce a framework for discovering such variables from observational data by identifying which candidate inputs influence the full conditional law of a target quantity, rather than only its conditional mean. This distinction is essential in stochastic, coarse-grained, or partially observed systems, where dependencies may appear through changes in variability, tail behavior, multimodality, or uncertainty rather than through deterministic functional relationships."
featured: true
publication: "arXiv preprint"
publication_short: "arXiv"
url_pdf: "https://arxiv.org/abs/2606.16219"
url_github: "https://github.com/ZongrenZou/GraphicalConditionalGenerativeModeling"
links:
- name: "Paper"
  url: "https://arxiv.org/abs/2606.16219"
- name: "Code"
  url: "https://github.com/ZongrenZou/GraphicalConditionalGenerativeModeling"
tags: ["Digital Twins", "Generative Models", "Sensitivity Analysis", "Machine Learning"]
---

## Context

We develop graphical conditional generative modeling to identify variables that affect the full conditional distribution of quantities of interest—supporting reduced, interpretable digital-twin surrogates.

## Abstract

Digital twin modeling, including control and data assimilation under model uncertainty, often faces an open-ended fidelity problem: adding variables, data streams, and time scales can indefinitely increase model complexity, ultimately producing systems that are difficult to maintain, validate, interpret, and use for stress or safety testing. As an alternative, one can seek parsimonious stochastic surrogate models built only on the variables needed to describe the relevant quantities of interest. We introduce a framework for discovering such variables from observational data by identifying which candidate inputs influence the full conditional law of a target quantity, rather than only its conditional mean. This distinction is essential in stochastic, coarse-grained, or partially observed systems, where dependencies may appear through changes in variability, tail behavior, multimodality, or uncertainty rather than through deterministic functional relationships.
