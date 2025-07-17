---
title: "Model Aggregation"
summary: "Talk on Model Aggregation framework for combining predictions from diverse models"
abstract: "Whether deterministic or stochastic, models can be viewed as functions designed to approximate a specific quantity of interest. We introduce Minimal Empirical Variance Aggregation (MEVA), a data-driven framework that integrates predictions from various models, enhancing overall accuracy by leveraging the individual strengths of each. This non-intrusive, model-agnostic approach treats the contributing models as black boxes and accommodates outputs from diverse methodologies, including machine learning algorithms and traditional numerical solvers. We advocate for a point-wise linear aggregation process and consider two methods for optimizing this aggregate: Minimal Error Aggregation (MEA), which minimizes the prediction error, and Minimal Variance Aggregation (MVA), which focuses on reducing variance. We prove a theorem showing that MVA can be more robustly estimated from data than MEA, making MEVA superior to Minimal Empirical Error Aggregation (MEEA). Unlike MEEA, which interpolates target values directly, MEVA formulates aggregation as an error estimation problem, which can be performed using any backbone learning paradigm. We demonstrate the versatility and effectiveness of our framework across various applications, including data science and partial differential equations, illustrating its ability to significantly enhance both robustness and accuracy."
tags: ["Model Aggregation", "Machine Learning", "Ensemble Methods", "Variance Minimization"]
featured: true

authors: ["Theo Bourdais"]

# Links
url_paper: "/publications/model-aggregation-minimizing-empirical-variance-outperforms-minimizing-empirical-error/"
url_slides: "/files/presentation_model_aggregation.pdf"

# Presentation venues (sorted by most recent first)
venues:
  - name: "UNCECOMP 2025"
    date: "2025-06-11"
    location: "Rhodes, Greece"
    url: "https://2025.uncecomp.org/"
  - name: "DTE AICOMAS"
    date: "2025-02-17"
    location: "Paris, France"
    url: "https://dte_aicomas_2025.iacm.info/"
  - name: "JPL"
    date: "2025-01-17"
    location: "Pasadena, California, USA"
    url: "https://www.jpl.nasa.gov/"
---

My talk on Model Aggregation! This framework introduces Minimal Empirical Variance Aggregation (MEVA), a data-driven approach that integrates predictions from various models to enhance overall accuracy.

The method treats contributing models as black boxes and accommodates outputs from diverse methodologies, focusing on variance minimization for more robust estimation compared to traditional error minimization approaches.