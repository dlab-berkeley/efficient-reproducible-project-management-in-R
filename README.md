# Efficient and Reproducible Project Management in R

by [Jae Yeon Kim](https://jaeyk.github.io/)

## Overview 

This workshop introduces tools and techniques to make a data science project efficient and reproducible in R. I recommend taking this workshop (1) if you have experienced difficulties organizing your project or (2) intend to share your code with other researchers (in a team or with the public). Science advances through the accumulation of reliable knowledge. A research project should be at the very least reproducible and, ideally, efficiently organized to make replication easy.

## Learning objectives 

- Part 1: Organizing files 
- Part 2: Making a project computationally reproducible 
- Part 3: Using Git and GitHub for version control and project management

## Prerequisites 

Basic familiarity with R, Bash, and Git/GitHub required. 

## Setup 

1. Install the following three packages in R. 

```r

pacman::p_load(
  tidyverse, # tidyverse 
  here # computational reproducibility 
  )

```

2. Install Git and sign up GitHub (if you haven't) 

- [Installing Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) 
   - Don't forget to do basic Git configurations. Here's a [step-by-step tutorial](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration). 
- [Singing up for a new GitHub account](https://docs.github.com/en/github/getting-started-with-github/signing-up-for-a-new-github-account)
   - Take advantage of [the GitHub Student Developer Pack](https://education.github.com/pack)

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
