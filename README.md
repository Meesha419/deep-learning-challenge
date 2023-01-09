# deep-learning-challenge
###### Alphabet Soup Foundation Funding Outcome Predictor using hyper-tuned Neural Networks.


## Report on the Neural Network Model

## *Overview*
With the attached tool - Neural network, Alphabet Soup Foundation can predict, which applicants would be able to fund thier ventures and have a higher rate of success.  The tool will create a binary classification from the given data set and will predict whether the applicants will be successful if funded by Alphabet Soup Foundation.  

## *Results*


Target Variable for the model:
- IS_SUCCESSFUL

Feature Variables for the model:

- APPLICATION_TYPE
- AFFILIATION
- CLASSIFICATION
- USE_CASE
- RGANIZATION
- TATUS
- INCOME_AMT
- SPECIAL_CONSIDERATIONS
- ASK_AMT

## *Summary* ##
*The final optimized neural network trained model from the keras tuner method achieved 80% prediction accuracy with a 0.45 loss, using a sigmoid activation function with input node of 76; 5 hidden layers at a 16, 21, 26, 11, 21, neurons split and 50 training epochs. Performing better than the non automized model. Keeping the Name column was crucial in achieving and and going beyond the target. This shows the importance of the shape of your datasets before you preprocess it.*
