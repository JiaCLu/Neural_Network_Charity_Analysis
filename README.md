# Neural_Network_Charity_Analysis

## Overview of the loan prediction risk analysis:
This analysis perform two machine learning algorithms: traditional machine learning and the neural network machine learning. I use the features in the provided dataset to help Beks create binary classifier to predict whether applicants will be successful if funded by Alphabet Soup. 

## Results
### Data Preprocessing
- The target variable is successful in the DataFrame which define funds successfully funded.
- IS_SUCCESSFUL column define as binary data to make yes or no decision using deep learning neural network.
- Drop the non-beneficial columns EIN and NAME which will not improve accuracy of the model.
### Compiling, Training, and Evaluating the Model
- For neural network model, in the first hidden layer using relu activation with 110 units of neurons, second hidden layer came out with 80 units of neurons, third and forth layers using sigmoid activation with 40 and 20 neurons to better fit for the model.
- The accuracy score in this model produce 72.6% which is below the target predictive accuracy score of 75%.
- To increase model performance, I remove noisy variables 'STATUS', 'SPECIAL_CONSIDERATIONS' and add additional neurons to additional hidden layers.

## Summary
The overall results of the deep learning model accuracy with 72.6% which we can consider this model is well under performing. My recommendation to use supervised machine learning model Random Forest Classifier, and decision trees to less outliers instead of using deep learning.