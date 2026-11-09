---
layout: page
title: Statistical genomics
description: Polygenic risk heterogeneity and eQTL discovery (PhD, Columbia)
img: assets/img/projects/clip_heterogeneity_thumb.png # card thumbnail; replace the file or point this at a new image
github: https://github.com/jyuan1322/CLiP # adds a GitHub icon to the project card; keep in sync with the Code link below
importance: 4
category: genomics
related_publications: true
---

My PhD research at Columbia, advised by Itsik Pe’er and Yaniv Erlich, developed statistical methods for detecting and characterizing latent heterogeneity in polygenic risk scores, and for improving eQTL discovery by combining gene expression and GWAS data.

<!-- TODO: replace with a real figure. Put images in assets/img/projects/ and update `path` and `caption`. -->
<div class="row justify-content-sm-center">
  <div class="mt-3 mt-md-0" style="width: 100%; max-width: 500px; margin: 0 auto;"> <!-- max-width sets the figure size -->
    {% include figure.liquid loading="eager" path="assets/img/projects/clip_heterogeneity.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">Among cases for polygenic traits, correlations are expected between risk alleles. In aggregate, these can be leveraged to identify hidden heterogeneity in the form of distinct sub-traits.</div>

- **Heterogeneity in GWAS cohorts.** I showed how correlations between variants in polygenic risk scores can reveal hidden heterogeneity among cases in genome-wide association cohorts, and applied the method to schizophrenia data with the Psychiatric Genomics Consortium. I presented this work as a platform talk at ASHG 2019. {% cite yuan2020leveraging %}
- **Reverse TWAS.** Reversing the direction of transcriptome-wide association studies improves the discovery of expression quantitative trait loci. {% cite yuan2020reversing %}
- **Contrastive tensor decomposition.** In my PhD thesis, I adapted contrastive spectral methods for mixture models ([Zou et al., NIPS 2013](https://www.cs.columbia.edu/~djhsu/papers/contrast-nips.pdf)) into a contrastive tensor decomposition that characterizes subtype-specific SNP effects in polygenic risk scores, independently of confounding heterogeneity such as ancestry. {% cite yuan2021thesis %}

<i class="fa-brands fa-github"></i> **Code:** [GitHub](https://github.com/jyuan1322/CLiP) <!-- TODO: replace with this project's repository URL (also update `github:` at the top) -->
