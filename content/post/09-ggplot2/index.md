---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "09 - Data Visualization with {ggplot2}"
subtitle: ""
summary: " "
authors: []
tags: []
categories: []
date: "2024-09-21"
weight: 10
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
  url: /slides/09-slides.html
- icon: readme
  icon_pack: fab
  name: Cheat Sheet
  url: https://github.com/rstudio/cheatsheets/blob/main/data-visualization-2.1.pdf
- icon: laptop-code
  icon_pack: fas
  name: Primers
  url: https://rstudio.cloud/learn/primers/3
---

<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>

Data visualization is at the very core of science. In order to understand and glean insights from our data, we need different ways of representing it visually. R has an incredible capacity for creating all sorts of plots, charts, and tables, and today we will only scratch the surface. We will discuss the fundamentals of the powerful ggplot2 package and the “grammar of graphics” that underlies it.

------------------------------------------------------------------------

### Further Reading

<div class="book">

1.  R for Data Science chapter on [data visualization](https://r4ds.had.co.nz/data-visualisation.html)

2.  Modern Dive chapter on [data visualization](https://moderndive.com/2-viz.html)

3.  Cookbook for R chapter on [data visualization](http://www.cookbook-r.com/Graphs/)

4.  [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/)

5.  [the ggplot flipbook](https://evamaerey.github.io/ggplot_flipbook/ggplot_flipbook_xaringan.html#1) by Gina Reynolds—shows how to create plots line-by-line

</div>
