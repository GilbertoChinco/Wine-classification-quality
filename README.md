# About the project: Wine-classification-quality
Data science &amp; machine learning project

This is otther begginer level project of data science and machine learning. It's about a dataset of wine, the dataset consists two differente wine "red wine" and "white wine" 

These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 12 constituents found in each of the two types of wines. 


Input variables (based on physicochemical tests):
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol

Output variable (based on sensory data):
12. quality (score between 0 and 10)
13. Class --> 0 : "red" ||  1 : "white" 

This project was divided in three stages
1. Data cleaning
2. Data visualization
3. Data modeling

## Data cleaning
* Fortunately, there were not missing values in the dataset so we did not replace and drop values
* the datasets were separated, one for "red wine" and other for "white wine"
* The idea was concatenate the two datasets and aggregate a column with the name target, the *"red-wine" : 0* and the *"white-wine" : 1*

## Data visualization
* Look the correlation, distribution between all the variables

## Data modeling
the dataset have a column withe name target so it's a supervised learning problem, the algorithms used for this project were:
* K Nearest Neighbors 
  * test set accuracy = 0.9912
  * train test accuracy = 0.9973
* Logistic Regression 
  * jaccard accuracy = 0.9638
  * Logarithmic loss = 0.0956
* Decision Tree
  * accuracy = 0.9830
* Support Vector Machine
  * accuracy f1 = 0.9830
  * jaccard accuracy = 0.9341
