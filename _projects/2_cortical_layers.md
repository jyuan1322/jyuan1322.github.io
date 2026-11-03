---
layout: page
title: Cortical layer boundaries from spatial data
description: Inferring layer boundaries and cleaning artifacts in 10x Visium data
img: assets/img/projects/cortical_layers.png # card thumbnail; replace the file or point this at a new image
importance: 2
category: omics
---

Annotating cortical layers in 10x Visium brain sections has usually been done by hand, which is slow and error-prone, and the data are very noisy. I developed a machine learning tool that infers nonlinear boundaries between cortical layers directly from the spatial expression data.

<!-- TODO: replace with a real figure. Put images in assets/img/projects/ and update `path` and `caption`. -->
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/projects/cortical_layers.png" title="placeholder" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">TODO: figure caption.</div>

To speed up quality control, I also built a web application for selecting and filtering out spatial artifact spots interactively, replacing a slow manual step.

<!-- TODO: add a link to the code (e.g., a jyuan1322 GitHub repo). -->
