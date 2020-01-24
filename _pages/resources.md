---
layout: archive
title: "Additional Resources"
permalink: /resources/
author_profile: true
---

{% include base_path %}

<!-- Edit below this line -->

Below are some additional resources and references you may find helpful throughout the course. These will be continuously updated, so stay tuned!

### Getting started

- [How to install R](https://stat545.com/install.html)
- [A brief intro to R](https://stat545.com/r-basics.html)

The following primers from RStudio.com are very helpful:

- [The Basics](https://rstudio.cloud/learn/primers/1)
- [Work with data](https://rstudio.cloud/learn/primers/2)
- [Visualize data](https://rstudio.cloud/learn/primers/3)
- [Tidy your data](https://rstudio.cloud/learn/primers/4)

Free e-book: [R for Data Science](https://r4ds.had.co.nz/)

- With a focus on chapters 1-7, 9-12, 15, 17–20. The beginning of each chapter is more useful than the end of each chapter.

### Other resources, books of interest, resources we may use/you might find useful

Thinking about stats

- [Seeing theory](https://seeing-theory.brown.edu/)
- [Modern Statistics for Biology](http://web.stanford.edu/class/bios221/book/)
- [datacamp](https://www.datacamp.com/home)
- [modern dive](https://moderndive.com/)
- [Visualizations from W&S](http://www.zoology.ubc.ca/~whitlock/Kingfisher/KFhomepage.htm)

R cheatsheets

- [RStudio](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)
- [dplyr](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf)
- [ggplot2](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf)
- [base R](http://github.com/rstudio/cheatsheets/raw/master/base-r.pdf)
- [RMarkdown](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf)
- See all the cheatsheets [here](https://www.rstudio.com/resources/cheatsheets/#ide)

More R resources

- [Intro R for genomics](https://carpentrieslab.github.io/genomics-r-intro/)
- [R for Data Science](https://r4ds.had.co.nz/)
- [Advanced R](https://adv-r.hadley.nz/)

Data Viz

- [Data Viz: A practical intro (R focussed)](https://socviz.co/)
- [Fundamentals of Data Viz (conceptual)](https://serialmentor.com/dataviz/)

[Youtube channel](https://www.youtube.com/channel/UCn9LZMDf0A2m_cQHbZt9OJQ?view_as=subscriber) of former student working through tidyverse examples.

---

### Getting started with R Markdown

R markdown comes installed with RStudio, however if you are running into errors when knitting an Rmarkdown file or find you want to get your own copy of `rmarkdown` from CRAN, you can run the following:

```R
# Running this also installs the following dependencies:
# ‘highr’, ‘markdown’, ‘knitr’, ‘evaluate’, ‘base64enc’, ‘mime’, ‘tinytex’, ‘xfun’
install.packages("rmarkdown")
```

RStudio has a helpful and quick intro to R Markdown that you can find [here](https://rmarkdown.rstudio.com/articles_intro.html).

If you run into error messages when you try to knit an Rmarkdown file to **output a PDF** that says something along the lines of missing the `tinytex` package, you can install `tinytex` with the following lines:

```R
install.packages("tinytex")
tinytex::install_tinytex()  # install TinyTeX
```

Rmarkdown needs LaTeX installed to generate a PDF output when you knit an Rmarkdown file.

If you are still running into additional errors with Rmarkdown, please email Yaniv and/or Chaochih.

