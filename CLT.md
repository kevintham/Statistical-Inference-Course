---
title: "Investigation of Central Limit Theorem"
author: "Kevin Tham"
date: "April 25, 2018"
output:
  html_document:
    keep_md: true
  pdf_document: default
---



# Simulation Exercise



## Overview

In this exercise we investigate the exponential distribution and compare it with the Central Limit Theorem. We expect that the means from a large number of identical exponential distributions will themselves form a normal distribution with known mean and standard deviation

We set the seed to ensure that the following analysis is reproducible:



We prepare a thousand repetitions of 40 samples drawn from an exponential distribution.





From our simulated data we can obtain the sample mean:


```
## [1] 0.6088292
```

<img src="CLT_files/figure-html/unnamed-chunk-6-1.png" style="display: block; margin: auto;" />
