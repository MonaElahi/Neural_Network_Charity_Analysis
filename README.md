# Neural Network Charity Analysis


# Overview of the analysis

The purpose of his analysis to create machine learning and neural networks 
models by using the features in the provided dataset to create a binary classifier 
that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

# Results

## Data Preprocessing

### What variable(s) are considered the target(s) for your model?
The target variable is "IS_SUCCESSFUL" which is a binary data, classifies charity is successful or not.

### What variable(s) are considered to be the features for your model?

All the below variables except of "IS_SUCCESSFUL" are features.

![git-hub](https://github.com/MonaElahi/Neural_Network_Charity_Analysis/blob/9345f73157f444e3582685e068e81226f751e46f/Images/Features.PNG)

### What variable(s) are neither targets nor features, and should be removed from the input data?

There are two noisy varibales which should be dropped from data for percision. 
![git-hub](https://github.com/MonaElahi/Neural_Network_Charity_Analysis/blob/9345f73157f444e3582685e068e81226f751e46f/Images/DroppedColumns.PNG)

## Compiling, Training, and Evaluating the Model

### How many neurons, layers, and activation functions did you select for your neural network model, and why?
I have taken 43 features and 80 nodes for 1st layer, and 30 nodes for 2nd layer. 
![git-hub](https://github.com/MonaElahi/Neural_Network_Charity_Analysis/blob/9345f73157f444e3582685e068e81226f751e46f/Images/HiddenLayers.PNG)

For 1st and 2nd hidden layer activation function used is "relu"
Output activation function used is "Sigmoid" nn

![git-hub](https://github.com/MonaElahi/Neural_Network_Charity_Analysis/blob/9345f73157f444e3582685e068e81226f751e46f/Images/ActivationFunction.PNG)

### Were you able to achieve the target model performance?
The target accuracy for this model was 75% however the acheived accuracy is 73.46%

![git-hub](https://github.com/MonaElahi/Neural_Network_Charity_Analysis/blob/9345f73157f444e3582685e068e81226f751e46f/Images/AccuracyScore.PNG)

###What steps did you take to try and increase model performance?

I did 3 attempts to optimize the performance of the model.
1ST attempt by adding one more layer, with 3 layers model accuracy score is 73.20%

![git-hub](https://github.com/MonaElahi/Neural_Network_Charity_Analysis/blob/450fdea22016e3694c41e67cc012433a2d69e684/Images/2ndAttempt.PNG)

2ND attempt by adding two more layers and with the total of 4 layers accuracy score is 74.71%

![git-hub](https://github.com/MonaElahi/Neural_Network_Charity_Analysis/blob/9345f73157f444e3582685e068e81226f751e46f/Images/1stAttempt.PNG)

3RD attempt by changing activation function for 1st & 2nd hidden layer to "relu" and for 3rd layer "tanh"

![git-hub](https://github.com/MonaElahi/Neural_Network_Charity_Analysis/blob/9345f73157f444e3582685e068e81226f751e46f/Images/3rdattempt1.PNG)

Accuracy acheived 74.04%

# Summary: 
The model accuracy is 73.46% and by using several methods maximum accuracy acheived is 74.71%

### Recommendation
We could further optimize the model by removing more features or adding more data to the dataset.
Random forest classifier from Supervised learning could be used to optimize the performance of the model because Random forest model is 
robust and accurate due to sufficient number of estimators. 

