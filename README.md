# deep-learning-challenge

##Overview of the analysis: 

This project aims to use a deep-learning neural network with TensorFlow library to analyze and classify the success of charitable donations from Alphabet Soup.

#Results: 
Using bulleted lists and images to support your answers, address the following questions:

#Data Preprocessing

* The target variable was the 'IS_SUCCESFUL' column;

* The feature variables were columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', 'ASK_AMT'.

* The variable columns 'EIN' and 'NAME' were dropped because they were neither targets nor features.

#Compiling, Training, and Evaluating the Model

#MODEL 1
* For the First model, there were 2 layers, with 16 and 25 neurons repectively. All layers had relu activation functions. In addition, the output layer had a sigmoid activation function. 
#MODEL 2
 * For the Second model, there were 2 layers, with 55, 6, 50, 100, and 40 neurons repectively. All layers had relu activation functions. In addition, the output layer had a sigmoid activation function. 
#MODEL 3
* For the Third model, there were 2 layers, with 55, 6, 50, 100, 4, 32, and 32 neurons repectively. All layers had relu activation functions. In addition, the output layer had a sigmoid activation function. 

All 3 models were unable to achieve the target model performance. Model 1 had a loss of 56% and an accuracy of 72.9%. Model 2 had a loss of 56% and an accuracy of 73%. Lastly Model 3 had a loss of 55% and an accuracy of 73%. 

The steps I took to increase model performance was confirming the data inputed into the model was clean, I increased the number of neuron in each of the layers and lastly I increased the number of layers in each model. 

#Summary

Summary: The models were unable to perform a 75% accuracy rate. All of them performed at a success rate of 73%, no matter how many neurons and layers were added. Potentially, improvements can be made witht eh imput data. 