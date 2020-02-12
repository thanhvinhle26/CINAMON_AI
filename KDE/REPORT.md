
# REPORT
>1. The choice of the kernel function K is not crucial to the accuracy of kernel density estimators, so we use the standard multivariate normal kernel throughout.
>2. On the other hand, the choice of the bandwidth matrix H is the single most important factor affecting its accuracy since it controls the amount and orientation of smoothing induced.
>**SOLUTION**
        

||Pros|Con|
|---|:---:|---:|
| silverman's rule |Easy to compute and fast | Lower accuracy |
| least squares cross validation |Slow to compute| Better accuracy |

![](https://github.com/thanhvinhle26/CINAMON_AI/blob/master/KDE/EvaluateDistribution.png)
### IMPLEMENTATION
>1. Compressed image from 784 dimensions down to 2 for improving time computing.
>2. Find bandwidth with Silver' rule call H1.
>3. Find bandwith by LSCV call H2.
>4. Generate new data
>5. Use K-S Statistics To Evaluate If Generated Data Is The Same Distribution As Dataset
