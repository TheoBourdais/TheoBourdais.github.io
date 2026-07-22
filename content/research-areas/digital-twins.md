---
title: "Digital Twins"
date: 2025-01-01
draft: false
description: "Creating robust digital representations of physical systems."
tags: ["Digital Twins", "Model Aggregation", "Uncertainty Quantification", "Aerospace", "Machine Learning"]

# Research metadata
experience:
  - title: "Research Associate"
    organization: "NASA Jet Propulsion Laboratory (JPL)"
    date: "2024-2025"
    focus: "Digital twin methodologies for aerospace applications"

related_publications:
  - title: "Graphical conditional generative modeling for digital twin modeling"
    venue: "arXiv 2026"
    url: "/publications/graphical-conditional-generative-modeling-for-digital-twin-modeling/"
    github: "https://github.com/ZongrenZou/GraphicalConditionalGenerativeModeling"
    type: "core"
  - title: "ISOMORPH: A Supply Chain Digital Twin for Simulation, Dataset Generation, and Forecasting Benchmarks"
    venue: "arXiv 2026"
    url: "/publications/isomorph-a-supply-chain-digital-twin-for-simulation-dataset-generation-and-forecasting-benchmarks/"
    github: "https://github.com/tuhinsahai/ISOMORPH"
    type: "core"
  - title: "Model aggregation: minimizing empirical variance outperforms minimizing empirical error"
    venue: "ICLR 2025"
    url: "/publications/model-aggregation-minimizing-empirical-variance-outperforms-minimizing-empirical-error/"
    github: "https://github.com/TheoBourdais/ModelAggregation"
    type: "core"
  - title: "Codiscovering graphical structure and functional relationships within data"
    venue: "PNAS 2024"
    url: "/publications/codiscovering-graphical-structure-and-functional-relationships-within-data-a-gaussian-process-framework-for-connecting-the-dots/"
    github: "https://github.com/TheoBourdais/ComputationalHypergraphDiscovery"
    type: "supporting"

related_talks:
  model_aggregation:
    - name: "CIRM Digital Twins Workshop"
      date: "2025-08-11"
      location: "Marseille, France"
      subject: "Model Aggregation"
      talk_url: "/talks/model-aggregation/"
    - name: "UNCECOMP 2025"
      date: "2025-06-11"
      location: "Rhodes, Greece"
      subject: "Model Aggregation"
      talk_url: "/talks/model-aggregation/"
    - name: "ICLR 2025 (poster)"
      date: "2025-04-24"
      location: "Singapore"
      subject: "Model Aggregation"
      talk_url: "/talks/model-aggregation/"
    - name: "DTE AICOMAS"
      date: "2025-02-17"
      location: "Paris, France"
      subject: "Model Aggregation"
      talk_url: "/talks/model-aggregation/"
    - name: "JPL Research Seminar"
      date: "2025-01-17"
      location: "Pasadena, CA"
      subject: "Model Aggregation"
      talk_url: "/talks/model-aggregation/"
  structure_discovery:
    - name: "SIAM AN26"
      date: "2026-07-09"
      location: "AN26 / MS118"
      subject: "Non-linear Sensitivity Analysis"
      talk_url: "/talks/non-linear-sensitivity-analysis-for-interpretable-structure-discovery/"
  chd:
    - name: "DTE AICOMAS"
      date: "2025-02-18"
      location: "Paris, France"
      subject: "Computational Hypergraph Discovery"
      talk_url: "/talks/computational-hypergraph-discovery/"
    - name: "SIAM MDS"
      date: "2024-10-24"
      location: "Atlanta, GA"
      subject: "Computational Hypergraph Discovery"
      talk_url: "/talks/computational-hypergraph-discovery/"
    - name: "Digital Twins for Inverse Problems (CIRM)"
      date: "2024-07-23"
      location: "Marseille, France"
      subject: "Computational Hypergraph Discovery"
      talk_url: "/talks/computational-hypergraph-discovery/"
    - name: "SIAM UQ 2024"
      date: "2024-03-29"
      location: "Trieste, Italy"
      subject: "Computational Hypergraph Discovery"
      talk_url: "/talks/computational-hypergraph-discovery/"

---


**Digital twins** are real-time digital replicas of physical systems that enable simulation, monitoring, and optimization. Unlike traditional models, they are **dynamic** (continuously updated), **bi-directional** (inform physical systems), and **predictive** (enable forecasting).

![Digital Twins](/images/uav-elements.jpeg)

## Technical challenges

To create a true digital twin, we need to combine:
- **Accurate modeling**
- **Real-time data assimilation**
- **Control of the physical system using the digital twin**

Combining these three aspects for complex, large scale systems with potentially chaotic behavior is the core challenge of digital twin research. 

---

## My research in Digital Twins

I use modern machine learning techniques to create better models of physical systems. With Computational Hypergraph Discovery (CHD), we can sort through large datasets with many variables to discover the underlying functional relationships and graphical structure. This allows us to build more accurate and interpretable models of complex systems. With model aggregation, we can combine multiple models to get better predictions. When designing the research, I specifically focused on aggregating models for large scale physical systems, such as Earth's climate. 
