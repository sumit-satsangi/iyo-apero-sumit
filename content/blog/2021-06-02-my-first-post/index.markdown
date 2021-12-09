---
title: "First rbind post"
subtitle: ""
excerpt: "My first R post"
date: 2021-12-01
author: "Sumit Satsangi"
draft: false
images:
series:
tags:
  - R
categories:
  - R
layout: single
output: html_document
---

<style>
body {
text-align: justify}
</style>

<div class="figure">
<img src="featured.png" alt="Thumbnail" width="20%" />
<p class="caption">Figure 1: Thumbnail</p>
</div>

## Hello World!


```r
x <- "Hello World!"
print(x)
## [1] "Hello World!"
```

Since this is the first ever post on this website, what could be better than the old trustworthy *Hello World!* program.

## Some penguins to continue

*(after all, it is an R inspired website):*


```r
library(tidyverse)
library(knitr)
library(palmerpenguins)
#library(tinytex)
```

<div class="figure">
<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-4-1.png" alt="Histogram" width="100%" />
<p class="caption">Figure 2: Histogram</p>
</div>

## Why rbind.io

Found out that the *rbind* website during the session of famous [*Alison Hill*](https://www.apreshill.com). She not only introduced us to her **Hugo Apero** theme but also GIT push (believe me, it was my first time) and rbind.io.

Normal link with https:
![](https://youtu.be/RksaNh5Ywbo)

without https:
![](youtu.be/RksaNh5Ywbo)

with iframe:

<iframe width="560" height="315" src="https://youtu.be/RksaNh5Ywbo" frameborder="0" allowfullscreen></iframe>

[Introduce yourself online using blogdown and Hugo Apèro](https://www.youtube.com/watch?v=RksaNh5Ywbo)
