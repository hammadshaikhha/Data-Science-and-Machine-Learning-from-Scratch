# Introduction
The "Linear Model Selection.ipynb" notebook discusses 1) Subset selection, 2) Step wise regression and 3) Shrinkage methods (lasso and ridge) for selecting from a set of linear models. These methods essentially inform of us of the predictors that should be contained in the regression for optimal model fitness.

# Data
The notebook uses school level achievement and characteristics data from New York. The data is [available on kaggle](https://www.kaggle.com/passnyc/data-science-for-good). We use model selection methods to find the important determinants of school level math achievememnt. 

## Dependencies
* numpy
* Pandas
* Matplotlib
* scikit-learn (just for lasso)

All dependencies can be installed using [pip](https://pip.pypa.io/en/stable/)

## Contribution Ideas
If anyone is interested in working further on improving this notebook, here are some ideas:
* Code lasso from scratch using numpy (don't rely on scikit-learn)
* Perform cross validation to find the optimal tuning parameter for lasso. Compare the model selected by lasso to the one selected by forward selection.

# References
[Subset selection video](https://www.youtube.com/watch?v=91si52nk3LA)

[Forward selection](https://www.youtube.com/watch?v=nLpJd_iKmrE)

[Backward selection](https://www.youtube.com/watch?v=NJhMSpI2Uj8)

[AIC, BIC, and adj Rsq video](https://www.youtube.com/watch?v=LkifE44myLc)

[Ridege regression for model selection video](https://www.youtube.com/watch?v=cSKzqb0EKS0)

[Lasso regression for model selection video](https://www.youtube.com/watch?v=A5I1G1MfUmA)
