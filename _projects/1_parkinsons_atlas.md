---
layout: page
title: Spatial cell atlas of Parkinson's disease
description: Multi-omic spatial and temporal atlas of PD pathology
img: # TODO: optional thumbnail, e.g. assets/img/projects/pd_atlas.png
importance: 1
category: omics
related_publications: true
---

I led computational development of a multi-omic spatial and temporal cell atlas of Parkinson's disease pathology, integrating spatial transcriptomics and single-cell data across disease stages. The atlas, a multi-faceted view of spatial and single-cell transcriptomes from 100 human brains, was presented as a platform talk at the American Society of Human Genetics meeting in 2023. The analyses covered annotation (clustering, batch correction, dimensionality reduction), differential expression, and single-cell/spatial deconvolution. The manuscript is in preparation.

To build a joint model across heterogeneous omics data types, I implemented integration methods based on variational graph autoencoders and adapted them to the hexagonal spot layout of spatial assays.

As part of the AMP-PD consortium, I also ran a Gaussian process time-series analysis, in Stan, of bulk blood gene expression in about 600 Parkinson's patients across multiple clinical visits.

{% cite hu2024parkinsons %}
