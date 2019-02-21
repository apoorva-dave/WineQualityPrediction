# WineQualityPrediction
Given a set of features as inputs, the task here is to predict the quality of wine on a scale of 0 - 10. 
I have solved it as a regression problem using Linear Regression.

## Dataset

The dataset used here is Wine Quality Data set from UCI Machine Learning Repository. 
I have attached the csv file needed for the regression task - winequality-red.csv
The same can also be found here https://archive.ics.uci.edu/ml/datasets/Wine+Quality

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

Output variable (based on sensory data): quality (score between 0 and 10)

## Dependencies

1. Python
2. Pandas
3. matplotlib
4. numpy
5. scikit-learn 

## Setup

1. Clone the repository
2. The repo contains the IPython Notebook for prediction task and the dataset as csv file.
3. Run the ipynb to see the results.

## Output

Correlation between different attributes

![1](https://user-images.githubusercontent.com/19779081/53142984-1725fc80-35bc-11e9-8dc5-cad2527bbb5c.PNG)

RMSE 

![2](https://user-images.githubusercontent.com/19779081/53143022-40df2380-35bc-11e9-950b-917386390967.PNG)

Coefficient values

![3](https://user-images.githubusercontent.com/19779081/53143050-5d7b5b80-35bc-11e9-846b-fd0ee3e09565.PNG)
