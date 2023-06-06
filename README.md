# ContinuousEvaluationWithKafka

This is implement a binary classifier aiming at predicting data exfiltration via DNS. The Classifier has benn implemented in the form of a static model were it is trained on the data and is given the new data in one shot. While, the dynamic model is trained on the data, however it keeps retraining on the new data it recieves.

## Static model

The following operations are preformed in the model:

   &emsp; &emsp; - Data Analysis. <br>
   &emsp; &emsp; - Feature engineering and data cleaning. <br>
   &emsp; &emsp; - Feature Filtering/Selection. <br>
   &emsp; &emsp; - Model Training. <br>
   &emsp; &emsp; - Model evaluation. <br>

