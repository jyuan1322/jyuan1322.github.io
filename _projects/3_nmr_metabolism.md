---
layout: page
title: Bayesian modeling of C. difficile metabolism
description: Real-time NMR spectroscopy to metabolic flux, with uncertainty
img: assets/img/projects/nmr_metabolism.png # card thumbnail; replace the file or point this at a new image
importance: 3
category: microbiome
---

At Brigham and Women's Hospital / Harvard Medical School, I built preprocessing, calibration, and Bayesian (Stan) modeling pipelines that characterize the metabolic dynamics of _Clostridioides difficile_ from real-time NMR spectroscopy. The model estimates are connected to dynamic flux balance analysis (dFBA, COBRApy), and their uncertainty carries through into the flux estimates. The pipeline cut analysis time from two weeks to six hours.

<!-- TODO: replace with a real figure. Put images in assets/img/projects/ and update `path` and `caption`. -->
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/nmr_metabolism.png" title="placeholder" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">TODO: figure caption.</div>

In the same group, I built reproducible multi-omics pipelines for microbiome cohorts (16S, shotgun metagenomics, NMR metabolomics, and proteomics), parallelized on a SLURM cluster. Alongside them I wrote a Python ML framework that shares modeling code across assays and handles clinical covariates flexibly.
