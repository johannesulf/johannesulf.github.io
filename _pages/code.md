---
permalink: /code/
layout: single
author_profile: true
title: "Code"
toc: true
toc_label: Content
toc_sticky: true
header:
  overlay_image: /_images/code.jpg
  overlay_filter: 0.3
---

## Halotools

I am contributing to the halotools project, a python package for analyzing large-scale structure and empirical galaxy models using N-body simulations. For example, I implemented empirical CLF models and help develop the redshift-space clustering and galaxy-galaxy lensing routines. Halotools is an astropy affiliated package.

[<i class="fab fa-fw fa-github"></i> GitHub](https://github.com/astropy/halotools){: .btn .btn--primary } [<i class="fas fa-book"></i> Docs](https://halotools.readthedocs.io/en/latest/){: .btn .btn--primary }

## TabCorr

I implemented the handy tabulation method described in [Zheng & Guo et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.458.4015Z/abstract) into an easy-to-use python package that works well with halotools. I also generalize the method and enable fast computation of galaxy-galaxy lensing statistics and implementation of galaxy assembly bias models. This package is ideal for HOD fitting and I have used it in many publications.

[<i class="fab fa-fw fa-github"></i> GitHub](https://github.com/johannesulf/TabCorr){: .btn .btn--primary }

## Dsigma

Together with Song Huang, I have developed an easy-to-use galaxy-galaxy lensing pipeline. This pipeline has been built to be computationally efficient and also universally applicable. For example, it can be used with shape catalogs from SDSS, KiDS, HSC and CFHTLenS. The documentation includes many examples of how to use dsigma to obtain galaxy-galaxy lensing measurements from publicly available shape catalogs.

[<i class="fab fa-fw fa-github"></i> GitHub](https://github.com/johannesulf/dsigma){: .btn .btn--primary } [<i class="fas fa-book"></i> Docs](https://dsigma.readthedocs.io/en/latest/){: .btn .btn--primary }
