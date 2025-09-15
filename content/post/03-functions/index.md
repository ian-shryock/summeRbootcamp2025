---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "03 - Functions, Packages, & Debugging"
subtitle: ""
summary: " "
authors: []
tags: []
categories: []
date: "2024-09-21"
weight: 4
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
  url: /slides/03-slides.html
- icon: laptop-code
  icon_pack: fas
  name: Primer
  url: https://rstudio.cloud/learn/primers/6.1
---

<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>

Functions are the “verbs” of R—they allow you to actually do interesting things with your data. We will cover the basics of how to use functions in R, how to get access to different functions by downloading packages, some general principles for what to do when you run into problems.

------------------------------------------------------------------------


### Further Reading

<div class="book">

1.  [How to read an R help page](https://socviz.co/appendix.html#a-little-more-about-r) by Kieran Healy

2.  [“Object of type ‘closure’ is not subsettable”](https://rstudio.com/resources/rstudioconf-2020/object-of-type-closure-is-not-subsettable/), keynote talk by Jenny Bryan at rstudio::conf(2020)

3.  Deep dive into [debugging](https://rstudio-conf-2020.github.io/what-they-forgot/materials/debugging.pdf) by Jim Hester

</div>
