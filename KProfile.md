---
title: "K's DS Profile"
author: "K Theobald"
date: "1/21/2019"
output:
  html_document:
    keep_md: true
---

## R Markdown

This R Markdown documents the entry level of Profile for K in Data Science. 

#Variables and Scale
  *Scale is 1:5 with 5 being the Best
  *Programming (aka. Computer Programming)
  *Math
  *Stats (aka. Statistics)
  *Machine Learning
  *Domain Expertise
  *Comm. Pres. Skills (aka. Communication Presentation Skills)
  *Data Visual (aka. Data Visualization)

#Session

```r
sessionInfo()
```

```
## R version 3.5.1 (2018-07-02)
## Platform: x86_64-apple-darwin15.6.0 (64-bit)
## Running under: macOS Sierra 10.12.6
## 
## Matrix products: default
## BLAS: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRblas.0.dylib
## LAPACK: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRlapack.dylib
## 
## locale:
## [1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## loaded via a namespace (and not attached):
##  [1] compiler_3.5.1  magrittr_1.5    htmltools_0.3.6 tools_3.5.1    
##  [5] yaml_2.2.0      Rcpp_1.0.0      stringi_1.2.4   rmarkdown_1.11 
##  [9] knitr_1.20      stringr_1.3.1   digest_0.6.18   packrat_0.5.0  
## [13] evaluate_0.12
```

#Code and Barplot for K's profile

```r
category <- c("Programming", "Math", "Stats", "Machine Learning", "Domain Expertise", "Comm. Pres. Skills", "Data Visual")
Ranking <- c(2, 3, 2, 2, 2,3,2)
k = data.frame(category, Ranking)
barplot(k$Ranking, cex.names=.5, names.arg=(k$category), ylab="Ranking", xlab="Category", main="K's Ranking")
```

![](KProfile_files/figure-html/unnamed-chunk-2-1.png)<!-- -->

