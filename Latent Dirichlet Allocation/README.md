## Purpose
The notebook "Latent Dirichlet Allocation.ipynb" discusses the Latent Dirichlet Allocation (LDA) unsupervised learning algorithm which is used for topic analysis in text data. It first assumes all documents in the text corpus consists of a mixture of a finite number of topics, and each topic is another mixture of similar words. Given this assumption, LDA uses bayesian inference to back out the distribution of topics and their associated words. 

## Data


## Work in Progress
Implement TF-IDF prior to applying LDA and check whether the words that appear in all topics resulting from LDA are ignored. 

## Dependencies
* numpy
* Pandas
* re
* nltk

All dependencies can be installed using [pip](https://pip.pypa.io/en/stable/)

## References
[Siraj's video on Generative Models and LDA](https://www.youtube.com/watch?v=HyuBTMaKFmU)

[Great video introducing LDA](https://www.youtube.com/watch?v=3mHy4OSyRf0)

[Video on Dirichlet distribution](https://www.youtube.com/watch?v=nfBNOWv1pgE)

[Great answer on Quora about LDA](https://www.quora.com/What-is-a-good-explanation-of-Latent-Dirichlet-Allocation)
