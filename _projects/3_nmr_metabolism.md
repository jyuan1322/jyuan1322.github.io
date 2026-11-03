---
layout: page
title: Bayesian modeling of C. difficile metabolism
description: Real-time NMR spectroscopy to metabolic flux, with uncertainty
img: # TODO: optional thumbnail
importance: 3
category: microbiome
---

At Brigham and Women's Hospital / Harvard Medical School, I built preprocessing, calibration, and Bayesian (Stan) modeling pipelines that characterize the metabolic dynamics of _Clostridioides difficile_ from real-time NMR spectroscopy. The model estimates are connected to dynamic flux balance analysis (dFBA, COBRApy), and their uncertainty carries through into the flux estimates. The pipeline cut analysis time from two weeks to six hours.

In the same group, I built reproducible multi-omics pipelines for microbiome cohorts (16S, shotgun metagenomics, NMR metabolomics, and proteomics), parallelized on a SLURM cluster. Alongside them I wrote a Python ML framework that shares modeling code across assays and handles clinical covariates flexibly.
