# Neural_Network_Charity_Analysis

## Overview
The purpose of this assignment was to design a machine learning model to assess and predict the success of charitable donations.

## Results
### Data Preprocessing
- Target Variable: IS_SUCCESSFUL
- Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, ORGANIZATION, USE_CASE, INCOME_AMT, SPECIAL_CONSIDERATIONS
- Not Target or Features: EIN, NAME

### Compiling, Training, and Evaluating the Model
- Number of Neurons: 14
- Number of Layers: 3
- Activation Functions: Relu and Sigmoid
- Model Success: I was not able to achieve the 75% target. In fact, my optimization attemps somehow made the model worse. It went from 65% accuracy to 58% accuracy.
- Optimization Attempts:
    - Dropped ORGANIZATION and APPLICATION TYPE
    - Added one layer
    - Added nine neurons

## Summary
Overall, the machine learning model had an accuracy of 65%. Logistic regression could be another option to solve this classification issue since we are trying to achieve a binary classifier - is the donation successful, yes or no. 