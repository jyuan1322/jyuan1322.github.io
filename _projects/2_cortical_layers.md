---
layout: page
title: Cortical layer boundaries from spatial data
description: Inferring layer boundaries and cleaning artifacts in 10x Visium data
img: assets/img/projects/Layersmoother_overview.png # card thumbnail; replace the file or point this at a new image
github: https://github.com/jyuan1322 # TODO: replace with this project's repository URL; adds a GitHub icon to the project card
importance: 2
category: omics
---

Manual annotation of cortical layers in 10x Visium brain sections from H&E images is time consuming, requires sensitive tissue preparation and imaging,  and does not scale to hundreds of samples. I developed LayerSmoother, a machine learning tool that infers nonlinear boundaries between cortical layers directly from clustered spatial expression data. Manuscript is in preparation.

<!-- TODO: replace with a real figure. Put images in assets/img/projects/ and update `path` and `caption`. -->
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/Layersmoother_overview.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">LayerSmoother infers high-dimensional spatial tissue orientations to generate interpretable cortical layers from noisy, clustered spot transcriptomes.</div>

To improve quality control and reduce spurious clusters, I also built a web application for selecting and filtering out spatial artifact spots interactively, replacing a slow manual step. This typically happens when the edges of the tissue fold or roll when mounting on the slide.

<i class="fa-brands fa-github"></i> **Code:** [GitHub](https://github.com/jyuan1322) <!-- TODO: replace with this project's repository URL (also update `github:` at the top) -->
