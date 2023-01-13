# Churn-Prediction
This is a customer churn prediction model using the Artificial Neural Network(ANN) which predicts how likely a customer is to leave the bank in future based on the values of other attributes like CreditScore, Tenure, ActivityStatus etc. 

# Architecture
*The input layer consist of 11 weights, the hidden layer consists of 3 perceptrons which passes the result to the output layer.*
*After adding the respective biases the total trainable parameters becomes 40.
*Activation function used is sigmoid function at every layer.
*Loss function and optimizer used is binary cross entropy and Adam optimizer respectively.
*The model is trained over 10 epochs and the acuracy acheived is around 80 percent.

# procedure
*Open the Customer_Churn_prediction.ipynb file in jupyter notebook 
*Provide the appropriate path of downloaded dataset to read_csv() in the 2nd cell of code.
