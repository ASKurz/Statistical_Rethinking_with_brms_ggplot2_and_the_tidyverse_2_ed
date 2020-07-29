--- 
title: "*Statistical rethinking* with brms, ggplot2, and the tidyverse: Second edition"
subtitle: "version 0.0.2"
author: ["A Solomon Kurz"]
date: "2020-06-30"
site: bookdown::bookdown_site
output: 
  bookdown::gitbook:
    split_bib: yes
documentclass: book
bibliography: bib.bib
biblio-style: apalike
csl: apa.csl
link-citations: yes
geometry:
  margin = 0.5in
urlcolor: blue
highlight: tango
header-includes:
  \usepackage{underscore}
  \usepackage[T1]{fontenc}
github-repo: ASKurz/Statistical_Rethinking_with_brms_ggplot2_and_the_tidyverse_2_ed
twitter-handle: SolomonKurz
description: "This book is an attempt to re-express the code in the second edition of McElreath's textbook, 'Statistical rethinking.' His models are re-fit in brms, plots are redone with ggplot2, and the general data wrangling code predominantly follows the tidyverse style."
---

# What and why {-}

This ebook is based on the second edition of [Richard McElreath](https://twitter.com/rlmcelreath)'s [-@mcelreathStatisticalRethinkingBayesian2020] text, [*Statistical rethinking: A Bayesian course with examples in R and Stan*](https://xcelab.net/rm/statistical-rethinking/). My contributions show how to fit the models he covered with [Paul Bürkner](https://twitter.com/paulbuerkner)'s [**brms** package](https://github.com/paul-buerkner/brms) [@R-brms; @burknerBrmsPackageBayesian2017; @burknerAdvancedBayesianMultilevel2018], which makes it easy to fit Bayesian regression models in **R** [@R-base] using Hamiltonian Monte Carlo. I also prefer plotting and data wrangling with the packages from the [**tidyverse**](http://style.tidyverse.org) [@R-tidyverse; @wickhamWelcomeTidyverse2019]. So we'll be using those methods, too.

## Caution: Work in progress {-}

The inaugural 0.0.1 release contained first drafts of Chapters 1 through 9. The 0.0.2 update adds drafts of Chapters 10 thorugh 12, which give a fine introduction to the generalized linear model.

There is no timetable for this project, but I'll update it periodically with new chapters and so on. To keep up with the latest changes, check in at the GitHub repository, [https://github.com/ASKurz/Statistical_Rethinking_with_brms_ggplot2_and_the_tidyverse_2_ed](https://github.com/ASKurz/Statistical_Rethinking_with_brms_ggplot2_and_the_tidyverse_2_ed), or follow my announcements on twitter at [https://twitter.com/SolomonKurz](https://twitter.com/SolomonKurz).

## Thank-you's are in order {-}

Before we move on, I'd like to thank the following for their helpful contributions:

* E. David Aja ([\@edavidaja](https://github.com/edavidaja)),
* Malcolm Barrett ([\@malcolmbarrett](https://github.com/malcolmbarrett)),
* Adam Bear ([\@adambear91](https://github.com/adambear91)),
* Paul-Christian Bürkner ([\@paul-buerkner](https://github.com/paul-buerkner)),
* Sebastian Lobentanzer ([\@slobentanzer](https://github.com/slobentanzer)), and
* Gavin Simpson ([\@gavinsimpson](https://github.com/gavinsimpson)).



