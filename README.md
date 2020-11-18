# KNN-Classification-for-Iris-Species

&nbsp;
### 1. Introduction
Here, I am working on a well-known Supervised Machine Learning algorithm known as KNN or k-Nearest Neighbors.
I am using the Iris data set to build the kNN model. Iris data is a very popular data set for machine learning. Species variable is our target variable which we will predict using our model.

###### KNN:
![Screenshot](Screenshot.png)

##### Steps:
1. Choose number of neighbors (K)
2. Consider K nearest neighbors of new data point and choose the distance metrics
3. Amongst these K neighbors, count the number of data points for each category
4. Assign the new data point to the most frequent neighboring category (most common category)

### 2. Data Preprocessing:
* Seperated independent and dependent variables
* Performed **Label Encoding** to transform the categorical dependent variable into numerical variable

### 3. Building KNN Model:
* Split the data into training and testing data sets. (20% - Test Data)
* Develop a basic KNN model with K neighbors = 3

### 4. Model Evaluation:
* Evaluated the base model using **Confusion Matrix, Accuracy, and Misclassification Error Rate**

### 5. Cross Validation:
* Performing **10 fold** cross validation
* Considering all **K values from 1 till 49**
* Obtaining average Accuracy for each K value
* Choosing the best model based on the Accuracy and Error rate 


