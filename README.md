# Week-6-Algorithms
# ANA505 - Week 6 algorithms assignment

## SVM Algorithm
Using Petal Length and Petal Width, created two hyperlanes as descision boundries to predict the species of flower as Setosa, Versicolor, or Virginica. Used that 
model to predict which species a flower should belong to based on Petal Length and Petal Width.  
### SVM Accuracy: 97.3333%

## K Means Algorithm
Chose to separate dataset with k=3 centroids, with Sepal Length, Sepal Width, Petal Length, and Petal Width normalized.  Then used the result to classify 
flowers as the species Setosa, Versicolor, or Virginica.  Of 150 flowers attempted to be classified, 133 were correctly classified and 17 were incorrectly classified.
### K Means Accuracy: 133/150 = .8866667 or 88.66667%

## C5.0 Algorithm
Splits the data into a training and a test dataset either based on species (Setosa, Versicolor, and Virginica), by numerical sequence of the data, or randomly 
using "carat".  This model used the random option to build the model on the training data.  Then used the test data and one parameter to predict the species of 
the flowers.  Out of 45 observations in the table, 43 were classified correctly and 2 were classified incorrectly.
### C5.0 Accuracy: 95.6%
