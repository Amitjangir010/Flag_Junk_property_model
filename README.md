# Flag_Junk_property_model
## Overview

The objective of this project is to develop a predictive model that can identify properties that are likely to be classified as "junk" based on their listing details and initial assessment. The aim is to assist businesses in prioritizing their renovation efforts and concentrating on properties with higher potential for success.

Data:
The project utilizes two datasets: Property_train.csv for training the model and Property_test_share.csv for testing purposes.
Preprocessing steps involve handling missing values, encoding categorical variables, and dividing the data into training and testing sets.

Models:
The primary machine learning model in this project is the RandomForestClassifier.and also used upsampling and selected best features by gridsearchcv before training .

Evaluation:
The model's performance is assessed using the ROC-AUC score. This metric provides a measure of the model's ability to differentiate between positive and negative classes.

Results:
The RandomForestClassifier achieved a 91% accuracy.
The ROC-AUC score for the model is 0.88, indicating strong performance in predicting junk properties.

Conclusion:
By accurately predicting properties that are likely to be difficult to sell, businesses can allocate their resources towards more promising opportunities, thereby minimizing losses and maximizing profitability.
