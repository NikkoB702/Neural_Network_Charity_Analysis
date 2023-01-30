# Neural_Network_Charity_Analysis

## Overview

Alphabet Soup is a philanthropist group that is looking to optimize their process in determining who should receive investments. We were tasked with creating a binary classifier using machine learning techniques. With data compiled from over 34,000 organizations that have received funding through a CSV file our goal was to create a model that achieved over 75% accuracy. 

## Results

* What variables are considered the target(s) for your model?

Our target variable will be the “Is_Successful,” column

* What variables are the features for your model?

Variables that represent features are Application type, affiliation, classification, use case, organization, status, income amount, special considerations, request amount.

* What variables are neither targets nor features, and should be removed from the input data?

We dropped two columns, “EIN” and “Name” after we determined they were of no value to us. 

##### Compiling, training and evaluating the model

* How many neurons, layers, and activation functions did you select for your neural network model and why?

The original model consists of two layers consisting of 80 and 30 neurons. The input activation function was relu and our output activation function was sigmoid. Our original model ran for 30 epoch and resulted in an accuracy score of 59% with a loss of 80%

* What steps did you take to try to increase the model performance?

Our first step to optimizing our model performance was to add a third hidden layer using 80, 30, and 15 neurons respectively. We ran this model for 100 epoch and resulted in a 73% accuracy. Keeping those same specs we created a new model and altered the input activation function from relu to tanh. This resulted in a 73% accuracy score. Keeping those specs intact we created a third model and altered the epoch from 100 to 200 which resulted in roughly the same 73% we’ve clipped in the previous attempts.

* Were you able to achieve the target model’s performance?

We were unable to reach the target model performance standard.

##### Summary

Although we weren’t able to achieve the desired 75% accuracy rate, I would say we are on the right track, clipping a 73% score. Some more alterations to our existing machine learning model could achieve our goal. Alternatively, I would recommend a support vector machine model. SVM is a binary classifier 
