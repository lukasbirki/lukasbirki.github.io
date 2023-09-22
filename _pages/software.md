---
layout: archive
title: "Software"
gallery:
  - url: software/interface.png
    image_path: software/interface.png
    alt: "interface"
    title: "Landing Page"
  - url: software/interface2.png
    image_path: software/interface2.png
    alt: "checklist"
    title: "checklist"
  - url: software/use_cases.png
    image_path: software/use_cases.png
    alt: "Use Cases"
    title: "Use Cases"
header:
  og_image: "software/spatial_weighting.png"
permalink: /software/
author_profile: true
redirect_from:
  - /resume
---

As a computational social scientist, developing tools and software is part of my daily work. Below, you will find some of my most recent project. 
# ValiTex

[![Project Status: Active -- The project has reached a stable, usable
state and is being actively
developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![DOI](https://zenodo.org/badge/634831162.svg)](https://zenodo.org/badge/latestdoi/634831162)
[![Lifecycle: stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://www.tidyverse.org/lifecycle/#stable)
[![R-CMD-check](https://github.com/lukasbirki/ValiTex/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/lukasbirki/ValiTex/actions/workflows/R-CMD-check.yaml)

One of my recent projects is the development of the [ValiTex](https://lukasbirki.shinyapps.io/ValiTex/) framework for validating text-based measures of social science constructs (for the working paper, see [Birkenmaier et al. (2023)](https://arxiv.org/abs/2307.02863)). The frameworks comes with a shiny app, which is also implemented in an R-Package.

{% include gallery %}



The latest [development version](https://github.com/lukasbirki/ValiTex) on GitHub can be installed with:

```r
install.packages("devtools")
devtools::install_github("lukasbirki/ValiTex")
```

You can then run the app locally by running `ValiTex::run_app()`

# CitiesRopen

[![Project Status: Active – The project has reached a stable, usable
state and is being actively
developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

This Rpackages allows you to directly inspect and download data from the Open Data Portal of Constance. It can be easily used by practioniers, members of the civil society and academics and expects users to have only a basic understanding of R. Technically, the package relies on the DKAN API.

``` r
install.packages("devtools")
devtools::install_github("CorrelAid/CitiesRopen")
```