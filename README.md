
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dlab-berkeley/efficient-reproducible-project-management-in-R/master?urlpath=rstudio)

# Efficient and Reproducible Project Management in R

by [Jae Yeon Kim](https://jaeyk.github.io/)

File an [issue](https://github.com/dlab-berkeley/efficient-reproducible-project-management-in-R/issues) if you have problems, questions or suggestions.

## Overview 

This workshop introduces tools and techniques to make a data science project efficient and reproducible in R. I recommend taking this workshop (1) if you have experienced difficulties organizing your project or (2) intend to share your code with other researchers (in a team or with the public). Science advances through the accumulation of reliable knowledge. A research project should be at the very least reproducible and, ideally, efficiently organized to make replication easy.

## Learning objectives 

- Part 1: [Organizing files and code](https://github.com/dlab-berkeley/efficient-reproducible-project-management-in-R/blob/master/code/01_organizing_files.Rmd)
- Part 2: [Making a project computationally reproducible and self-contained](https://github.com/dlab-berkeley/efficient-reproducible-project-management-in-R/blob/master/code/02_computational_reproducibility.Rmd)

## Prerequisites 

Basic familiarity with R required. 

## Setup 

Launch the bider or manually install the following three packages in R. 

```r

pacman::p_load(
  tidyverse, # tidyverse 
  here # computational reproducibility 
  )

```

# References 

- [Berkeley Research Data Management](https://researchdata.berkeley.edu/)

- [RStudio-Project-Management](https://github.com/dlab-berkeley/RStudio-Project-Management) by Evan Muzzall 

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
