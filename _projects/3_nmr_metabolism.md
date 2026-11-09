---
layout: page
title: Bayesian modeling of C. difficile metabolism
description: Real-time NMR spectroscopy to metabolic flux, with uncertainty
img: assets/img/projects/nmr_fig.png # card thumbnail; replace the file or point this at a new image
github: https://github.com/jyuan1322/dynamic-flux-balance-analysis # adds a GitHub icon to the project card; keep in sync with the Code link below
importance: 3
category: microbiome
---

In the Gerber lab at Brigham and Women's Hospital / Harvard Medical School, I built preprocessing, calibration, and Bayesian (Stan) modeling pipelines that characterize the metabolic dynamics of _Clostridioides difficile_ from real-time NMR spectroscopy. Concentration trajectories for observed metabolites are modeled as a mixture of logistic functions, and confidence intervals on fluxes are passed as constraint bounds to dynamic flux balance analysis (dFBA, COBRApy) to infer a complete system of metabolic reactions over time. The pipeline cut analysis time from two weeks using conventional tools in TopSpin to six hours.

<!-- TODO: replace with a real figure. Put images in assets/img/projects/ and update `path` and `caption`. -->
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/nmr_fig.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Analysis pipeline includes processing of raw NMR signals into concentrations, including interactive tools for Lorentzian peak deconvolution and alignment across spectra. Concentration trajectories are modeled as posterior distributions on a mixture of logistic functions.</div>

In the same group, I built reproducible multi-omics pipelines in R and Python for microbiome cohorts (16S, shotgun metagenomics, NMR metabolomics, and proteomics), parallelized on a SLURM cluster. These frameworks allow for fast and professional analysis of new data sets including nested cross-validation and handling of clinical covariates across diverse study designs.

<i class="fa-brands fa-github"></i> **Code:** [GitHub](https://github.com/jyuan1322/dynamic-flux-balance-analysis) <!-- TODO: replace with this project's repository URL (also update `github:` at the top) -->
