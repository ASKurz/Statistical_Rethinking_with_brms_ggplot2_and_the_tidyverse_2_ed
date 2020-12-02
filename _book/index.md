--- 
title: "*Statistical rethinking* with brms, ggplot2, and the tidyverse: Second edition"
subtitle: "version 0.1.1"
author: ["A Solomon Kurz"]
date: "2020-12-02"
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

## We have updates {-}

For a brief rundown of the version history, we have:

### Version 0.1.0. {-}

I released the 0.1.0 version of this project in November 24, 2020. It was the first full-length and nearly complete draft including material from all the 17 chapters in McElreath's source material. All **brms** models were fit with version 2.14.0+. 

### Version 0.1.1. {-}

Welcome to version 0.1.1! This is a mini update designed to 

* fix code breaks resulting from updates to the [**broom** package](https://CRAN.R-project.org/package=broom) [@R-broom], caught by [Jenny Bigman](https://twitter.com/jennybigman);
* replace the soon-to-be retired `sample_n()` code with `slice_sample()`, caught by [Randall Pruim](https://github.com/rpruim);
* and correct a few typos along the way.

### We're not done yet and I could use your help. {-}

Some areas of the book could use some fleshing out. The sections I'm particularly anxious to improve are

* [4.6][~~Summary~~ B-splines with **brms**], which introduces the **brms** approach to b-splines;
* [15.3][Categorical errors and discrete absences], which may someday include a **brms** workflow for categorical missing data;
* [16.2.3][Coding the statistical model.], which contains a mixture model that McElreath fit directly in Stan and I suspect may be possible in **brms** with a custom likelihood; and
* [16.4.2][The statistical model.], which contains an ordinary differential equation model that McElreath fit directly in Stan and I suspect may be possible in **brms**, but is beyond my current skill set.

If you have insights on how to improve any of these sections, please share your thoughts on GitHub at [https://github.com/ASKurz/Statistical_Rethinking_with_brms_ggplot2_and_the_tidyverse_2_ed/issues](https://github.com/ASKurz/Statistical_Rethinking_with_brms_ggplot2_and_the_tidyverse_2_ed/issues). The contribution guidelines for this book are listed at [https://github.com/ASKurz/Statistical_Rethinking_with_brms_ggplot2_and_the_tidyverse_2_ed/blob/master/CONTRIBUTING.md](https://github.com/ASKurz/Statistical_Rethinking_with_brms_ggplot2_and_the_tidyverse_2_ed/blob/master/CONTRIBUTING.md).

## Thank-you's are in order {-}

I'd like to thank the following for their helpful contributions:

* E. David Aja ([\@edavidaja](https://github.com/edavidaja)),
* Monica Alexander ([\@MJAlexander](https://github.com/MJAlexander)),
* Shaan Amin ([\@Shaan-Amin](https://github.com/Shaan-Amin)),
* Malcolm Barrett ([\@malcolmbarrett](https://github.com/malcolmbarrett)),
* Adam Bear ([\@adambear91](https://github.com/adambear91)),
* Jenny Bigman ([\@jennybigman](https://github.com/jennybigman)),
* Louis Bliard ([\@lbiard](https://github.com/lbiard)),
* Paul-Christian Bürkner ([\@paul-buerkner](https://github.com/paul-buerkner)),
* Sebastian Lobentanzer ([\@slobentanzer](https://github.com/slobentanzer)),
* Ed Merkle ([\@ecmerkle](https://github.com/ecmerkle)),
* Randall Pruim ([\@rpruim](https://github.com/rpruim)),
* Gavin Simpson ([\@gavinsimpson](https://github.com/gavinsimpson)),
* Richard Torkar ([\@torkar](https://github.com/torkar)), and
* Donald R. Williams ([\@donaldRwilliams](https://github.com/donaldRwilliams)). 

Science is better when we work together.

## License and citation {-}

This book is licensed under the Creative Commons Zero v1.0 Universal license. You can learn the details, [here](https://github.com/ASKurz/Statistical_Rethinking_with_brms_ggplot2_and_the_tidyverse_2_ed/blob/master/LICENSE). In short, you can use my work. Just make sure you give me the appropriate credit the same way you would for any other scholarly resource. Here's the citation information:


```r
@book{kurzStatisticalRethinkingSecondEd2020,
  title = {Statistical rethinking with brms, ggplot2, and the tidyverse: {{Second}} edition},
  author = {Kurz, A. Solomon},
  year = {2020},
  month = {dec},
  edition = {version 0.1.1},
  url = {https://bookdown.org/content/4857/}
}
```



