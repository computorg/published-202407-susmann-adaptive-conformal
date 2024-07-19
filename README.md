# AdaptiveConformal: An `R` Package for Adaptive Conformal Inference

[![build and publish](https://github.com/computorg/template-computo-R/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/template-computo-R/actions/workflows/build.yml)

Authors: 

- [Herbert Susmann](https://herbsusmann.com) - [CEREMADE (UMR 7534), Université Paris-Dauphine PSL, Place du Maréchal de Lattre de Tassigny, Paris, 75016, France](https://www.ceremade.dauphine.fr/)
- [Antoine Chambaz](https://helios2.mi.parisdescartes.fr/~chambaz/) - [Université Paris Cité, CNRS, MAP5, F-75006 Paris, France](https://map5.mi.parisdescartes.fr/)
- [Julie Josse](http://juliejosse.com/) - [Inria PreMeDICaL team, Idesp, Université de Montpellier](https://team.inria.fr/premedical/)

Conformal Inference (CI) is a popular approach for generating finite sample prediction intervals based on the output of any point prediction method when data are exchangeable. Adaptive Conformal Inference (ACI) algorithms extend CI to the case of sequentially observed data, such as time series, and exhibit strong theoretical guarantees without having to assume exchangeability of the observed data. The common thread that unites algorithms in the ACI family is that they adaptively adjust the width of the generated prediction intervals in response to the observed data. We provide a detailed description of five ACI algorithms and their theoretical guarantees, and test their performance in simulation studies. We then present a case study of producing prediction intervals for influenza incidence in the United States based on black-box point forecasts. Implementations of all the algorithms are released as an open-source `R` package, `AdaptiveConformal`, which also includes tools for visualizing and summarizing conformal prediction intervals.

[![](https://img.shields.io/github/last-commit/computorg/published-202407-susmann-adaptive-conformal.svg)](https://github.com/computorg/published-202407-susmann-adaptive-conformal/commits/main)
[![DOI:xxx/xxx-xxx](https://img.shields.io/badge/DOI-10.57750/edan--5f53-034E79.svg)](https://doi.org/10.57750/edan-5f53)
[![HTML](https://img.shields.io/badge/article-HTML-034E79)](https://computo.sfds.asso.fr/published-202407-susmann-adaptive-conformal/)
[![PDF](https://img.shields.io/badge/article-PDF-034E79)](https://computo.sfds.asso.fr/published-202407-susmann-adaptive-conformal/published-202407-susmann-adaptive-conformal.pdf)
[![reviews](https://img.shields.io/badge/review-report%201-blue)](https://github.com/computorg/published-202407-susmann-adaptive-conformal/issues/2)
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

## Build instructions

The main paper can be found in [published-202407-susmann-adaptive-conformal](http://computo.sfds.asso.fr/published-202407-susmann-adaptive-conformal/). Several helper functions, such as functions that execute the simulation studies, are defined in [helpers.R](https://github.com/computorg/published-202407-susmann-adaptive-conformal/blob/main/helpers.R).