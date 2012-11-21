---
title       : NEM quarterly trends
subtitle    : updated november 2012
author      : mike sandiford
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
---

## Making it work

load data using R package 'aemo'



```r
require(plyr, ggplot2, aemo)
state = "VIC"
plots <- NEM_quarterly_trends(state = state)
```



---
## `VIC` mean demand
![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 

---
## `VIC` peak demand
![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 

---
## `VIC` min demand
![plot of chunk unnamed-chunk-4](figure/unnamed-chunk-4.png) 

---
## `VIC` mean to peak demand
![plot of chunk unnamed-chunk-5](figure/unnamed-chunk-5.png) 

---

## `VIC` revenue
![plot of chunk unnamed-chunk-6](figure/unnamed-chunk-6.png) 

---

## `VIC` volume weighted price
![plot of chunk unnamed-chunk-7](figure/unnamed-chunk-7.png) 



---

## `VIC` standard deviation
![plot of chunk unnamed-chunk-8](figure/unnamed-chunk-8.png) 

