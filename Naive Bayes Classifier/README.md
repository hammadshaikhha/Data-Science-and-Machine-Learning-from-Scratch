## Purpose
Naive Bayes is a classification algorithm that uses the Bayes theorem together with a assumption of conditional independence to assign probabilities to all classes given the observation features. The notebook "Naive Bayes.ipynb" introduces the Naive Bayes algorithm, and applies it to classify Youtube comments as spam or ham (legitimate comments). 

## Data
The data used in the Naive Bayes notebook is from the UCI machine learning repository. It contains several comments from very popular music videos from youtube and has labels for each comment being spam or ham. The youtube spam collection data set can be found [here](https://archive.ics.uci.edu/ml/datasets/YouTube+Spam+Collection).

## Work in Progress
I am trying to use TF-IDF instead of bag of words model and compare whether the classification accuracy on the test set increases.

## Dependencies
* numpy
* Pandas
* re

All dependencies can be installed using [pip](https://pip.pypa.io/en/stable/)

## References
[Siraj's video on Probability and Naive Bayes](https://www.youtube.com/watch?v=PrkiRVcrxOs)

[Great introduction to Bayes Theorem](https://www.youtube.com/watch?v=R13BD8qKeTg&t=551s)

[Simple introduction to Naive Bayes](http://machinelearningmastery.com/naive-bayes-tutorial-for-machine-learning/)

[Naive Bayes from Scratch in Python on Diabetes Classification](http://machinelearningmastery.com/naive-bayes-classifier-scratch-python/)

[Alberto Blanco notebook on sentiment analysis](https://github.com/alberduris/The_Math_of_Intelligence/tree/master/Week6)
