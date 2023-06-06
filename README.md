# ContinuousEvaluationWithKafka

This is implement a binary classifier aiming at predicting data exfiltration via DNS. The Classifier has benn implemented in the form of a static model were it is trained on the data and is given the new data in one shot. While, the dynamic model is trained on the data, however it keeps retraining on the new data it recieves.

## Static model

The following operations are preformed in the model:

>* Data Analysis. 
>* Feature engineering and data cleaning.
>* Feature Filtering/Selection. 
>* Model Training.
>* Model evaluation. 

## Dynamic model

The model is trained on the incoming data and its preformance is compared to the static model. 
