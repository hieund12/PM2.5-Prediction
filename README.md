# PM2.5-Prediction
Handcrafted "linear regression" using Adaptive Gradient Descent.

### File description:
 1. train.csv: 12 months' wheather information which only contains 18 features per hour for the first 20 days each month. 
 2. test.csv: For the rest 10 days per month, use the data of 9 continuous hours to predict the PM2.5 value in the 10th hour.
 3. model.npy: the trained weights which stand for the model
 4. predict.csv: the prediction result.
 
 ### Tools and libraries:
 python 3.6; numpy, math, scv
 
