# hw_21_deep_learning

## Overview of the Analysis
With our knowledge of machine learning and neural networks, the purpose of this analysis is to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup

## Results

Data Preprocessing
- The variables that are targeted are if it was successful
- The variable that are features are Application type, Affliliation, classification, use case, organizations, status, income AMT, special considerations, and ask AMT.
- The variables that were dropped were name and EIN

Compiling, Training, and Evaluating the model
- I added 3 hidden layers and 1 output layer. I have 300 neurons and the activation function of relu for the first hidden layer, secound layer has 200 neurons and activation function of sigmoid, and lastly third hidden layer of 100 neurons and activation function of sigmoid. I didn't believe 2 hidden layers were enough and i did see a boast when adding a third but not as much when adding a fourth. I had tested out with more neurons origninally but the time it took to have it running and not seeing results that justify having it run for longer. The activation function was originally all relu but a tutor suggested using sigmoid, but the results were the same.
- I would of preffered getting better results but this is an acceptable target model performance
- Adding more layers and more neurons were provided the greatest increase in model performance

## Summary
The learning model achieved an accuracy of 0.7290 and a loss of 0.5677, while the results are acceptable, a different model could definetly achieve a better result
