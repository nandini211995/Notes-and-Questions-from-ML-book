## **Chapter 2 : End-to-End Machine Learning Project**

1. What is univariate regression and multivariate regression?

```diff
+ In univariate regression, we are only trying to predict a single value i.e. only one x for y.
+ In multivariate regression, we are trying to predict multiple values i.e. multiple x1,x2,... for y.
```
2. What is RMSE(root mean square error)?

```diff
+ It gives an idea of how much error the system typically makes in its predictions.
``` 
$$
RMSE(X,h) = \sqrt{\frac{1}{m} \sum_{i=1}^{m}(h(x^{(i)}) - y^{(i)})^{2}}
$$
