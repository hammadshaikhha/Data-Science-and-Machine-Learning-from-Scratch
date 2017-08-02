## Purpose
The notebook "Bayesian Linear Regression.ipynb" outlines the differences between the frequentist and bayesian approaches to linear regression. It shows how the bayesian approach to linear regression is analagous to regularization. Both the frequentist and bayesian linear regression approach is applied to the IMDB data set and it shown that bayesian approach seems to be fit the data more smoothly relative to the frequentist approach. 

## Data
I use the IMDB movie data set from kaggle and examine the relationship between IMDB rating and gross sales revenue using a frequentist multiple linear regression (degree 5), and bayesian multiple regression (degree 5). For analysis purposes I clean the data set to only contain IMDB movie rating and gross sales revenue for US movies.

## Dependencies
* numpy
* Pandas
* Matplotlib

All dependencies can be installed using [pip](https://pip.pypa.io/en/stable/)

## References
[Siraj's video on hyperparameters](https://www.youtube.com/watch?v=ttE0F7fghfk)

[Video introducing bayesian linear regression](https://www.youtube.com/watch?v=dtkGq9tdYcI)

[Frequentist vs Bayes Regression stackexchange discussion](https://stats.stackexchange.com/questions/252577/bayes-regression-how-is-it-done-in-comparison-to-standard-regression)
