---
title: "Codiscovering graphical structure and functional relationships within data: A Gaussian Process framework for connecting the dots"
collection: publications
permalink: /publication/CHD/
excerpt: 'This paper introduces Computational Hypergraph Discovery (CHD), a novel method for uncovering unknown functional relationships between variables within datasets, And represent them using a hypergraph.'
date: 2023-11-28
venue: 'PNAS'
paperurl: 'https://www.pnas.org/doi/10.1073/pnas.2403449121'
#citation: 'Bourdais, T., Batlle, P., Yang, X., Baptista, R., Rouquette, N., & Owhadi, H. (2024). Codiscovering graphical structure and functional relationships within data: A Gaussian Process framework for connecting the dots. Proceedings of the National Academy of Sciences, 121(32), e2403449121. https://doi.org/10.1073/pnas.2403449121'
---

## Context

This paper introduces Computational Hypergraph Discovery (CHD), a novel method for uncovering unknown functional relationships between variables within datasets, And represent them using a hypergraph. See the companion blog post [here](/posts/2023/11/CHD/).

[See the full article here](https://www.pnas.org/doi/10.1073/pnas.2403449121)

[Download preprint here](/files/2311.17007.pdf)

![Computational Hypergraph Discovery](/images/CHD/FPUT_subgraph.png)

## Abstract

Most problems within and beyond the scientific domain can be framed into one of the following three levels of complexity of function approximation. Type 1: Approximate an unknown function given input/output data. Type 2: Consider a collection of variables and functions, some of which are unknown, indexed by the nodes and hyperedges of a hypergraph (a generalized graph where edges can connect more than two vertices). Given partial observations of the variables of the hypergraph (satisfying the functional dependencies imposed by its structure), approximate all the unobserved variables and unknown functions. Type 3: Expanding on Type 2, if the hypergraph structure itself is unknown, use partial observations of the variables of the hypergraph to discover its structure and approximate its unknown functions. These hypergraphs offer a natural platform for organizing, communicating, and processing computational knowledge. While most scientific problems can be framed as the data-driven discovery of unknown functions in a computational hypergraph whose structure is known (Type 2), many require the data-driven discovery of the structure (connectivity) of the hypergraph itself (Type 3). We introduce an interpretable Gaussian Process (GP) framework for such (Type 3) problems that does not require randomization of the data, access to or control over its sampling, or sparsity of the unknown functions in a known or learned basis. Its polynomial complexity, which contrasts sharply with the super-exponential complexity of causal inference methods, is enabled by the nonlinear ANOVA capabilities of GPs used as a sensing mechanism.


