---
title: "Computational Hypergraph Discovery"
summary: "Talk on Computational Hypergraph Discovery framework for discovering unknown functional relationships in data"
abstract: "Most scientific challenges can be framed into one of the following three levels of complexity of function approximation. Type 1: Approximate an unknown function given input/output data. Type 2: Consider a collection of variables and functions, some of which are unknown, indexed by the nodes and hyperedges of a hypergraph (a generalized graph where edges can connect more than two vertices). Given partial observations of the variables of the hypergraph (satisfying the functional dependencies imposed by its structure), approximate all the unobserved variables and unknown functions. Type 3: Expanding on Type 2, if the hypergraph structure itself is unknown, use partial observations of the variables of the hypergraph to discover its structure and approximate its unknown functions. While most Computational Science and Engineering and Scientific Machine Learning challenges can be framed as Type 1 and Type 2 problems, many scientific problems can only be categorized as Type 3. Despite their prevalence, these Type 3 challenges have been largely overlooked due to their inherent complexity. Although Gaussian Process (GP) methods are sometimes perceived as well-founded but old technology limited to Type 1 curve fitting, their scope has recently been expanded to Type 2 problems. We introduce an interpretable GP framework for Type 3 problems, targeting the data-driven discovery and completion of computational hypergraphs. Our approach is based on a kernel generalization of (1) Row Echelon Form reduction from linear systems to nonlinear ones and (2) variance-based analysis. Here, variables are linked via GPs, and those contributing to the highest data variance unveil the hypergraph's structure. We illustrate the scope and efficiency of the proposed approach with applications to network discovery (gene pathways, chemical, and mechanical), and raw data analysis."
tags: ["Gaussian Processes", "Hypergraphs", "Machine Learning", "Computational Science"]
featured: true

authors: ["Theo Bourdais"]

# Links
url_slides: "/files/CHD_one_world_seminar.pdf"
url_video: "https://youtu.be/XIz2Va_wXrc"
url_paper: "/publications/codiscovering-graphical-structure-and-functional-relationships-within-data-a-gaussian-process-framework-for-connecting-the-dots/"

# Presentation venues (sorted by most recent first)
venues:
  - name: "DTE AICOMAS"
    date: "2025-02-18"
    location: "Paris, France"
    url: "https://dte_aicomas_2025.iacm.info/"
  - name: "SIAM Mathematics of Data Science (SIAM MDS)"
    date: "2024-10-24"
    location: "Atlanta, Georgia, USA"
    url: "https://www.siam.org/conferences/cm/conference/mds24"
  - name: "Digital twins for inverse problems in Earth science"
    date: "2024-07-23"
    location: "Marseille, France"
    url: "https://dt4ip.sciencesconf.org/"
  - name: "SIAM UQ 2024"
    date: "2024-03-29"
    location: "Trieste, Italy"
    url: "https://www.siam.org/conferences/cm/conference/uq24"
  - name: "Differential Equations for Data Science 2024 (DEDS2024)"
    date: "2024-02-19"
    location: "Online"
    url: "https://scheme.hn/deds2024/"
    video: "https://scheme.hn/deds2024/videos/bourdais.mp4"
  - name: "One World Seminar Series on the Mathematics of Machine Learning"
    date: "2024-01-17"
    location: "Online"
    url: "https://www.oneworldml.org/home"
    slides: "/files/CHD_one_world_seminar.pdf"
    video: "https://youtu.be/XIz2Va_wXrc"
---

My talk on Computational Hypergraph Discovery! This framework addresses the challenge of discovering unknown functional relationships and hypergraph structures from partial observations using Gaussian Processes.

The approach introduces a kernel generalization of Row Echelon Form reduction and variance-based analysis to unveil hypergraph structures, with applications to network discovery in gene pathways, chemical systems, and mechanical systems.