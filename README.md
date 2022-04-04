# Dimensionality_reduction

Task 1:

The file winequality-red-reduced.csv is used for this task. One of your colleagues 
suggests that the non-quality aspects of this dataset could be modelled using three latent 
variables: content (capturing fixed acidity, volatile acidity, chlorides, free sulphur dioxide, total 
sulphur dioxide and sulphates), properties (capturing pH and alcohol) and quality (capturing a single variable: quality).

Use scikit learn’s implementation of sparse PCA to fit a model with three components to the raw 
data. Sparse PCA is a version of PCA which attempts to find sparse components. The idea is 
similar to that discussed for factor analysis. Sparsity is controlled by a parameter alpha. For this 
task, set alpha to 5. Print out the components found by sparse PCA.
Now scale the data so that it has mean 0 and variance 1 (you may wish to use scikit learn’s 
Standard Scaler). Similarly to above, use sparse PCA to fit a model with three components to the 
scaled data and print out the resulting components.
You should see a difference between the two results. Explain why there is a difference between 
the results and which of the two results is most likely to capture the relationships between the 
variables. For the result that you think is most likely to capture these relationships, discuss 
whether or not it supports your colleague’s suggestion for how to model the data using latent 
variables.

Task 2:

The file winequality-red-full.csv is used for this task. It contains the full dataset in which 
each row has 12 features. You are interested in using this dataset to predict the quality of the 
wine from the other variables using regression and in the effect that reducing the dimensionality 
of your dataset will have on the performance of your regression algorithm.

Choose a regression algorithm of your choice. Design and implement a methodology to select an 
appropriate reduction method and a dimensionality to reduce the dataset to. Compare the 
performance of your regression algorithm on the full dataset and your chosen reduced dataset.
Based on these results, comment on whether you believe dimensionality reduction was a useful 
technique for solving this regression problem. Justify your answer
