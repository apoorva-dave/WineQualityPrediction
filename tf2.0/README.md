 Wine quality prediction using Deep Learning.The code has been implemented using Tensorflow 2.0 APIs. Model has been trained using
 GPU on Google Colab.
 The MSE, MAE are a bit higher than the original implementation in scikit-learn.
However, this could be due to a couple of reasons.

1 - The train and test split is different. So it would definitely have an impact on the result. I have saved the train and test data 
    in separate csvs. Someone could use those CSVs to compare against the numbers obtained using a neural network model to the numbers
    in traditional machine learning.
2 - The amount of data is not very high. roughly around 1600 samples. As there is less data, so the traditional machine learning could  
    genuinely be the better option among the two.
    
