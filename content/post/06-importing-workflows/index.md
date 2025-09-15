---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "06 - Importing Data & Project-Oriented Workflows"
subtitle: ""
summary: " "
authors: []
tags: []
categories: []
date: "2024-09-21"
weight: 7
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
  url: /slides/06-slides.html
- icon: readme
  icon_pack: fab
  name: Cheat Sheet
  url: https://github.com/rstudio/cheatsheets/blob/main/data-import.pdf
---

<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>

The first step of any data analysis workflow is to get data into R. This isn’t always as straightforward as you might think, but, fortunately, there are some core functions that make this easy and efficient. Since we are starting at the beginning, we will also discuss the idea of a project-oriented workflow, which is a way to keep an organized and consistent process whenever you work with data in R that will also make your work reproducible and shareable. And the decisions you make right at the start of a data analysis project—even before importing your data—will have a lot of down-stream consequences.

------------------------------------------------------------------------


### Further Reading

<div class="book">

1.  R for Data Science [Ch 8: Project-oriented workflow](https://r4ds.had.co.nz/workflow-projects.html#rstudio-projects)

2.  Why Jenny Bryan will come [set your computer on fire 🔥](https://www.tidyverse.org/blog/2017/12/workflow-vs-script/) if you use `setwd()`.

3.  [How to use the here package](http://jenrichmond.rbind.io/post/how-to-use-the-here-package/) by Jenny Richmond

</div>
