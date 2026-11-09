---
layout: page
title: Spatial cell atlas of Parkinson's disease
description: Multi-omic spatial and temporal atlas of PD pathology
img: assets/img/projects/pd5d_overview.png # card thumbnail; replace the file or point this at a new image
github: https://github.com/jyuan1322/mtg-spatial-transcriptomics # adds a GitHub icon to the project card; keep in sync with the Code link below
importance: 1
category: omics
related_publications: false
---

I led computational development of a multi-omic spatial and temporal cell atlas of Parkinson's disease pathology, integrating spatial transcriptomics and single-cell data across disease stages. The atlas, a multi-faceted view of spatial and single-cell transcriptomes from 100 human brains, was presented as a platform talk at the American Society of Human Genetics meeting in 2023. The analyses covered annotation (clustering, batch correction, dimensionality reduction), differential expression, and single-cell/spatial deconvolution. The manuscript is in preparation.

<!-- TODO: replace with a real figure. Put images in assets/img/projects/ and update `path` and `caption`. -->
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/pd5d_overview.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">The Parkinson's cell atlas comprises multi-omic assay and clinical data for 100 subjects at varying stages of Parkinson's disease. Cross-assay integration to discover disease stage-specific pathology is of major interest.</div>

To build a joint model across heterogeneous omics data types, I implemented integration methods based on variational graph autoencoders and adapted them to the hexagonal spot layout of spatial assays.

As part of the AMP-PD consortium, I also ran a Gaussian process time-series analysis, in Stan, of bulk blood gene expression in about 600 Parkinson's patients across multiple clinical visits.

<i class="fa-brands fa-github"></i> **Code:** [GitHub](https://github.com/jyuan1322/mtg-spatial-transcriptomics) <!-- TODO: replace with this project's repository URL (also update `github:` at the top) -->
