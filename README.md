# AdaBoostClassifier---Predict-Species
Predict flower specifies using AdaBoost Classifier.

### Contents
This project is meant to explore, analyse, visualize and predict the salary of an individual:
      1. Id    
      2. SepalLengthCm
      3. SepalWidthCm
      4. PetalLengthCm
      5. PetalWidthCm
      6. Species   

Machine Learning Steps Follwed to acheve the objective.
1. Import necessary Libraries
2. Read the csv dataset
3. Check for the null values and the unwanted values in the dataset
     - We checked for the null values and unwanted values in the dataset there were none.  
4. Perform preprocessing on target variable and convert it into numeric values in order to predict the same.
4. Train Test Split the dataset.
5. Use AdaBoostClassifier with SVC base_estimator.
6. Prediction of Train data
     - We got the accuracy of  - 0.93 for Train data 
7. Prediction of Test data 
     - We got the Test accuracy of - 0.96.
