---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "07 - Data Wrangling with {dplyr}"
subtitle: ""
summary: " "
authors: []
tags: []
categories: []
date: "2024-09-21"
weight: 8
featured: false
draft: false
social: false
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Artwork by @allison_horst"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
links:
- icon: film
  icon_pack: fas
  name: Slides
  url: /slides/07-slides.html
- icon: readme
  icon_pack: fab
  name: Cheat Sheet
  url: https://github.com/rstudio/cheatsheets/blob/main/data-transformation.pdf
- icon: laptop-code
  icon_pack: fas
  name: Primer 1
  url: https://rstudio.cloud/learn/primers/2.2
- icon: laptop-code
  icon_pack: fas
  name: Primer 2
  url: https://rstudio.cloud/learn/primers/2.3
---

<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>

When you are given data to analyze, it will almost always be in a format that makes it hard to create visualizations, perform modelling, and generate tables. In other words, most of the time, it will need to be wrangled into the correct format. The dplyr package has a very powerful set of functions for doing just this. Today we will be covering the core dplyr “verbs” that allow you to transform your data with optimal specificity and efficiency.

------------------------------------------------------------------------


### Further Reading

<div class="book">

1.  R for Data Science chapter on [data transformation](https://r4ds.had.co.nz/transform.html)

2.  [Tutorial on tidyselect](https://tladeras.shinyapps.io/learning_tidyselect/) by Ted Laderas

3.  Flipbooks on [data wrangling](https://evamaerey.github.io/data_manipulation/one_stream_wrangle.html#1) and [summarizing](https://evamaerey.github.io/data_manipulation/summarize.html#3) by Gina Reynolds

</div>
