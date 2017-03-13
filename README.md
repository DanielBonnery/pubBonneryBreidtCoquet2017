# KDE informative selection
`pubBonneryBreidtCoquet2017` is an R package that contains the source code to reproduce the graphs and simulations of a paper to come.

## 1. How to install the package

```r
devtools::install_github("DanielBonnery/pubBonneryBreidtCoquet2017",force=TRUE)
```

Note that this package depends on different packages we developped, that will be installed automatically, including:
* [pubBonneryBreidtCoquet2016](https://github.com/DanielBonnery/pubBonneryBreidtCoquet2017). pubBonneryBreidtCoquet2016 is a package that contains generic functions to simulate populations and draw samples

## 2. 
### 2.1. Graph 1 

### 2.2. Execution


```r
library("pubBonneryBreidtCoquet2017")
demo(w_graph1,package = "pubBonneryBreidtCoquet2017")
print(w_graph1)
```

![plot of chunk r2](figure/r2-1.png)

```r
print(w_graph1)
```

![plot of chunk r3](figure/r3-1.png)
