# Neural_Network_Charity_Analysis

# Overview of the analysis:

The purpose of this analysis is to use the knowledge of machine learning and neural networks to use the provided dataset's features to help Beks create a binary classifier to predict the success rate of the applicants if funded by Alphabet Soup.

# Results

## Data Preprocessing

* APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT variables are to be the features for our model.

* IS_SUCCESSFUL is considered the target for our model.

* EIN and NAME are neither targets nor features removed from the input data.

## Compiling, Training, and Evaluating the Model

* The neural network model is built to improve the model performance with input features & two hidden layers with  80,30 neurons and an output layer of 1. Each layer has an activation function. The first and second hidden layers have an activation function relu, sigmoid, and the activation function for the output layer is sigmoid.

<img width="903" alt="Screen Shot 2022-07-10 at 1 43 16 PM" src="https://user-images.githubusercontent.com/100738688/178156382-0c16fc8f-d106-4d76-b00c-6cbffee273d4.png">


 * I was not able to achieve the target model performance.
 
 * I tried to improve the model's performance by changing the activation type, adding hidden layers,  increasing neurons in each layer, and increasing the number of epochs.

# Summary:

The initial neural network had an accuracy of 72%. As I added more hidden layers, changed activation, and increased neurons, model accuracy dropped to 63%. This loss in accuracy may be because of model overfitting.
I would recommend the random forest classifier model as random forests are much less likely to overfit as they are made up of many weak learner algorithms (decision trees) on entirely different subsets of the training data.



