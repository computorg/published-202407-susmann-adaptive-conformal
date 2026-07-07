# AdaptiveConformal: An `R` Package for Adaptive Conformal Inference
Herbert Susmann, Antoine Chambaz, Julie Josse
2024-07-18

### Citation

Herbert Susmann, Antoine Chambaz and Julie Josse (July 2024). AdaptiveConformal: An R Package for Adaptive Conformal Inference. Computo.
<https://doi.org/10.57750/edan-5f53>

### Badges

[![build and
publish](https://github.com/computorg/published-202407-susmann-adaptive-conformal/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202407-susmann-adaptive-conformal/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202407-susmann-adaptive-conformal/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202407-susmann-adaptive-conformal)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202407-susmann-adaptive-conformal)
[![DOI:10.57750/edan-5f53](https://img.shields.io/badge/DOI-10.57750%2Fedan--5f53-034E79.svg)](https://doi.org/10.57750/edan-5f53)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- [Herbert Susmann](https://herbsusmann.com) (CEREMADE (UMR 7534), Université Paris-Dauphine PSL, Place du Maréchal de Lattre de Tassigny, Paris, 75016, France)
- [Antoine Chambaz](https://helios2.mi.parisdescartes.fr/~chambaz/) (Université Paris Cité, CNRS, MAP5, F-75006 Paris, France)
- [Julie Josse](http://juliejosse.com/) (Inria PreMeDICaL team, Idesp, Université de Montpellier)

### Abstract

Conformal Inference (CI) is a popular approach for generating finite
sample prediction intervals based on the output of any point prediction
method when data are exchangeable. Adaptive Conformal Inference (ACI)
algorithms extend CI to the case of sequentially observed data, such as
time series, and exhibit strong theoretical guarantees without having to
assume exchangeability of the observed data. The common thread that
unites algorithms in the ACI family is that they adaptively adjust the
width of the generated prediction intervals in response to the observed
data. We provide a detailed description of five ACI algorithms and their
theoretical guarantees, and test their performance in simulation
studies. We then present a case study of producing prediction intervals
for influenza incidence in the United States based on black-box point
forecasts. Implementations of all the algorithms are released as an
open-source `R` package, `AdaptiveConformal`, which also includes tools
for visualizing and summarizing conformal prediction intervals.
