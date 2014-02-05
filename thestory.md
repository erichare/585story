A Non-Normal Life 

By: "The Gang"
========================================================

In the beginning, there was probability. Well, there probably was. There were all sorts of distributions of all different sorts, and it was wonderful.

![IT WAS GLORIOUS](http://i.imgur.com/FVXGtV0.png)




=======
All of the distributions lived in perfect harmony.

![SUCH COOPERATION](http://i.imgur.com/NayB2RR.gif)

Until one day, a new distribution appeared... and ABnormal distribution
![NOOOOO!!!!](http://i.imgur.com/OVe8D.jpg)



```r
rabnorm <- function(n, mean = 0, sd = 1, useless = "0xFFFFFF") {
    return(rcauchy(n)%%as.numeric(useless))
}
qplot(rabnorm(800), geom = "histogram")
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 


![Trap](http://cccpwned.com/img/ackbar.jpg)


```r
abnormal_land = function() {
    "(" = function(x) {
        return(5 * x)
    }
}
```


