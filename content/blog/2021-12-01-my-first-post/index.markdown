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
text-align: justify
}
</style>

<style type="text/css">
.panelset {
  --panel-tab-foreground: currentColor;
  --panel-tab-active-foreground: #0047bd;
  --panel-tab-hover-foreground: #0047bd;
  --panel-tabs-border-bottom: #ddd;
  --panel-tab-inactive-opacity: 0.5;
  --panel-tab-font-family: Roboto, Menlo, Consolas, Monaco, Liberation Mono, Lucida Console, monospace;\
}
</style>

## Hello World!


```r
x <- "Hello World!"
print(x)
## [1] "Hello World!"
```

Since this is the first ever post on this website, what could be better than the old trustworthy `<Hello World!>` program.

## Some penguins to continue
*<sup>(after all, it is an R inspired website):</sup>*


```r
library(tidyverse)
library(knitr)
library(palmerpenguins)
#library(tinytex)
```

<div class="figure">
<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-4-1.png" alt="Histogram" width="100%" />
<p class="caption">Figure 1: Histogram</p>
</div>

## Why rbind.io

Found out about the *rbind* website during the session of famous [*Alison Hill*](https://www.apreshill.com). She not only introduced us to her **Hugo Apero** theme but also GIT push (believe me, it was my first time) and rbind.io.

[![Introduce yourself online using blogdown and Hugo Apèro](https://i.ytimg.com/vi/RksaNh5Ywbo/maxresdefault.jpg)](https://www.youtube.com/watch?v=RksaNh5Ywbo)
*<sup>Link opens in a new window</sup>*


I was planning to use www.canva.com but my 10 year old princess has promised to make all the thumbnails and images for the website. Here is the thumbnail and original image:
{{< panelset class="greetings" >}}
{{< panel name="Thumbnail" >}}
<img src="featured.png" width="20%" />
{{< /panel >}}
{{< panel name="Full Scale Pic" >}}
<img src="featured.png" width="100%" />
{{< /panel >}}
{{< /panelset >}}

Let me know how this looks like. I am just a newbie (oldbie, to be precise) in this area and hopefully can provide my contribution back to the society while learning a thing or two.

I will try to keep uploading new content now and then. Strictly speaking, there is no agenda as of now. So don’t know if I would be categorizing anything on the website. Eventually, it will come though.

So long!

Stay safe, stay with family, wear mask!!!

above all, keep smiling and keep learning…
