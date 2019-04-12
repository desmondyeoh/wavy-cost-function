# sq-err-logreg

## Why Not to Use "squared error cost function" for Logistic Regression

In Andrew Ng's Machine Learning course in Coursera, Andrew mentioned that using we should use logistic cost function instead of the squared error cost function used in linear regression. This is because squared error cost function will cause a lot of wavy-like cost function, which will have a lot of local optimums. He said that the wavy-like property is due to the non-linear sigmoid function used in the logistic regression hypothesis h. And, why this matters is because, having multiple local minima in cost function is bad for gradient descent as it's harder to find the global minimum.

In this notebook, we show that using squared error cost function will indeed cause wavy-like functions.
