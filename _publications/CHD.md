---
title: "Computational Hypergraph Discovery, a Gaussian Process framework for connecting the dots"
collection: publications
permalink: /publication/CHD/
excerpt: 'This post introduces Computational Hypergraph Discovery (CHD), a novel method for uncovering unknown functional relationships between variables within datasets, And represent them using a hypergraph.'
date: 2023-11-28
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2311.17007'
#citation: 'Théo Bourdais, Pau Batlle, Xianjin Yang, Ricardo Baptista, Nicolas Rouquette, Houman Owhadi ; Computational Hypergraph Discovery, a Gaussian Process framework for connecting the dots. Arxiv 2023; https://arxiv.org/abs/2311.17007'
---

## Context

This post introduces Computational Hypergraph Discovery (CHD), a novel method for uncovering unknown functional relationships between variables within datasets, And represent them using a hypergraph. See the companion blog post [here](/posts/2023/11/CHD/).

[Download paper here](/files/2311.17007.pdf)


## Abstract

Most scientific challenges can be framed into one of the following three levels of complexity of function approximation. Type 1: Approximate an unknown function given input/output data. Type 2: Consider a collection of variables and functions, some of which are unknown, indexed by the nodes and hyperedges of a hypergraph (a generalized graph where edges can connect more than two vertices). Given partial observations of the variables of the hypergraph (satisfying the functional dependencies imposed by its structure), approximate all the unobserved variables and unknown functions. Type 3: Expanding on Type 2, if the hypergraph structure itself is unknown, use partial observations of the variables of the hypergraph to discover its structure and approximate its unknown functions. While most Computational Science and Engineering and Scientific Machine Learning challenges can be framed as Type 1 and Type 2 problems, many scientific problems can only be categorized as Type 3. Despite their prevalence, these Type 3 challenges have been largely overlooked due to their inherent complexity. Although Gaussian Process (GP) methods are sometimes perceived as well-founded but old technology limited to Type 1 curve fitting, their scope has recently been expanded to Type 2 problems. In this paper, we introduce an interpretable GP framework for Type 3 problems, targeting the data-driven discovery and completion of computational hypergraphs. Our approach is based on a kernel generalization of Row Echelon Form reduction from linear systems to nonlinear ones and variance-based analysis. Here, variables are linked via GPs and those contributing to the highest data variance unveil the hypergraph's structure. We illustrate the scope and efficiency of the proposed approach with applications to (algebraic) equation discovery, network discovery (gene pathways, chemical, and mechanical) and raw data analysis.


