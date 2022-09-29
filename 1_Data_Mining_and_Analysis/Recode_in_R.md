Recoding data in R
================

``` r
x1 <- iris[,1]
A <- rep(0,150)
A[x1>=7] <- 1
table(A)
```

    ## A
    ##   0   1 
    ## 137  13
