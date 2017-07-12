## Purpose
Self Organizing Maps (SOM) are a type of neural network that is trained using unsupervised learning algorithm for the purposes of demensionality reduction and data clustering. The notebook "Self Organizing Maps for Clustering.ipynb" discusses the intuition and theory behind SOM, and applies it to a publicly avaiable education data set from the state of Tennessee to classify each student as being weak, average, or gifted based on their characteristics. 

## Data
From 1985-1989 the state of Tennessee conducted a experiment to examine the causal impacts of smaller class sizes on student test scores. The data set from this study is now publicly available and can be found on [dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=hdl:1902.1/10766). I use a subset of this data set to apply SOM. In particular, I keep 6 variables for the grade 1 students, free or reduced lunch status, school absences, math, reading, listening, and word study standardized test scores. I only keep students that non-missing data for each of these variables. 

## Dependencies
* numpy
* Pandas
* Matplotlib

All dependencies can be installed using [pip](https://pip.pypa.io/en/stable/)

## Work In Progress
The notebook shows how to classify the input data into 3 groups using SOM. However I am open to ideas on how this 6 demensional data should be viewed on a 2D plane. There seem to be many ways to do it as show in this data visualization video from MATLAB SOM library [MATLABs Neural Network Toolbox](https://www.youtube.com/watch?v=1z5wDCubvV0) which applies SOM to the standard Iris data set. 

## References
[Siraj's Video on Neural Networks](https://www.youtube.com/watch?v=ov_RkIJptwE&t=1s)

[Video on using SOM for Classification of Input Data](https://www.youtube.com/watch?v=H9H6s-x-0YE)

[Tutorial on SOM with some code](http://www.ai-junkie.com/ann/som/som1.html)

[Tutorial on SOM with python code](http://blog.yhat.com/posts/self-organizing-maps-1.html)

[Lecture Slides on SOM](http://www.cs.bham.ac.uk/~jxb/NN/l16.pdf)
