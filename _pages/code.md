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

## halotools

I am contributing to the halotools project, a python package for analyzing large-scale structure and empirical galaxy models using N-body simulations. For example, I implemented empirical CLF models and help develop the redshift-space clustering and galaxy-galaxy lensing routines. Halotools is an astropy affiliated package.

[<i class="fab fa-fw fa-python"></i> PyPI](https://pypi.org/project/halotools/){: .btn .btn--primary } [<i class="fab fa-fw fa-github"></i> GitHub](https://github.com/astropy/halotools){: .btn .btn--primary } [<i class="fas fa-book"></i> Docs](https://halotools.readthedocs.io/en/latest/){: .btn .btn--primary }

## TabCorr

I implemented the handy tabulation method described in [Zheng & Guo et al. (2016)](https://ui.adsabs.harvard.edu/abs/2016MNRAS.458.4015Z/abstract) into an easy-to-use python package that works well with halotools. I also generalize the method and enable fast computation of galaxy-galaxy lensing statistics and implementation of galaxy assembly bias models. This package is ideal for HOD fitting and I have used it in many publications.

[<i class="fab fa-fw fa-python"></i> PyPI](https://pypi.org/project/tabcorr/){: .btn .btn--primary } [<i class="fab fa-fw fa-github"></i> GitHub](https://github.com/johannesulf/TabCorr){: .btn .btn--primary } [<i class="fas fa-book"></i> Docs](https://github.com/johannesulf/TabCorr){: .btn .btn--primary }

## dsigma

Together with Song Huang, I have developed an easy-to-use galaxy-galaxy lensing pipeline. This pipeline has been built to be computationally efficient and also universally applicable. For example, it can be used with shape catalogs from SDSS, KiDS, HSC and CFHTLenS. The documentation includes many examples of how to use dsigma to obtain galaxy-galaxy lensing measurements from publicly available shape catalogs.

[<i class="fab fa-fw fa-python"></i> PyPI](https://pypi.org/project/dsigma/){: .btn .btn--primary } [<i class="fab fa-fw fa-github"></i> GitHub](https://github.com/johannesulf/dsigma){: .btn .btn--primary } [<i class="fas fa-book"></i> Docs](https://dsigma.readthedocs.io/en/latest/){: .btn .btn--primary }

## Nautilus

I'm developing a new Bayesian analysis tool called Nautilus. It allows the user to estimate Bayesian posteriors and evidences, similar to existing MCMC and nested sampling codes such as emcee and dynesty. This new code is designed to be substantially more efficient than existing algorithms by utilizing neural network emulators to make efficient proposals. A publication describing the underlying algorithm and demonstrating its efficiency is in preparation.

[<i class="fab fa-fw fa-python"></i> PyPI](https://pypi.org/project/nautilus-sampler/){: .btn .btn--primary } [<i class="fab fa-fw fa-github"></i> GitHub](https://github.com/johannesulf/nautilus){: .btn .btn--primary } [<i class="fas fa-book"></i> Docs](https://nautilus-sampler.readthedocs.io/en/latest/){: .btn .btn--primary }
