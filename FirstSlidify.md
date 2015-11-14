---
title       : First Slide of Pablo in Slidify
subtitle    : (hope it works)
author      : Pablo Tercero
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Read-And-Delete

1. Edit YAML front matter
2. Write using R Markdown
3. Use an empty line followed by three dashes to separate slides!

--- .class #id 
library(datasets)
data("airquality")


## Slide 2
--- 
This should be very pretty graph 
pairs(airquality)

```r
pairs(airquality)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 



