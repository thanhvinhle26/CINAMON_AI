
# REPORT
>1. The choice of the kernel function K is not crucial to the accuracy of kernel density estimators, so we use the standard multivariate normal kernel throughout.
>2. On the other hand, the choice of the bandwidth matrix H is the single most important factor affecting its accuracy since it controls the amount and orientation of smoothing induced.  
>**SOLUTION**
        

||Pros|Con|
|---|:---:|---:|
| silverman's rule |Easy to compute and fast | Lower accuracy |
| least squares cross validation |Slow to compute| Better accuracy |

![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/KDE/EvaluateDistribution.png)

