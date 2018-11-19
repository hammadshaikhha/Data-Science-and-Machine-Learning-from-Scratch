## Introduction
The linear contextual bandit notebook discussion bayesian linear regression in comparsion with standard linear regression. Bayesian linear regression with conjugate normal inverse gamma prior is used together with thompson sampling to implement the contextual bandit. The purpose of the contextual bandit is to choose the action the maximizes the expected reward given the context of the user. 

The notebook can be opened with google collab and the code can be adjusted there. This repository also contains a PDF file (supplementary material) with detailed notes on the bayesian linear regression and thompson sampling procedure implemented in this notebook.

## Dependencies
* numpy
* Pandas
* Matplotlib
* statsmodels
* scipy.stats

All dependencies can be installed using [pip](https://pip.pypa.io/en/stable/)

## References
[Details behind bayesian linear regression](http://www.biostat.umn.edu/~ph7440/pubh7440/BayesianLinearModelGoryDetails.pdf)

[Multiarm bandit vs. AB test](https://vwo.com/blog/multi-armed-bandit-algorithm/)

[Contextual bandit introduction](https://getstream.io/blog/introduction-contextual-bandits/)
