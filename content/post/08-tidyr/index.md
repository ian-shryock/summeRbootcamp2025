---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "08 - Data Tidying with {tidyr}"
subtitle: ""
summary: " "
authors: []
tags: []
categories: []
date: "2024-09-21"
weight: 9
featured: false
draft: false

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
  url: /slides/08-slides.html
- icon: readme
  icon_pack: fab
  name: Cheat Sheet
  url: https://github.com/rstudio/cheatsheets/blob/main/data-import.pdf
- icon: laptop-code
  icon_pack: fas
  name: Primer 1
  url: https://rstudio.cloud/learn/primers/4.1
- icon: laptop-code
  icon_pack: fas
  name: Primer 2
  url: https://rstudio.cloud/learn/primers/4.2
---

<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>

The concept of tidy data is, as the name suggests, of primary importance in the tidyverse. This lesson will introduce you to the criteria of tidy data, why it’s important, and how to reshape your raw data into a tidy format using `pivot_wider()` and `pivot_longer()`.

------------------------------------------------------------------------

### Further Reading

<div class="book">

1.  R for Data Science chapter on [tidy data](https://r4ds.had.co.nz/tidy-data.html#pivoting)

2.  Tutorial on [reshaping data](https://rladiessydney.org/courses/ryouwithme/02-cleanitup-5/) from R-Ladies
    Sydney

</div>
