# ContinuousEvaluationWithKafka

This is implement a binary classifier aiming at predicting data exfiltration via DNS. The Classifier has benn implemented in the form of a static model were it is trained on the data and is given the new data in one shot. While, the dynamic model is trained on the data, however it keeps retraining on the new data it recieves.

## Static model

The following operations are preformed in the model:

 &emsp; * Data Analysis
 &emsp; * Feature engineering and data cleaning
 &emsp; * Feature Filtering/Selection
 &emsp; * Model Training
 &emsp; * Model evaluation

