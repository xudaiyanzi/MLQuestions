so what is bias?

- bias is the difference between you prediction and true value
- -> high bias means the model is too simple, it can not capture the important features. e.g. you use the linear regression to fit the log function
- -> as a result, you are underfitting

  so what is variance?
- variance is how much your model predictions change if you trained with difference data sample
- -> high variance means the model is too complex, it memorize the data noise
- -> as a result, you are overfitting

  so what is the trade of bias-variance?
- if you use too complex model, you will have low bias and high variance
- if you use too simple model, you will have high bias and low variance.
- you need to balance the both to minize the error.
- error =  bias^2 + variance + irreducible noise, if you reduce bias, you will introduce higher variances; if you reduce variances, you make get larger bias.
