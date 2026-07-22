---
title: "ISOMORPH: A Supply Chain Digital Twin for Simulation, Dataset Generation, and Forecasting Benchmarks"
date: 2026-05-12
publishDate: 2026-05-12
type: "publications"
short_text: "A public multi-echelon logistics digital twin for simulation, dataset generation, and forecasting benchmarks, with interpretable controls and verification tools."
authors: ["Zhizhen Zhang", "Hyemin Gu", "Benjamin J. Zhang", "Daniel Elenius", "Michael Tyrrell", "Theo J. Bourdais", "Houman Owhadi", "Markos A. Katsoulakis", "Tuhin Sahai"]
publication_types: ["3"]
image: "/images/isomorph.gif"
abstract: "Open time-series forecasting (TSF) benchmarks cover retail, energy, weather, and traffic, but supply-chain logistics remains underserved. We introduce ISOMORPH, the first public digital twin of a multi-echelon logistics network with interpretable, user-configurable parameters and modular topology, demand, and control rules. The simulator advances a directed routing graph in discrete time: demand is served from inventory or recorded as backlog and triggers replenishment throughout the network. The state tracks inventory, outstanding orders, in-transit shipments, and a smoothed demand estimate, yielding Markovian dynamics on a tractable state space. The released data reproduces the bullwhip effect at empirically consistent magnitudes, while three conservation laws provide verification tools for simulator extensions."
featured: true
publication: "arXiv preprint"
publication_short: "arXiv"
url_pdf: "https://arxiv.org/abs/2605.12768"
url_github: "https://github.com/tuhinsahai/ISOMORPH"
links:
- name: "Paper"
  url: "https://arxiv.org/abs/2605.12768"
- name: "Code"
  url: "https://github.com/tuhinsahai/ISOMORPH"
- name: "Demo"
  url: "https://huggingface.co/spaces/HyeminGu/ISOMORPH-demo"
tags: ["Digital Twins", "Supply Chain", "Simulation", "Forecasting"]
---

## Context

ISOMORPH provides an open, configurable supply-chain digital twin for simulation, dataset release, and forecasting benchmarks in multi-echelon logistics.

## Abstract

Open time-series forecasting (TSF) benchmarks cover retail, energy, weather, and traffic, but supply-chain logistics remains underserved. We introduce ISOMORPH, the first public digital twin of a multi-echelon logistics network with interpretable, user-configurable parameters and modular topology, demand, and control rules. The simulator advances a directed routing graph in discrete time: demand is served from inventory or recorded as backlog and triggers replenishment throughout the network. The state tracks inventory, outstanding orders, in-transit shipments, and a smoothed demand estimate, yielding Markovian dynamics on a tractable state space. The released data reproduces the bullwhip effect at empirically consistent magnitudes, while three conservation laws provide verification tools for simulator extensions.
