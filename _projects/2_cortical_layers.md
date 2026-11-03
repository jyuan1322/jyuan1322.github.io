---
layout: page
title: Cortical layer boundaries from spatial data
description: Inferring layer boundaries and cleaning artifacts in 10x Visium data
img: # TODO: optional thumbnail
importance: 2
category: omics
---

Annotating cortical layers in 10x Visium brain sections has usually been done by hand, which is slow and error-prone, and the data are very noisy. I developed a machine learning tool that infers nonlinear boundaries between cortical layers directly from the spatial expression data.

To speed up quality control, I also built a web application for selecting and filtering out spatial artifact spots interactively, replacing a slow manual step.

<!-- TODO: add a link to the code (e.g., a jyuan1322 GitHub repo) and an example figure. -->
