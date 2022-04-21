# Dimensionality_reduction

Task 1:

The file winequality-red-reduced.csv is used for this task. Implementation of sparse PCA to fit a model with three components to the raw data as mentioned in the coursework. Sparse PCA is a version of PCA which attempts to find sparse components. The idea is similar to factor analysis. Sparsity is controlled by a parameter alpha. For this task, set alpha to 5 as per the coursework. Followed by generating the components found by sparse PCA. Inorder to understand the advantage of scaling we iterate the same process but scale the data first so that it has mean 0 and variance 1, which is then succeeded by sparse PCA. We can observe magnitude variation in the array of the output generated between the two different iterations.

Before scaling:

![image](https://user-images.githubusercontent.com/102992254/163504817-f27d0cf2-9368-4b02-a94c-0ccb5588315c.png)

After scaling:

![image](https://user-images.githubusercontent.com/102992254/163504875-aeb16a7a-291a-4db6-88a3-ec06780df218.png)

Task 2:

The file winequality-red-full.csv is used for this task. It contains the full dataset in which each row has 12 features. Will be using this dataset to predict the quality of the wine from the other variables using PCA and the effect that reducing the dimensionality of the dataset will have on the performance of the regression algorithm.

![image](https://user-images.githubusercontent.com/102992254/163505447-cc2181a1-87ce-4aa3-bced-4142d260ea6f.png)
